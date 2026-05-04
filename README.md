<!DOCTYPE html>
<html lang="ru">
<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Marry Me Manas</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
scroll-behavior:smooth;
}

body{
font-family:'Poppins',sans-serif;
background: linear-gradient(180deg,#ffffff,#f7f7f7);
color:#333;
}

/* HEADER */

header{
position:fixed;
width:100%;
background:rgba(255,255,255,0.9);
backdrop-filter:blur(10px);
padding:15px 0;
z-index:1000;
box-shadow:0 5px 20px rgba(0,0,0,0.05);
}

nav{
display:flex;
justify-content:center;
gap:40px;
}

nav a{
color:#333;
text-decoration:none;
font-weight:500;
}

nav a:hover{
color:#d4af37;
}

/* HERO */

.hero{
height:100vh;
background:url('https://images.unsplash.com/photo-1519741497674-611481863552') center/cover no-repeat;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
color:white;
position:relative;
}

.hero::after{
content:"";
position:absolute;
width:100%;
height:100%;
background:rgba(0,0,0,0.45);
}

.hero-content{
position:relative;
z-index:1;
animation:fadeUp 1.5s ease;
}

.hero h1{
font-size:60px;
font-family:'Playfair Display',serif;
margin-bottom:10px;
}

.hero p{
font-size:22px;
margin-bottom:25px;
}

.btn{
background: linear-gradient(45deg,#d4af37,#f5d76e);
color:white;
padding:15px 35px;
border-radius:30px;
text-decoration:none;
font-weight:600;
display:inline-block;
transition:0.3s;
box-shadow:0 5px 20px rgba(212,175,55,0.4);
}

.btn:hover{
background:white;
color:#d4af37;
}

/* SECTION */

.section{
padding:100px 20px;
text-align:center;
background:white;
margin:40px auto;
max-width:1200px;
border-radius:25px;
box-shadow:0 10px 40px rgba(0,0,0,0.05);
}

.section h2{
font-size:40px;
font-family:'Playfair Display',serif;
color:#d4af37;
margin-bottom:40px;
}

/* PRICING */

.pricing{
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:40px;
}

.card{
background: linear-gradient(145deg,#ffffff,#f9f9f9);
width:350px;
padding:40px;
border-radius:25px;
box-shadow:0 10px 30px rgba(0,0,0,0.08);
transition:0.3s;
}

.card:hover{
transform:translateY(-10px) scale(1.02);
box-shadow:0 20px 50px rgba(0,0,0,0.12);
}

.card h3{
color:#d4af37;
margin-bottom:20px;
}

.old{
text-decoration:line-through;
color:#999;
font-size:18px;
}

.new{
font-size:28px;
font-weight:700;
color:#d4af37;
}

.card.vip{
border:2px solid #ff4d6d;
background: linear-gradient(145deg,#fff5f7,#ffffff);
}

.card.vip h3{
color:#ff4d6d;
}

/* EXTRA SERVICES */

.extra-services{
margin-top:20px;
padding:15px;
border-radius:15px;
background:#fafafa;
box-shadow: inset 0 0 10px rgba(0,0,0,0.05);
}

.extra-services h4{
margin-bottom:10px;
color:#d4af37;
}

.extra-services ul{
list-style:none;
}

.extra-services li{
margin:6px 0;
}

/* INSTAGRAM */

.insta-btn{
background: linear-gradient(45deg,#f09433,#e6683c,#dc2743,#cc2366,#bc1888);
color:white;
padding:12px 30px;
border-radius:30px;
text-decoration:none;
display:inline-block;
margin-top:10px;
font-weight:600;
box-shadow:0 5px 20px rgba(0,0,0,0.2);
}

/* WHATSAPP FLOAT */

.whatsapp{
position:fixed;
bottom:20px;
right:20px;
background:#25D366;
color:white;
padding:15px 20px;
border-radius:50px;
font-weight:600;
text-decoration:none;
box-shadow:0 10px 30px rgba(0,0,0,0.3);
}

/* FOOTER */

footer{
background:#111;
color:white;
padding:30px;
text-align:center;
border-top-left-radius:20px;
border-top-right-radius:20px;
}

/* ANIMATION */

@keyframes fadeUp{
from{
opacity:0;
transform:translateY(40px);
}
to{
opacity:1;
transform:translateY(0);
}
}

/* MOBILE */

@media(max-width:768px){

.hero h1{
font-size:38px;
}

.hero p{
font-size:18px;
}

nav{
gap:20px;
}

.card{
width:90%;
}

}

</style>
</head>

<body>

<header>
<nav>
<a href="#home">Главная</a>
<a href="#about">О нас</a>
<a href="#price">Пакеты</a>
<a href="#contact">Контакты</a>
</nav>
</header>

<section class="hero" id="home">
<div class="hero-content">
<h1>Предложение руки и сердца ❤️</h1>
<p>Красивое оформление предложения</p>
<a href="https://wa.me/996509298741" class="btn">Заказать через WhatsApp</a>
</div>
</section>

<section class="section" id="about">
<h2>О нас</h2>
<p>
Marry Me Manas — мы красиво и незабываемо организуем предложение руки и сердца.
</p>
</section>

<section class="section" id="price">

<h2>Наши пакеты 💍</h2>

<div class="pricing">

<!-- ЭКОНОМ -->
<div class="card">
<h3>Эконом</h3>

<p>
🤍 Большое сердце<br>
💍 Надпись “Will you MARRY ME”<br>
⬜ Дорожка<br>
🌹 Лепестки роз<br>
🕯 Свечи<br>
💐 Цветы<br>
🎶 Музыка<br>
🎇 4 холодных фонтана<br>
📷❌ без мобилографа<br>
</p>

<p>🚗 Установка — бесплатно</p>

<div class="new">6000 сом</div>

<div class="extra-services">
<h4>✨ Дополнительные услуги</h4>
<ul>
<li>💥 Салют 7–19 залпов — 1500–6500 сом</li>
<li>🎇 Фонтан вертушка (6 шт) — 2500 сом</li>
<li>📷 Мобилограф — договорная</li>
</ul>
</div>

<br>
<a href="https://wa.me/996509298741" class="btn">Заказать</a>
</div>

<!-- ЭКОНОМ + -->
<div class="card">
<h3>Эконом +</h3>

<p>
🤍 Большое сердце<br>
💍 Надпись “Will you MARRY ME”<br>
⬜ Дорожка<br>
🌹 Лепестки роз<br>
🕯 Свечи<br>
💐 Цветы<br>
🎶 Музыка<br>
🎇 4 холодных фонтана<br>
🌀 Вертушка<br>
📷 Мобилограф<br>
</p>

<div class="price">
<span class="old">13000 сом</span><br>
<span class="new">9900 сом</span>
</div>

<div class="extra-services">
<h4>✨ Дополнительные услуги</h4>
<ul>
<li>💥 Салют 7–19 залпов — 1500–6500 сом</li>
<li>🎇 Фонтан вертушка (6 шт) — 2500 сом</li>
<li>📷 Мобилограф — договорная</li>
</ul>
</div>

<br>
<a href="https://wa.me/996509298741" class="btn">Заказать</a>
</div>

<!-- ПРЕМИУМ -->
<div class="card vip">
<h3>Премиум</h3>

<p>
❤️ Большое сердце<br>
💍 Надпись “Will you MARRY ME”<br>
🔤 Большие буквы MARRY ME<br>
🟥 Дорожка<br>
🌹 Лепестки роз<br>
🕯 Свечи<br>
💐 Цветы<br>
🎶 Музыка<br>
🎇 4 холодных фонтана<br>
🎇 Вертушка<br>
📷 Мобилограф<br>
💥 Салют 14–19 залпов<br>
</p>

<div class="price">
<span class="old">15000 сом</span><br>
<span class="new">12900 сом</span>
</div>

<div class="extra-services">
<h4>✨ Дополнительные услуги</h4>
<ul>
<li>💥 Салют 7–19 залпов — 1500–6500 сом</li>
<li>🎇 Фонтан вертушка (6 шт) — 2500 сом</li>
<li>📷 Мобилограф — договорная</li>
</ul>
</div>

<br>
<a href="https://wa.me/996509298741" class="btn">Заказать</a>
</div>

</div>
</section>

<section class="section" id="contact">
<h2>Контакты</h2>
<p>📍 Манас</p>
<p>📱 WhatsApp: 221501222</p>

<a href="https://www.instagram.com/merry.me.manas/" target="_blank" class="insta-btn">
@merry.me.manas
</a>

<br><br>

<a href="https://wa.me/996221501222" class="btn">
Связаться
</a>
</section>

<footer>
© 2026 Marry Me Manas
</footer>

<a href="https://wa.me/996221501222" class="whatsapp">
WhatsApp
</a>

</body>
</html>
