<!DOCTYPE html>
<html>
<head>
	<link rel="stylesheet" type="text/css" href="mystyle.css">
	<meta charset="utf-8">
	<title>Qi73</title>
   <style type="text/css" media="screen">
    body{
        background-image: url(D:/Html/images/background.jpg);
    }
    ul{
        list-style-type: none;
        margin: 0px;
        padding: 0px;
        overflow: hidden;
        background-color: #333;
        border: 1px solid #ccc!important;
        border-radius: 16px!important;
    }
    li{
        float: left;
        border-right: 1px solid #E0FFFF;
    }
    li a, .dropdown-button{
        display: inline-block;
        padding: 14px 16px;
        text-align: center;
        color: #FFFFFF;
        text-decoration: none;
        font-family: Kaiti;
        font-size: 17px;
    }
    li a:hover, .dropdown:hover, .dropdown-button{
        background-color: #008B8B;
    }
    .active{
        background-color: #000000;
    }
    .dropdown{
        display: inline-block;
    }
    .dropdown-content{
        display: none;
        position: absolute;
        background-color: #3CB371;
        min-width: 160px;
        box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
        border: 1px solid #ccc!important;
        border-radius: 16px!important;
    }
    .dropdown-content a{
        color: #000000;
        padding: 12px 16px;
        text-decoration: none;
        display: block;
    }
    .dropdown:hover .dropdown-content{
        display: block;
    }
    .dropdown-content a:hover{
        background-color: #008B8B;
    }
    .tooltip{
        position: relative;
        display: inline-block;
        border-bottom: 1px dotted black;
    }
    .tooltip .tooltip-text{
        visibility: hidden;
        width: 120px;
        padding: 5px 0px;
        color: #FFFFFF;
        background-color: #333;
        text-align: center;
        border-bottom: 6px;
        position: absolute;
        z-index: 1;
        width: 120px;
        top: 20%;
        border: 1px solid #ccc!important;
        border-radius: 16px!important;
    }
    .tooltip:hover .tooltip-text{
        visibility: visible;
    }
    p{
        font-size: 50px
    }
</style>
</head>

<body>
    <ul>
        <li><div class="tooltip"><a class="active" href="#不要动我！！">首页</a><span class="tooltip-text">这就是首页了</span></div></li>
        <li><div class="tooltip"><a href="#不知道">不知道</a><span class="tooltip-text">就是不知道</span></div></li>
        <div class="dropdown">
            <a href="#看下面！！" class="dropdown-button">关于</a>
            <div class="dropdown-content">
                <a href="..\html\css\待施工.html">第二页（待施工...）</a>
                <a href="https://www.youtube.com"><img src="D:\Html\images\youtube.png" border="-1" width="30" alt="My Youtube"></a></li>
                <a href="https://www.facebook.com"><img src="D:\Html\images\facebook.png" border="-1" width="30" alt="My Facebook"></a></li>
                <a href="https://www.instagram.com"><img src="D:\Html\images\instagram.png" border="-1" width="30" alt="My Facebook"></a></li>
            </div>
        </div>
    </ul>
    <p>Tex</p>
    <p>Text</p>
    <p>Text</p>
    <p>Text</p>
    <p>Text</p>
    <p>Text</p>
    <p>Text</p>
    <p>Text</p>
    <p>Text</p>
</body>

</html>
