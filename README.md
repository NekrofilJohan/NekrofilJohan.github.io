<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body {
            background-color: rgb(9, 9, 63);
            font-size: 1.5em;
            height: 100vh;
 font-family:monospace;
            display: grid;
            justify-content: center;
            align-items: center;
            flex-direction: column;
        }
    </style>
 
    <style>
        .container {
          width: 310px;
          height:190px;
            display: grid;
 background-color: rgb(114, 114, 163);;
            grid-template-columns: 45px 25px 25px 25px 45px 45px;
            grid-template-rows: 30px 15px 15px 15px 15px 15px;
            border-radius: 5px;
            gap: 15px;
        }
        .item:hover{
            width: 80%;
            height: 80%;
        }
        .cisla:hover{
            width: 110%;
            height: 110%;
        }
        .plus:hover{
            transform: rotate(15deg);
        }
 .cisla{
   width: 100%;
   height: 100%;
    margin-left: 12px;
    font-size: 10px;
color: white;
     background: rgb(72, 72, 165);
     text-align: center;
     padding-top: 2px;
    border-radius: 3px;
    
 }
      .plus{
        margin-left: 12px;
        grid-column:5/5;
        grid-row:5/7;
          width: 100%;
            height: 100%;
            background-color: rgb(9, 9, 63);
            text-align:center;
            color: white;
            font-size: 32px;
            border-radius: 3px;
            padding-top: 2px;
      }
.asd{
    margin-top: 10px;
    margin-left: 12px;
    grid-column: 1/7;
    width: 100%;
            height: 20px;
            background-color: rgb(52, 52, 82);
            text-align: end;
            color:rgb(150, 148, 148);
            font-size: 12px;
            border-radius: 3px;
            padding-top: 5px;
          
}
      .item {      
        margin-left: 12px;
        width: 100%;
            height: 100%;
            background-color: rgb(9, 9, 63);
            color:white;
text-align: center;
border-radius: 3px;
font-size: 10px;
padding-top: 2px;
        }
        .priklad{
            width: 200px;
            height: 30px;
            background: white;
            border-radius: 3px;
        }
    </style>
</head>
 
<body>
    <div class="container">
        <div class="asd">120 + 78 - 20 / 2 </div>
        <div class="item">M/EX</div>
        <div class="item">M+</div>
        <div class="item">M-</div>
       <div class="item">MR</div>
        <div class="item">MC</div>
        <div class="item">GT</div>
        <div class="item">AC</div>
        <div class="cisla">7</div>
        <div class="cisla">8</div>
        <div class="cisla">9</div>
        <div class="item">%</div>
        <div class="item">√</div>
        <div class="item">±</div>
        <div class="cisla">4</div>
        <div class="cisla">5</div>
        <div class="cisla">6</div>
        <div class="item">x</div>
        <div class="item">÷</div>
        <div class="item">➤</div>
        <div class="cisla">1</div>
        <div class="cisla">2</div>
        <div class="cisla">3</div>
        <div class="plus">+</div>
        <div class="item">-</div>
        <div class="item">C</div>
        <div class="cisla">0</div>
        <div class="cisla">00</div>
        <div class="cisla">.</div>
        <div class="item">=</div>
        

    </div>
<script defer src="https://static.cloudflareinsights.com/beacon.min.js/v652eace1692a40cfa3763df669d7439c1639079717194" integrity="sha512-Gi7xpJR8tSkrpF7aordPZQlW2DLtzUlZcumS8dMQjwDHEnw9I7ZLyiOj/6tZStRBGtGgN6ceN6cMH8z7etPGlw==" data-cf-beacon='{"rayId":"6cad5431deb47172","version":"2021.12.0","r":1,"token":"25d9f0f0107d43049faf6db7784267e7","si":100}' crossorigin="anonymous"></script>
</body>
