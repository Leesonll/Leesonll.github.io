/*居中对齐*/
.demo{
    justify-content: center;
    display: flex;
    margin-right: 10px;
    background-color: #ffffff;
}
/* 清除li样式 */
.demo ul,li{
    list-style: none;
    padding: 0;
}
div{
    text-align: center;
}
/* ul弹性盒，让li横着排*/
.demo .demo_ul{
    position: relative;
    display: flex;
    width: 500px;
    margin-top: 50px;
}
/* 三个li平分宽度*/
.demo .demo_li{
    flex:1;
    height: 40px !important;
}
/* 隐藏input */
.demo .active{
    display:none;
}
.demo input+label{
    display: block;
    height: 40px;
    background: #d5e4f9cc;
    text-align: center;
    line-height: 40px;
    color: #333;
    border: 1px solid #e8e4e4;
}
.demo input+label+div{
    display:none;
    position: absolute;
    left:0;
    top:50px;
}
.demo input:checked+label{
    border-bottom: none;
    background: #fff;
    color: #5c80ea;
    text-align: center;
}
.demo input:checked+label+div{
    display:block;
}
