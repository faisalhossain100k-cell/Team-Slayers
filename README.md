# Team-Slayers
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SLAYERS eSports</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,Helvetica,sans-serif;
}

body{
background:linear-gradient(135deg,#eef5ff,#dce4ec);
color:#093b6d;
}

header{
background:white;
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 10%;
box-shadow:0 5px 20px rgba(0,0,0,.1);
}

.logo{
font-size:35px;
font-weight:bold;
color:#0077ff;
text-shadow:0 0 10px #66b3ff;
}

nav a{
margin-left:20px;
text-decoration:none;
color:#093b6d;
font-weight:bold;
}

.hero{
padding:80px 10%;
display:flex;
justify-content:space-between;
align-items:center;
flex-wrap:wrap;
}

.hero h1{
font-size:60px;
color:#0077ff;
text-shadow:0 0 15px #66b3ff;
}

.hero p{
margin-top:20px;
font-size:20px;
}

.btn{
display:inline-block;
margin-top:25px;
padding:15px 35px;
background:#0077ff;
color:white;
text-decoration:none;
border-radius:30px;
font-weight:bold;
}

.logoimg{
width:300px;
border-radius:20px;
box-shadow:0 0 30px #6cbcff;
}

.players{
padding:60px 10%;
}

.title{
text-align:center;
font-size:40px;
margin-bottom:40px;
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.card{
background:white;
padding:25px;
border-radius:20px;
box-shadow:0 5px 20px rgba(0,0,0,.15);
transition:.3s;
}

.card:hover{
transform:translateY(-10px);
}

.card h2{
color:#0077ff;
margin-bottom:10px;
}

.notice{
padding:60px 10%;
text-align:center;
}

.notice h2{
font-size:40px;
color:#0077ff;
}

footer{
background:#dce4ec;
padding:25px;
text-align:center;
margin-top:40px;
}
</style>

</head>
<body>

<header>

<div class="logo">SLAYERS</div>

<nav>
<a href="#">Home</a>
<a href="#">Players</a>
<a href="#">About</a>
<a href="#">Contact</a>
</nav>

</header>

<section class="hero">

<div>

<h1>Rush.<br>Dominate.<br>Conquer.</h1>

<p>Professional Free Fire eSports Team</p>

<a href="#" class="btn">Join SLAYERS</a>

</div>

<img src="logo.png" class="logoimg">

</section>

<section class="players">

<h1 class="title">OUR PLAYERS</h1>

<div class="cards">

<div class="card">
<h2>SL.Tornado</h2>
<h3>First Rusher</h3>
<p>Ultra aggressive entry fragger with incredible speed and close-range combat.</p>
</div>

<div class="card">
<h2>SL.Ismail</h2>
<h3>Support Rusher</h3>
<p>Supports Tornado in every push and protects teammates during fights.</p>
</div>

<div class="card">
<h2>SL.Abuhasan</h2>
<h3>Grenadier</h3>
<p>Explosive specialist who dominates the battlefield using grenades.</p>
</div>

<div class="card">
<h2>SL.Faisal</h2>
<h3>Sniper</h3>
<p>Long-range support using Skyler, Moco, Rafael and Suzy.</p>
</div>

</div>

</section>

<section class="notice">

<h2>WE WILL PLAY THE FFWS NEXT TIME</h2>

<p><b>Never this time.</b></p>

</section>

<footer>

© 2026 SLAYERS eSports | Rush. Dominate. Conquer.

</footer>

</body>
</html>
