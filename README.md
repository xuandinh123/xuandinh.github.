<!DOCTYPE html>
<html>
    <head>
         <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Tống Xuân Định - Top 1 Osu!standard của Thành Phố Nam Định">
    <meta name="keywords" content="Tống Xuân Định, Top 1 Nam Định, osu! Nam Định">
    <meta name="author" content="Tống Xuân Định">
    <title>Tong Xuan Dinh</title>
    <style>
        *{
            margin:0;
            padding :0;
            box-sizing: border-box;
            font-weight: bold; 
            font-style: italic; 
            
        }
        h1{
            text-align: center;
            font-weight: bold; 
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif; 
            font-size: 50px;
        }
        .header {
            width: 100%;
            background-color: rgb(0, 0, 0);
            margin: 0;
            padding: 0;
            height: 100px;
            position: fixed;
            z-index: 100;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-sizing: border-box;
            overflow-x: hidden;
        }

        .left_header {
            display: flex;
            align-items: center;
        }

        .center_header {
            display: flex;
            align-items: center;
        }

        .right_header {
            display: flex;
            align-items: center;
        }

        ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            width: 100%;
        }

        li {
            display: flex;
            padding: 10px;
            padding-top: 40px;
            background-color: rgb(0, 0, 0);
            color: white;
            justify-content: center;
            text-align: center;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            border: 1px solid #000000;
            height: 100px;
            border-radius: 20px;
            box-sizing: border-box; 
        }
        li img{
            display: flex;
            background-color: rgb(0, 0, 0);
            color:white;
            justify-content: center;
            text-align: center;
        }
        li:hover{
            background-color: rgb(255, 0, 0);
            color:rgb(255, 255, 255);
        }
        
        .eula{
             
             width: 100%;
             height:910px;
        }
        .static{
            width:600px;
            height:250px;
            border:2px solid black;
            background-color: black;
            border-radius: 20px;
            color:White;
            position: absolute;
            top: 20%;
            left: 5%; 
            padding: 20px;
            font-family:Arial, Helvetica, sans-serif;
            font-weight: bold; 
            font-style: italic; 
            font-size: 30px;
        }
        .static:hover{
            background-color: white;
            color:black;
        }
        .ranked{
            display: flex;
            justify-content: center; 
            width:550px;
            height:100px;
            border-radius: 20px;
            position: fixed;
            
            background-color: rgb(0, 0, 0);
            position: absolute;
            top: 80%;
            left: 5%; 
        }
        .rankedS{
             text-align: center;
            width: 33.3%;
            color: white;
            border: 0.1px solid white;
            display: inline;
            padding: 20px;
            align-items: center;
            font-weight: bold; 
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif; 
            font-size: 15px;
            border-radius: 20px;
        }
        .rankedS:hover{
            background-color: white;
            color:black;
        }
        .names{
            display: flex;
            justify-content: center; 
            width:850px;
            height:100px;
            border-radius: 20px;
            position: fixed;
            color:white;
            background-color: rgb(0, 0, 0);
            position: absolute;
            top: 80%;
            right: 5%; 
            border: 0.1px solid white;
        }
        .names:hover{
            background-color: white;
            color:black;
        }
        .name{
            padding-top: 20px;
            text-align: center;
            font-weight: bold; 
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            font-size: 50px;
            
        }
        .point{
            background-color: #000000;
             width: 100%;
            height:980px;
            padding-left:300px;
            padding-right:300px;
            padding-top: 100px;
        }
         .medal {
            display: flex;
            justify-content: space-around; 
            padding: 40px;
            padding-top: 80px;
            background-color: #000000;
            
        }
        .topmedal {
            text-align: center;
            width: 30%;
            padding-top: 40px;
            padding-bottom: 40px;
            border-radius: 10px;
            background-color: #f9f9f9;
            height:50%;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            font-weight: bold; 
            font-style: italic; 
            background-color: white;
            box-shadow: 10px 20px 150px #ffffff;
        }
        .topmedal:hover{
            background-color: rgb(255, 0, 0);
            color:black;
        }
        .mods{
            display: flex;
            justify-content: space-between;
            align-items: center; 
            padding: 40px;
            padding-top: 40px;
            background-color: #000000;
             gap:10px;
        }
        .topmods{
            text-align: center;
            width: 30%;
            padding-bottom: 20px;
            border: 1px solid #000000;
            border-radius: 10px;
            background-color: #ff0000;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            font-weight: bold; 
            font-style: italic; 
            background-color: rgb(0, 0, 0);
            color: #f9f9f9;
            box-shadow: 0px 0px 50px #ffffff;
        }
        .keyboard{
            padding-top :100px;
            background-color: #3c0080;
            height:895px;
        }
        .info{
            padding: 20px;
            display: flex;
            align-items: center;
             font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            font-weight: bold; 
            font-style: italic; 
            font-size: 25px;
            color: white;
        }
       
        .kb1 {
           width:48%;
            margin-bottom: 30px;
            padding: 50px;
           color:white;
            border-radius: 8px;
            background-color: #000000;
            border:1px solid black;
            box-shadow: 10px 20px 150px #000000;
        }
        .kb2{
            width:48%;
            margin-bottom: 30px;
            
            padding: 20px;
           color:rgb(0, 0, 0);
            border-radius: 8px;
            background-color: #ffffff;
            border:1px solid black;
            box-shadow: 10px 20px 150px #000000;
        }
        .kb p {
            font-size: 18px;
            color: rgb(0, 0, 0);
            padding: 10px;
            line-height: 1.5;
            font-weight: bold; 
            font-style: italic; 
            font-size: 35px;
        }
        .lowkb{
             display: flex;
            justify-content: space-between;
            
        }
        .maps h1{
            text-align: center;
            color: #00ff00;
            padding-top: 40px;
            font-size: 45px;
            padding-bottom: 40px;
             font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            font-weight: bold; 
            font-style: italic; 
        }
        .kb1 p{
            text-align: right;
            color: #ffffff;
            padding-top: 40px;
            font-size: 25px;
            padding-bottom: 40px;
             font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            font-weight: bold; 
            font-style: italic; 
            
        }
        .kb2 p{
            text-align: left;
            color: #000000;
            padding-top: 40px;
            font-size: 25px;
            padding-bottom: 40px;
             font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            font-weight: bold; 
            font-style: italic; 
        }
        .mapart{
            display: flex;
            justify-content: center;
            height:620px;
            
            
        }
        .allmaps{
            width: 33.3%;
            background-color: hwb(0 17% 76%);
            background-repeat: no-repeat;
            background-position: center;
            background-size: cover;
            overflow: hidden;
            display: flex;
            flex-direction: column; 
            justify-content: space-between; 
            height: 100%
        }
        .allmaps img {
            width: 100%;
            height: 400px;
            
        }
        .artist{
            width: 33.3%;
            background-color: #00ff00;
            align-content:flex-start;
            background-repeat: no-repeat;
            background-position: center;
            background-size: cover;
        }
        .jss{
            text-align: center;
             font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            font-weight: bold; 
            font-style:initial; 
            font-size: 30px;
        }
        .count{
            padding-top :100px;
            background-color: #800000;
            height:895px;
        }
        
      .register-form {
            background-color: #d400ff;
            padding: 40px;
            width: 100%;
            height:auto;
            padding-top:100px;
            margin:  auto;
            font-family: Arial, sans-serif;
            color: rgb(0, 0, 0);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }
        .form-group {
            display: flex;
            align-items: center;
            justify-content:center;
            margin-bottom: 15px;
        }

        .form-group label {
            flex: 1;
            font-size: 18px;
            color: #000000;
            box-shadow: 10px 20px 150px #000000;
        }

        .form-group input[type="text"],
        .form-group input[type="password"] {
            flex: 2;
            padding: 12px;
            border: 1px solid #ccc;
            border-radius: 4px;
            font-size: 16px;
            box-shadow: 10px 20px 150px #000000;
        }
        .register-form button {
            width: 100%;
            height: 70px;
            background-color: #000000;
            color: #ffffff;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 18px;
        }

        .register-form button:hover {
            background-color: #ff0000;
        }
        .tablet{
            padding-top :50px;
            background-color: #00ff55;
            height:895px;
            text-align: center;
        }
        .tbinfo{
            display: flex;
            justify-content: center;
            text-align: center;
            background-color: #00ff00;
            
        }
        .tbinfo img{
            max-width: 500px;
            margin-right:40px;
        }
        .tbinfo p{
            margin = 0;
            text-align: left;
            position:relative;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            font-weight: bold; 
            font-style: italic; 
            margin-top: 100px;
        }
        .team{
             padding-top :50px;
            background-color: #000000;
            height:895px;
            color:#f9f9f9;
        }
        .players{
            display: flex;
            justify-content: center;
            align-items: center;
            box-shadow: 10px 20px 150px #f8f8f8;
        }
        .pls{
            width:25%;
            height:691px;
            text-shadow: 
                -1px -1px 0 #000, 
                1px -1px 0 #000,  
                -1px 1px 0 #000,  
                1px 1px 0 #000; 
            border:1px solid rgb(255, 0, 0);
            background-repeat: no-repeat;
            background-position: center;
            background-size: cover;
            opacity: 0.7;
            display: flex;
            justify-content: center;
            align-items: center;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            font-weight: bold; 
            font-style: italic; 
            font-size: 50px;
            color:#800000;
        }
        .pls:hover{
            opacity: 1;
            color:white;
        }
        .pls:nth-child(1){
            background-image: url("lucia1.jpg");
            
        }
        .pls:nth-child(2){
            background-image: url("texas.jpg");
            
        }
        .pls:nth-child(3){
            background-image: url("elua.png");
            
        }.pls:nth-child(4){
            background-image: url("wolf.jpeg");
            
        }
        .game{
             padding-top :50px;
            background-color: #fffffff;
            height:auto;
            text-align: center;
            
           
        }
        .anothergame {
            display: flex;
            flex-direction: row;
            flex-wrap: wrap;
            gap: 10px;
            height: fit-content;
            justify-content: center;
        }

        .games {
            display: flex;
            align-items: center;
            padding: 10px;
            border: 1px solid #c300ff; 
            background-color: #000000; 
            width: 260px;
            box-sizing: border-box; 
            border-radius: 10px;
            box-shadow: 5px 5px 50px #000000;
        }

        .image {
            width: 100px; 
            height: 100px; 
            border-radius: 10px;
            background-size: cover;
            background-repeat: no-repeat; 
            background-position: center; 
            margin-right: 10px; 
        }

        .games span {
            flex:1;
            text-align: center; 
            font-size: 16px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            font-weight: bold; 
            font-style: italic; 
            font-size: 20px;
            color:#f9f9f9;
        }
        .gms:nth-child(1) .games .image /*<- phai co dau cach giua games va image ->*/
        {
             background-image: url("ic1.png");
        }
        .gms:nth-child(2) .games .image
        {
            background-image: url("ic2.png");
        }
        .gms:nth-child(3) .games .image
        {
            background-image: url("ic3.webp");
        }
        .gms:nth-child(4) .image
        {
            background-image: url("ic4.png");
        }
        .gms:nth-child(5) .games .image
        {
            background-image: url("ic5.jpg");
        }
        .gms:nth-child(6) .games .image
        {
            background-image: url("ic6.png");
        }
        .gms{
            width:290px;
            height:600px;
            border:1px solid rgb(255, 0, 0);
            background-repeat: no-repeat;
            background-position: center;
            background-size: cover;
            box-shadow: 10px 20px 150px #000000;
            display: flex;
            justify-content: center;
            align-items: center;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            font-weight: bold; 
            font-style: italic; 
            font-size: 50px;
            color:#800000;
            border-radius: 10px;
            
        }
        .gms:nth-child(1){
            background-image: url("ww1.jpg");
        }
        .gms:nth-child(2){
            background-image: url("ww2.jpg");
        }
        .gms:nth-child(3){
            background-image: url("ww3.jpg");
        }
        .gms:nth-child(4){
            background-image: url("ww4.jpg");
        }
        .gms:nth-child(5){
            background-image: url("ww5.jpg");
        }
        .gms:nth-child(6){
            background-image: url("ww6.webp");
        }
        .ending {
            display: flex;
            justify-content: center; 
            align-items: center; 
            height: 120px;
            margin: 0; 
            background-color: #ffffff; 
        }

        .end {
            height: 120px;
            display: flex;
            justify-content: center;
            align-items: center;
            width: 800px;
            background-color: #000000;
            border-radius: 10px;
            color:#ffffff;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            font-weight: bold; 
            font-style:normal; 
            font-size: 15px;
            padding:20px;
        }
        
        .end img {
            width: 100px;
            margin-right: 20px;
        }
        .end span{
            width: 300px;
            margin-right: 20px;
        }
        .lapmon{
            background-color: #ccc;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .laptop{
            width:48%;
            background-color: #800000;
            border-radius: 10px;
        }
        .monitor{
            width: 48%;
            background-color: #d400ff;
            border-radius: 10px;
        }
        .laptop img{
            width: 800px;
        }
        .monitor img{
            width: 800px;
        }
        .searching {
            height:auto;
            background-image: url("bg2.webp");
            background-size:cover;
             width: 100%;
             height:850px;
        }
        table {
            text-align: center;
            width: 70%; 
            margin: auto;
        }

        td {
            text-shadow: 
                -1px -1px 0 #ffffff, 
                1px -1px 0 #ffffff,  
                -1px 1px 0 #ffffff,  
                1px 1px 0 #ffffff; 
            border: 1px solid #ddd;
            padding: 10px;
            font-size: 40px;
            height: 100px;
            border-radius: 20px;
            background-color: #000000;
            background-repeat: no-repeat;
            background-size: cover;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            font-weight: bold; 
            font-style: normal;
            display: flex; 
            align-items: center; 
            justify-content: start; 
            gap: 15px; 
            box-shadow: 10px 20px 150px #000000;
            
        }

        td img {
            width: 150px;
            height: 70px;
            border-radius: 10px;
            
        }
        td:hover{
             border: 1px solid #000000;
             color:white;
             background-image: url("exe.png");
        }
    </style>
    </head>
    <body>
        <div class="header">
            <div class="left_header">
                <ul>
                <li>Global Ranking</li>
                <li>Country Ranking</li>
                <li>Top 1% Rating</li>
                </ul>
            </div>
            <div class="center_header">
                <li> <img src="Osu!_Logo_2016.svg.png"></li>
                <li>Tong Xuan Dinh</li>
                <li>Performance Point</li>
                <li>Settings</li>
                <li>Top Mappers</li>
                <li>Rank peaking</li>
                <li>Osu! to Valorant</li>
            </ul>
            </div>
            <div class="right_header">
                <ul>
                <li>World Settings</li>
                <li>Shopping</li>
                <li>Sign in</li>
                </ul>
            </div>
        </div>
        <div class ="jssjv">
            
        </div>
    <div class="main">
        <div class="main-char">
          <img src="backgroundmain.jpg" class="eula" >
        </div>
        <div class="static">
            <p>Điểm Được Xếp Hạng : 5.425.728.315</p>
            <p>Độ Chính Xác : 97,30%</p>
            <p>Số lần chơi : 36.933</p>
            <p>Tổng điểm : 34.233.516.246</p>
            <p>Tổng Lần Bấm : 6.528.884</p>
            <p>Combo Cao Nhất : 1.602</p>
        </div>
        <div class="ranked">
            <div class="rankedS">
                <h3>GLOBAL</h3>
                <h1>1,578</h1>
            </div>
            <div class="rankedS">
                <h3>COUNTRY</h3>
                <h1>273</h1>
            </div>
            <div class="rankedS">
                <h3>CITY</h3>
                <h1>1</h1>
            </div>
        </div>
        <div class="names">
            <p class="name"> RpMDinhVNa9 -<a style="font-size:50px;color:rgb(0, 255, 13)"> SSS </a>- Tống Xuân Định</p>
        </div>
    </div>
    
    <div class ="team">
        <h1>VIETNAM's TEAM</h1>
        <h1 style="margin-bottom:40px;"><====DISTincTed====></h1>
        <div class="players">
            <div class="pls">PhucTraNX6</div>
            <div class="pls">SieuPhanDong</div>
            <div class="pls">RpMDinhVNa9</div>
            <div class="pls">TreEmLaSo1</div>
        </div>
    </div>
    <div class="searching">
        <h1 style=" margin:60px;text-shadow: 
                -1px -1px 0 #ffffff, 
                1px -1px 0 #ffffff,  
                -1px 1px 0 #ffffff,  
                1px 1px 0 #ffffff;font-size:60px; ">ROLES and WINNING TEAM</h1>
    <table class="mid_header">
    <tr>
        <td>
            <img src="x (1).png" >
            Corsace Openning Cup 2nd Place Winning Team
        </td>
    </tr>
    <tr>
        <td>
            <img src="x (2).png" >
            BuddlyBQT 2021 osu!Party Winning Team
        </td>
    </tr>
    <tr>
        <td>
            <img src="x (3).png" >
            Perennial osu!standard 2rd Place 
        </td>
    </tr>
    <tr>
        <td>
            <img src="x (4).png" >
            Osu! World Cup 2021 2rd Place (VIETNAM)
        </td>
    </tr>
    <tr>
        <td>
            <img src="x (5).png" >
            Osu! World Cup 2022 3rd Place (VIETNAM)
        </td>
    </tr>
