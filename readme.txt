https://htmlcolorcodes.com/

Задній фон
Колір
body{background:red;}

Картинка
body{background:url("logo.png");}

Картинка і колір
body{background:red url("logo.png");}

налаштування фону

background-size:50%; - розмір фону
background-repeat:no-repeat; - повторення фону
background-position:50%; - позиція фону
background-attachment:fixed; - прикріплення фону (фон не прокручується) 
Текст
#text{
color:blue; Колір
font-size:20px; Розмір
font-family:Comic Sans MS; Вигляд(шрифт)
}
#apelsynky{
width:400px; - ширина
height:250px;- висота

box-shadow:0px 0px 50px orange; - тінь
border-radius:50px; - округлення
}
<img src="1517496734-8689.jpg" align="center" id="apelsynky">-вставка зображення
Списки
Нумерований
<ol type="A"> типи 1 I i A a
<li>element
<li>element
<li>element
<li>element
<li>element
</ol>
Markovanyi			type =  disk circle square
<ul type="disk">
<li>element
<li>element
<li>element
<li>element
</ul>
<hr width="200px" size="10px" color="white" align="left"> -лінія

Блоки
<html>
<head>
<link href="https://fonts.googleapis.com/css?family=Roboto&display=swap" rel="stylesheet">
<style>
header{
width:100%;
height:45px;
background:black;
color:whitesmoke;
font-size:30px;
position:fixed;
top:0;
left:0;
}
body{
margin:0;
margin-top:60px;
font-family: 'Roboto', sans-serif;
}
#block1{width:100%;
height:400px;
background:white url("background1.png");
background-repeat:no-repeat;
background-position:100% 50%;
}
#knopka{background:#494EEE;
text-decoration:none;color:white;font-size:25pt; 
width:150px;
height:50px;
border-radius:20px;
padding:5px;
text-align:center;
position:relative;
top:200px;left:400px;}
a{text-decoration:none;color:white;}
#block2{width:100%;
height:400px;
background:whitesmoke url("1.png");margin-top:0;}
</style>
</head>

<body>
<header>BEZ INTERNETU</header>
<main>
<div id="block1">
<div id=knopka>
<a href="http://github.com">GitHub</a>
</div>
</div>
<div id="block2"><h1 align="center">Нарешті</h1>
<p>Введіть ваш текст</p></div>

