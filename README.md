<!DOCTYPE html>
<html>
 <head>
  <meta charset="UTF-8">
  <title></title>
  <style type="text/css">
   *{
    margin: 0;
    padding: 0;
   }
   .top{
    width: 1280px;
             height: 30px;
             margin: 0 auto;
             background-color: forestgreen;
             background-image: linear-gradient(45deg,#0081ff,#1cbbb4);
   }
   .top ul li{
    list-style-type: none;
             font-size: 16px;
             float: left;
             margin-left: 45px;
   }
   .top ul li a{
    text-decoration: none;
             color: black;
             font-weight: bold;
             text-align: center;
             line-height: 30px; 
             display: block;
             width: 140px;
             height: 30px;
             float: left;
   }
   .top ul li a:hover{
             background-color: salmon;
            }
   .sousuo{
    margin-top: 5px;
    margin-left: 60px;
   }
   .body{
    width: 1280px;
    height: 1200px;
    margin: 0 auto;
   }
   .body_left{
    width: 990px;
    height: 100%;
    float: left;
   }
   .body_left_t{
    width:100%;
    height:680px ;
    background-color: antiquewhite;
    box-shadow: 4px 4px 8px 4px slategrey;
    margin-bottom: 20px;
   }
   .body_left_t_1{
    width: 980px;
    height: 380px;
    background-image: url(img/微信图片_20221105093126.jpg);
    margin: 0 auto;
    margin-top: 5px;
    border: 5px solid white;
   }
   .body_left_f{
    width: 100%;
    height: 500px;
    background-color: cornflowerblue;
   }
   .body_right{
    width:250px;
    height:100%;
    background-color: darkmagenta;
    float: right;
    margin-left: 20px;
   }
   h2{
    margin-left: 5px;
             font-size: 20px;
   }
   p{
    text-indent: 2em;
   }
  </style>
 </head>
 <body>
  <div class="top">
   <ul>
    <li>< a href=" ">首页</ a></li>
    <li>< a href="a">热门精选</ a></li>
    <li>< a href="a">攻略游记</ a></li>
    <li>< a href="a">服务中心</ a></li>
    <li>< a href="a">查看更多</ a></li>
   </ul>
   <input class="sousuo" type="text" value="搜索旅游资讯"/>
  </div>
  <div class="body">
   <div class="body_left">
    <div class="body_left_t">
     <div class="body_left_t_1"></div>
     <div class="body_left_t_2">
      <h2>简介</h2>
         <p class="p1"></p >
         <br />
            <p class="p1></p >
     </div>
    </div>
    <div class="body_left_f"></div>
   </div>
   <div class="body_right"></div>
  </div>
 </body>
</html>
   