</table>
</div>
</div>
    <div class="point">
        <h1 style="color:white;text-align:center; font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;font-weight: bold; font-style: italic; ">MEDAL ARCHIVED FROM 11/2021</h1>
        <div class="medal">
            <div class="topmedal">
                 <p><img src="osu-combo-2000.png"></p>
                 <h2>2000 Combo</h2>
                 <h3>5/2021</h3>
                 <p>MAX COMBO</p>
                 <p>Nothing can stop you now</p>
            </div>
            <div class="topmedal">
                <p><img src="osu-skill-fc-8.png"></p>
                <h2>Full combo 8 stars</h2>
                 <h3>2/2022</h3>
                 <p>ABERRATION</p>
                 <p>They said it couldn't be done. They were wrong.</p>
            </div>
            <div class="topmedal">
                <p><img src="all-skill-highranker-4.png"></p>
                <h2>Top 1,000 Global</h2>
                <h3>8/2023</h3>
                <p>APPOARCHING THE SUMMIT</p>
                 <p>Pro tier. Welcome to the top 1,000!</p>
            </div>
            
        </div>
          <h1 style="color:white;text-align:center; font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;font-weight: bold; font-style: italic; ">MOST USED MODS FOR RANKED MAPS (PERFORMANCE POINT)</h1>
          <div class="mods">
            <div class="topmods">
                 <p><img style="width: 120px;height: 120px;" src="selection-mod-hardrock.png"></p>
                 <h1>27%</h1>
                 <p>HARD ROCK x1,06</p>
                 
            </div>
            <div class="topmods">
                <p><img style="width: 120px;height: 120px;" src="selection-mod-hidden.png"></p>
                <h1>40%</h1>
                 <p>HIDDEN x1,06</p>
            </div>
            <div class="topmods">
                <p><img style="width: 120px;height: 120px;" src="selection-mod-doubletime.png"></p>
                <h1>92%</h1>
                 <p>DOUBLE TIME x1,12</p>
            </div>
            <div class="topmods">
                <p><img style="width: 120px;height: 120px;" src="selection-mod-nightcore.png"></p>
                <h1>86%</h1>
                <p>NIGHTCORE x1,12</p>
            </div>
            <div class="topmods">
                <p><img style="width: 120px;height: 120px;" src="selection-mod-fadein.png"></p>
                <h1>9%</h1>
                 <p>FLASHLIGHT x1,06</p>
            
          </div>
    </div> 
    </div>
    <div class="maps">
        <h1>MAPS</h1>
        <div class="mapart">
            <div class="allmaps">
                <img src="Ảnh chụp màn hình 2024-11-11 215942.png" >
                <img src="3nd.png" >
            </div>
            <div class="artist">
                <h1 style="color:#000000">KHẢ NĂNG ĐIỀU KHIỂN MAP  MAX FORCUSING </h1>
                <p class="jss">JUMPS : 62%</p>
                <p class="jss">STREAM : 35%</p>
                <p class="jss">DEATHSTREAM : 3%</p>
               
            </div>
             <div class="allmaps">
                <img src="Ảnh chụp màn hình 2024-11-11 220000.png" >
                <img src="4nd.png" >
             </div>
        </div>
    </div>
    <div class="lapmon">
        <div class="laptop">
            <img src="mon1.jpg">
            <p>GIGABYTE - Laptop Gamming</p>
        </div>
        <div class="monitor">
            <img src="mon2.jpg">
            <p>360HZ gaming monitor</p>
        </div>
    </div>
    <div class="keyboard">
        <h1 style="color:white;text-align:center; font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;font-weight: bold; font-style: italic;font-size:60px;">BEST AND MOST USED KEYBOARD</h1>
        <div class="info">
        <img style="width:4000px;height:700px;float:left;box-shadow: 10px 20px 150px #000000;border-radius:10px;" class="kb"src="Remove-bg.ai_1731176520199.png" >
        <p style="padding:30px">Bàn phím V87 Pro là một bàn phím cơ dạng tenkeyless (TKL), thiết kế nhỏ gọn, chắc chắn, phù hợp cho những ai thích sự tiện dụng và di chuyển. Với các switch cơ học từ Cherry, Gateron, hoặc Outemu, V87 Pro mang đến cảm giác gõ phong phú và bền bỉ. Bàn phím có đèn nền LED tùy chỉnh, hỗ trợ kết nối không dây hoặc USB Type-C, cùng với keycap PBT cao cấp chống mài mòn. Ngoài ra, tính năng tùy chỉnh phím và macro giúp người dùng cá nhân hóa trải nghiệm sử dụng.</p>
        <h3>MECHANICAL EXPERT KEYBOARD FOR OSU!</h3>
        </div>
     </div>
     <div style="background-color:white"class="keyboard">
        <h1 style="color:rgb(0, 0, 0);text-align:center; font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;font-weight: bold; font-style: italic;font-size:60px;">LOW END KEYBOARD</h1>
        <div class="lowkb">
        <div class="kb1">
            <img style=" width: 800px;height: 350px;" src="Remove-bg.ai_1731178228084.png" >
        <p style="padding:30px">Bàn phím giả cơ XUNFOX K82 là bàn phím gaming có dây, với thiết kế công thái học thoải mái, chất liệu ABS bền bỉ và cấu trúc 6 lớp chắc chắn. Bàn phím trang bị 94 phím, có độ bền cao và tính năng Antighosting hỗ trợ khi chơi game. Kết nối USB 3.0, tương thích với nhiều hệ điều hành, cùng đèn LED 7 màu và núm xoay âm lượng tiện lợi, tạo trải nghiệm tốt cho game thủ, đặc biệt trong môi trường thiếu sáng. Nhưng rác.</p>
        </div>
        <div class="kb2">
            <img style=" width: 850px;height: 350px;" src="Remove-bg.ai_1731178563105.png" >
        <span style="padding-top:55px;text-align: left;
            color: #000000;
            padding-top: 40px;
            font-size: 25px;
            padding-bottom: 40px;
             font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            font-weight: bold; 
            font-style: italic; ">(lỗi)Bàn phím cơ LEAVEN K620 là dòng bàn phím siêu nhẹ và bền với trọng lượng chỉ 380 gram và thiết kế 61 phím nhỏ gọn, tiện lợi. Có nhiều màu sắc như đen, trắng, hồng, và xanh, bàn phím sử dụng trục xanh lá cây cho cảm giác gõ sống động và độ bền cao. Keycap từ chất liệu ABS chống dầu và dấu vân tay, cùng hiệu ứng RGB đầy màu sắc với phím chuyển đổi FN + INS. Kết nối USB 3.2 plug-and-play, không cần cài đặt, chân ẩn điều chỉnh độ nghiêng, phù hợp cho game, văn phòng và các môi trường tập thể như câu lạc bộ thể thao điện tử.</span>
        </div>
        </div>
     </div>
     <div class="tablet">
        <h1 >BEST TABLET - VEIKK 480 PRO</h1>
        <div class="tbinfo">
            <img src="tabletV.png">
            <p style="width:30%;padding-top:80px;padding-right:40px;text-align: center;font-size:20px;">Bảng vẽ tốt nhất được thiết kế riêng cho speed player, có khả năng vuốt bút cực nhạy, SENS cực kỳ thích hợp khi HDDT hay HDDTHR, Đây là một màn hình vẽ với kích thước 15.6 inch, rất được yêu thích trong cộng đồng game thủ osu!. Với độ nhạy 8192 mức, và tính năng cảm ứng đa điểm, Gaomon PD1560 mang lại trải nghiệm mượt mà cho người chơi.</p>
            <img src="tbsetting.png">
        </div>
         <p style="padding-top:40px;padding-bottom:40px;color:rgb(0, 0, 0);text-align:center; font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;font-weight: bold; font-style: italic;font-size:60px;">SETTING THẾ GIỚI của <a style="color:white;font-size:100px;">TOP 1</a> NAM DINH </p>
     </div>
     <div class="count">
        <h1>TOP <a style="font-size:80px;color:white">1</a> OSU! STANDARD IN <a style="font-size:80px;color:white">NAM DINH</a> 2022-2023</h1>
        <h1 style="font-size:40px;color:rgb(0, 255, 13)">RpMDinhVNa9 -- Đổi tên lần cuối :21/10/2022</h2>
        <img style="padding:100px;width: 100vw; height: 80vh;" src="6nd.png">

     </div>
     <div class="register-form">
    <h1>ĐĂNG KÝ SOLO TOP 1</h1>
    <form action="#">
        <div class="form-group">
            <label for="fullName">NAME</label>
            <input type="text" id="fullName" name="fullName" required>
        </div>

        <div class="form-group">
            <label for="inGameName">NAME_INGAME</label>
            <input type="text" id="inGameName" name="inGameName" required>
        </div>

        <div class="form-group">
            <label for="password">PASSWORDS</label>
            <input type="password" id="password" name="password" required>
        </div>
        <button type="submit">Đăng Ký</button>
    </form>
