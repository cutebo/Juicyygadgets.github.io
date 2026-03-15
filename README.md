<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>JuicyyGadgets</title>

<style>

body{
margin:0;
font-family:Arial;
background:#020617;
color:white;
overflow-x:hidden;
}

/* iPhone background animation */

.bg{
position:fixed;
top:0;
left:0;
width:100%;
height:100%;
z-index:-1;
opacity:0.05;
font-size:70px;
animation:move 25s linear infinite;
}

@keyframes move{
0%{transform:translateY(100%);}
100%{transform:translateY(-100%);}
}

/* header */

header{
text-align:center;
padding:25px;
background:#020617;
box-shadow:0 0 15px #00f2ff;
}

header h1{
color:#00f2ff;
font-size:40px;
}

/* network signal animation */

.signal{
display:flex;
justify-content:center;
margin-top:10px;
}

.bar{
width:8px;
margin:3px;
background:#00f2ff;
animation:signal 1s infinite;
}

.bar:nth-child(1){height:10px;}
.bar:nth-child(2){height:15px;animation-delay:.2s;}
.bar:nth-child(3){height:20px;animation-delay:.4s;}
.bar:nth-child(4){height:25px;animation-delay:.6s;}

@keyframes signal{
0%{opacity:.3;}
50%{opacity:1;}
100%{opacity:.3;}
}

/* hero section */

.hero{
text-align:center;
padding:40px;
}

.hero h2{
color:#00f2ff;
font-size:32px;
}

/* contact buttons */

.contacts{
text-align:center;
margin:20px;
}

.contacts a{
display:inline-block;
margin:10px;
padding:12px 22px;
background:#00f2ff;
color:black;
border-radius:6px;
text-decoration:none;
font-weight:bold;
}

.contacts a:hover{
background:#06b6d4;
}

/* product grid */

.store{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:20px;
padding:40px;
}

.card{
background:#020617;
padding:20px;
border-radius:10px;
text-align:center;
box-shadow:0 0 10px black;
transition:.3s;
}

.card:hover{
transform:scale(1.05);
box-shadow:0 0 15px #00f2ff;
}

.card img{
width:100%;
border-radius:10px;
}

/* iphone gallery */

.iphones{
padding:40px;
text-align:center;
}

.iphones h2{
color:#00f2ff;
margin-bottom:30px;
}

.phonegrid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
gap:20px;
}

.phone{
background:#020617;
padding:20px;
border-radius:10px;
box-shadow:0 0 10px black;
}

.phone img{
width:100%;
border-radius:10px;
}

footer{
text-align:center;
padding:20px;
background:#020617;
}

</style>
</head>

<body>

<div class="bg">
📱 📱 📱 📱 📱 📱 📱 📱 📱 📱
</div>

<header>

<h1>JuicyyGadgets</h1>

<div class="signal">
<div class="bar"></div>
<div class="bar"></div>
<div class="bar"></div>
<div class="bar"></div>
</div>

</header>

<section class="hero">

<h2>Best Place To Buy • Sell • Swap Gadgets</h2>

<p>
JuicyyGadgets is your trusted gadget store where you can buy,
sell or swap smartphones and accessories.  
We specialize in iPhones and premium gadgets with reliable service.
</p>

</section>

<div class="contacts">

<a href="https://wa.me/08119505986" target="_blank">WhatsApp</a>

<a href="https://www.tiktok.com/@juicyyvibez?_r=1&_t=ZS-94hy46tkUYW" target="_blank">TikTok</a>

<a href="mailto:empireemmanuel4@gmail.com">Email</a>

</div>

<section class="store">

<div class="card">
<img src="https://via.placeholder.com/300x200">
<h3>AirPods Pro</h3>
</div>

<div class="card">
<img src="https://via.placeholder.com/300x200">
<h3>Apple Watch</h3>
</div>

<div class="card">
<img src="https://via.placeholder.com/300x200">
<h3>Bluetooth Speaker</h3>
</div>

</section>

<section class="iphones">

<h2>Available iPhones</h2>

<div class="phonegrid">

<div class="phone"><img src="https://via.placeholder.com/300x200"><h3>iPhone 11</h3></div>
<div class="phone"><img src="https://via.placeholder.com/300x200"><h3>iPhone 12</h3></div>
<div class="phone"><img src="https://via.placeholder.com/300x200"><h3>iPhone 13</h3></div>
<div class="phone"><img src="https://via.placeholder.com/300x200"><h3>iPhone 14</h3></div>
<div class="phone"><img src="https://via.placeholder.com/300x200"><h3>iPhone 15</h3></div>
<div class="phone"><img src="https://via.placeholder.com/300x200"><h3>iPhone 16</h3></div>
<div class="phone"><img src="https://via.placeholder.com/300x200"><h3>iPhone 17 Pro Max</h3></div>

</div>

</section>

<footer>

<p>© 2026 JuicyyGadgets | Buy • Sell • Swap</p>

</footer>

</body>
</html>