</div>
<div class="game">
    <h1 style="padding-bottom:40px;">NGOÀI OSU! THÌ CÒN 6 GAME KHÁC...</h1>
    <div style="padding-bottom:auto;"class="anothergame">
        <div class="gms">
        <div class="games">
            <div class="image"></div>
            <span>ARKNIGHTS</span>
        </div>
        </div>
        <div class="gms">
        <div class="games">
            <div class="image"></div>
            <span>WUTHERING WAVES</span>
        </div>
        </div>
        <div class="gms">
        <div class="games">
            <div class="image"></div>
            <span>PHIGROS</span>
        </div>
        </div>
        <div class="gms">
        <div class="games">
            <div class="image"></div>
            <span>FORZA HORIZON 4</span>
        </div>
        </div>
        <div class="gms">
        <div class="games">
            <div class="image"></div>
            <span>CYBERFUNK 2077 DLC</span>
        </div>
        </div>
        <div class="gms">
        <div class="games">
            <div class="image"></div>
            <span>STRINOVA</span>
        </div>
        </div>
    </div>
    <p style="padding-top:40px;padding-bottom:40px;color:rgb(0, 0, 0);text-align:center; font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;font-weight: bold; font-style: italic;font-size:20px;">Well...vừa top 1 vừa Wibu như thế này thì chắc vẫn còn cứu được</p>
    </div>
    <div class="ending">
    <div class="end">
        <img src="Osu!_Logo_2016.svg.png">
        <span>
        <p>Copyright to Tống Xuân Định</p>
        <p>030705 - 0941****55</p>
        <p>Yew York's Web Domain</p>
        </span>
        <span>
        <p>Contact:</p>
        <p>dinhtong343@gmail.com</p>
        <p>https://osu.ppy.sh/250746 </p>
        </span>
    </div>
    </div>
    </body>
</html>
