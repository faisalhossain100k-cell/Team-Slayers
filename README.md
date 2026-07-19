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
/* ==========================
   SLAYERS ESPORTS
   AI Gaming Theme
========================== */

*{
margin:0;
padding:0;
box-sizing:border-box;
scroll-behavior:smooth;
font-family:'Orbitron',sans-serif;
}

body{
background:#dfe7ef;
overflow-x:hidden;
color:white;
}

/* Background Video */

#bgVideo{
position:fixed;
top:0;
left:0;
width:100%;
height:100%;
object-fit:cover;
z-index:-2;
filter:brightness(.35);
}

/* Overlay */

body::before{
content:'';
position:fixed;
width:100%;
height:100%;
background:rgba(180,210,240,.35);
backdrop-filter:blur(4px);
z-index:-1;
}

/* Loader */

#loader{
position:fixed;
width:100%;
height:100vh;
background:#dce5ee;
display:flex;
justify-content:center;
align-items:center;
z-index:99999;
animation:fadeOut 3s forwards;
animation-delay:2s;
}

.loader-logo{
text-align:center;
}

.loader-logo img{
width:150px;
animation:spin 5s linear infinite;
}

.loader-logo h1{
font-size:60px;
margin-top:20px;
color:#008cff;
text-shadow:0 0 20px #00bfff;
}

.loader-logo p{
color:#333;
font-size:18px;
}

/* Navigation */

header{
position:fixed;
top:0;
left:0;
width:100%;
padding:18px 7%;
display:flex;
justify-content:space-between;
align-items:center;
background:rgba(230,240,250,.15);
backdrop-filter:blur(12px);
border-bottom:1px solid rgba(255,255,255,.25);
z-index:999;
}

.logo{
display:flex;
align-items:center;
gap:15px;
}

.logo img{
width:60px;
}

.logo h1{
font-size:30px;
color:#00bfff;
text-shadow:0 0 15px #00bfff;
}

nav a{
color:white;
text-decoration:none;
margin-left:25px;
font-size:15px;
transition:.4s;
}

nav a:hover{
color:#00bfff;
text-shadow:0 0 20px cyan;
}

.join-btn{
padding:12px 28px;
background:#00aaff;
border-radius:40px;
cursor:pointer;
transition:.4s;
font-weight:bold;
box-shadow:0 0 20px #00bfff;
}

.join-btn:hover{
background:#4dc3ff;
transform:translateY(-5px);
}

/* Hero */

.hero{
height:100vh;
display:flex;
justify-content:space-between;
align-items:center;
padding:0 8%;
}

.hero-left{
width:55%;
}

.hero-left h3{
font-size:22px;
color:#8fd9ff;
letter-spacing:4px;
}

.hero-left h1{
font-size:75px;
line-height:90px;
margin-top:20px;
text-shadow:0 0 20px #00bfff;
}

.hero-left p{
font-size:20px;
margin-top:30px;
color:#ddefff;
}

.buttons{
margin-top:45px;
display:flex;
gap:20px;
}

.buttons button{
padding:15px 35px;
border:none;
border-radius:35px;
font-size:16px;
cursor:pointer;
font-weight:bold;
background:#00aaff;
color:white;
box-shadow:0 0 25px #00bfff;
transition:.4s;
}

.buttons button:hover{
transform:translateY(-8px);
background:#008cff;
}

.hero-right{
width:40%;
display:flex;
justify-content:center;
}

.hero-right img{
width:360px;
filter:drop-shadow(0 0 35px #00bfff);
animation:float 4s ease-in-out infinite;
}

/* Section */

section{
padding:120px 8%;
}

section h1{
font-size:50px;
margin-bottom:35px;
text-align:center;
color:#00bfff;
text-shadow:0 0 20px #00bfff;
}

section p{
font-size:18px;
line-height:34px;
text-align:center;
}

/* Responsive */

@media(max-width:991px){

header{
flex-direction:column;
padding:15px;
}

nav{
margin-top:20px;
}

.hero{
flex-direction:column;
justify-content:center;
text-align:center;
padding-top:120px;
}

.hero-left{
width:100%;
}

.hero-left h1{
font-size:55px;
line-height:65px;
}

.hero-right{
margin-top:40px;
width:100%;
}

.hero-right img{
width:260px;
}

.buttons{
justify-content:center;
}

}

/* Animations */

@keyframes float{

0%{
transform:translateY(0px);
}

50%{
transform:translateY(-20px);
}

100%{
transform:translateY(0px);
}

}

@keyframes spin{

100%{
transform:rotate(360deg);
}

}

@keyframes fadeOut{

100%{
opacity:0;
visibility:hidden;
}

}
/* ===============================
   PLAYER CARDS
================================ */

.player-grid{

display:grid;

grid-template-columns:repeat(auto-fit,minmax(270px,1fr));

gap:35px;

margin-top:60px;

}

.card{

background:rgba(230,240,250,.12);

backdrop-filter:blur(20px);

border:1px solid rgba(255,255,255,.25);

border-radius:25px;

padding:30px;

text-align:center;

transition:.45s;

overflow:hidden;

position:relative;

}

.card::before{

content:'';

position:absolute;

top:-100%;

left:-100%;

width:300%;

height:300%;

background:linear-gradient(45deg,

transparent,

rgba(0,191,255,.18),

transparent);

transform:rotate(45deg);

transition:.6s;

}

.card:hover::before{

top:-20%;

left:-20%;

}

.card:hover{

transform:translateY(-15px);

box-shadow:0 0 35px #00bfff;

}

.card img{

width:170px;

height:170px;

object-fit:cover;

border-radius:50%;

border:4px solid #00bfff;

box-shadow:0 0 30px #00bfff;

margin-bottom:20px;

}

.card h2{

font-size:28px;

color:#00bfff;

margin-bottom:10px;

}

.card h3{

font-size:18px;

color:white;

margin-bottom:15px;

}

.card p{

font-size:15px;

line-height:28px;

color:#d8ecff;

}

/* ===============================
COUNTDOWN
================================ */

.countdown{

text-align:center;

}

#timer{

display:flex;

justify-content:center;

flex-wrap:wrap;

gap:25px;

margin-top:50px;

}

.time-box{

width:130px;

height:130px;

background:rgba(255,255,255,.1);

backdrop-filter:blur(20px);

border-radius:20px;

display:flex;

flex-direction:column;

justify-content:center;

align-items:center;

box-shadow:0 0 20px #00bfff;

}

.time-box h1{

font-size:42px;

color:#00bfff;

}

.time-box span{

font-size:16px;

}

/* ===============================
TOURNAMENT
================================ */

.tournament-grid{

display:grid;

grid-template-columns:repeat(auto-fit,minmax(320px,1fr));

gap:35px;

margin-top:60px;

}

.tournament-card{

background:rgba(255,255,255,.08);

border-radius:25px;

padding:35px;

backdrop-filter:blur(18px);

transition:.4s;

}

.tournament-card:hover{

transform:scale(1.05);

box-shadow:0 0 35px #00bfff;

}

.tournament-card h2{

color:#00bfff;

margin-bottom:20px;

}

/* ===============================
GALLERY
================================ */

.gallery-grid{

display:grid;

grid-template-columns:repeat(auto-fit,minmax(250px,1fr));

gap:20px;

margin-top:50px;

}

.gallery-grid img{

width:100%;

height:240px;

object-fit:cover;

border-radius:20px;

transition:.4s;

cursor:pointer;

box-shadow:0 0 20px rgba(0,191,255,.3);

}

.gallery-grid img:hover{

transform:scale(1.08);

box-shadow:0 0 35px #00bfff;

}

/* ===============================
MATCH SCHEDULE
================================ */

.match{

background:rgba(255,255,255,.08);

padding:30px;

border-radius:20px;

margin-top:25px;

display:flex;

justify-content:space-between;

align-items:center;

backdrop-filter:blur(18px);

transition:.4s;

}

.match:hover{

box-shadow:0 0 25px #00bfff;

transform:translateX(8px);

}

.match h2{

color:#00bfff;

}

/* ===============================
FOOTER
================================ */

footer{

margin-top:100px;

padding:60px;

text-align:center;

background:rgba(255,255,255,.08);

backdrop-filter:blur(20px);

border-top:1px solid rgba(255,255,255,.2);

}

footer h2{

color:#00bfff;

margin-bottom:15px;

}

footer p{

color:white;

line-height:30px;

}

/* Scrollbar */

::-webkit-scrollbar{

width:10px;

}

::-webkit-scrollbar-thumb{

background:#00bfff;

border-radius:20px;

}

::-webkit-scrollbar-track{

background:#dce5ef;

}
/* ===========================
   SLAYERS AI ANIMATIONS
===========================*/

/* Fade In */

.fade{
opacity:0;
transform:translateY(60px);
animation:fadeUp 1.2s forwards;
}

@keyframes fadeUp{

100%{

opacity:1;

transform:translateY(0);

}

}

/* Floating */

.float{

animation:floating 4s ease-in-out infinite;

}

@keyframes floating{

0%{

transform:translateY(0);

}

50%{

transform:translateY(-18px);

}

100%{

transform:translateY(0);

}

}

/* Neon Pulse */

.glow{

animation:glow 2s infinite alternate;

}

@keyframes glow{

0%{

box-shadow:

0 0 10px #00bfff,

0 0 20px #00bfff,

0 0 40px #00bfff;

}

100%{

box-shadow:

0 0 20px cyan,

0 0 50px cyan,

0 0 90px cyan;

}

}

/* Hero Title */

.hero h1{

animation:titleGlow 3s infinite alternate;

}

@keyframes titleGlow{

0%{

text-shadow:

0 0 10px #00bfff,

0 0 20px #00bfff;

}

100%{

text-shadow:

0 0 20px cyan,

0 0 40px cyan,

0 0 70px cyan;

}

}

/* Buttons */

button{

transition:.4s;

}

button:hover{

transform:translateY(-8px) scale(1.05);

box-shadow:

0 0 20px cyan,

0 0 40px cyan;

}

/* Player Cards */

.card{

transition:.5s;

}

.card:hover{

transform:

translateY(-12px)

rotateX(6deg)

rotateY(6deg);

}

/* Images */

.gallery-grid img{

transition:.6s;

}

.gallery-grid img:hover{

transform:

scale(1.1)

rotate(1deg);

}

/* Navigation */

nav a{

position:relative;

}

nav a::after{

content:'';

position:absolute;

left:0;

bottom:-6px;

width:0;

height:3px;

background:cyan;

transition:.4s;

}

nav a:hover::after{

width:100%;

}

/* Loader */

.loader-logo img{

animation:

rotateLogo 8s linear infinite;

}

@keyframes rotateLogo{

100%{

transform:rotate(360deg);

}

}

/* Logo */

.logo img{

transition:.5s;

}

.logo img:hover{

transform:rotate(360deg);

}

/* Scroll */

html{

scroll-behavior:smooth;

}

/* Page Animation */

section{

animation:pageLoad 1s;

}

@keyframes pageLoad{

from{

opacity:0;

transform:translateY(80px);

}

to{

opacity:1;

transform:translateY(0);

}

}

/* Neon Border */

.neon{

border:2px solid cyan;

box-shadow:

0 0 20px cyan,

inset 0 0 20px cyan;

}

/* Background Animation */

body::after{

content:'';

position:fixed;

top:0;

left:0;

width:100%;

height:100%;

background:

radial-gradient(circle,

rgba(0,191,255,.05),

transparent);

pointer-events:none;

animation:bgPulse 6s infinite;

}

@keyframes bgPulse{

50%{

opacity:.3;

transform:scale(1.08);

}

}

/* Mobile */

@media(max-width:768px){

.hero h1{

font-size:45px;

}

.logo h1{

font-size:22px;

}

nav{

display:flex;

flex-wrap:wrap;

justify-content:center;

}

button{

width:100%;

margin-top:15px;

}

.card{

margin-top:20px;

}

}
// =========================
// SLAYERS ESPORTS
// AI UI SCRIPT
// =========================

// Loader

window.addEventListener("load",()=>{

const loader=document.getElementById("loader");

setTimeout(()=>{

loader.style.opacity="0";

loader.style.visibility="hidden";

},2500);

});

// =========================
// Navbar Blur
// =========================

const header=document.querySelector("header");

window.addEventListener("scroll",()=>{

if(window.scrollY>80){

header.style.background="rgba(10,20,40,.75)";

header.style.boxShadow="0 0 25px cyan";

}else{

header.style.background="rgba(255,255,255,.10)";

header.style.boxShadow="none";

}

});

// =========================
// Reveal Animation
// =========================

const reveal=document.querySelectorAll("section");

function showSection(){

let windowHeight=window.innerHeight;

reveal.forEach(sec=>{

let top=sec.getBoundingClientRect().top;

if(top<windowHeight-120){

sec.classList.add("fade");

}

});

}

window.addEventListener("scroll",showSection);

// =========================
// Mouse Glow
// =========================

const glow=document.createElement("div");

glow.style.position="fixed";

glow.style.width="25px";

glow.style.height="25px";

glow.style.borderRadius="50%";

glow.style.background="cyan";

glow.style.pointerEvents="none";

glow.style.filter="blur(12px)";

glow.style.zIndex="999999";

document.body.appendChild(glow);

document.addEventListener("mousemove",(e)=>{

glow.style.left=e.clientX-12+"px";

glow.style.top=e.clientY-12+"px";

});

// =========================
// Floating Particles
// =========================

for(let i=0;i<40;i++){

let star=document.createElement("span");

star.className="particle";

star.style.left=Math.random()*100+"vw";

star.style.animationDuration=(3+Math.random()*8)+"s";

star.style.animationDelay=Math.random()*5+"s";

document.body.appendChild(star);

}

// =========================
// Hero Buttons
// =========================

const buttons=document.querySelectorAll("button");

buttons.forEach(btn=>{

btn.addEventListener("mouseenter",()=>{

btn.style.boxShadow="0 0 40px cyan";

});

btn.addEventListener("mouseleave",()=>{

btn.style.boxShadow="";

});

});

// =========================
// Player Cards
// =========================

const cards=document.querySelectorAll(".card");

cards.forEach(card=>{

card.addEventListener("mousemove",(e)=>{

let x=e.offsetX;

let y=e.offsetY;

card.style.transform=

`rotateX(${-(y-120)/20}deg)

 rotateY(${(x-120)/20}deg)

 translateY(-12px)`;

});

card.addEventListener("mouseleave",()=>{

card.style.transform="rotateX(0) rotateY(0)";

});

});

// =========================
// Smooth Navigation
// =========================

document.querySelectorAll("nav a").forEach(link=>{

link.onclick=function(e){

e.preventDefault();

document.querySelector(this.getAttribute("href"))

.scrollIntoView({

behavior:"smooth"

});

};

});

// =========================
// AI Console Welcome
// =========================

console.log("SLAYERS ESPORTS AI SYSTEM LOADED");

console.log("Rush. Dominate. Conquer.");

// ===========================
// SLAYERS FFWS COUNTDOWN
// ===========================

// Set your target date here
const targetDate = new Date("January 1, 2027 00:00:00").getTime();

const timer = document.getElementById("timer");

function updateCountdown(){

const now = new Date().getTime();

const distance = targetDate - now;

if(distance <= 0){

timer.innerHTML = `

<div class="time-box">

<h2>🔥</h2>

<span>TOURNAMENT STARTED</span>

</div>

`;

return;

}

const days = Math.floor(distance/(1000*60*60*24));

const hours = Math.floor((distance%(1000*60*60*24))/(1000*60*60));

const minutes = Math.floor((distance%(1000*60*60))/(1000*60));

const seconds = Math.floor((distance%(1000*60))/1000);

timer.innerHTML = `

<div class="time-box">

<h1>${days}</h1>

<span>DAYS</span>

</div>

<div class="time-box">

<h1>${hours}</h1>

<span>HOURS</span>

</div>

<div class="time-box">

<h1>${minutes}</h1>

<span>MINUTES</span>

</div>

<div class="time-box">

<h1>${seconds}</h1>

<span>SECONDS</span>

</div>

`;

}

updateCountdown();

setInterval(updateCountdown,1000);

// ===========================
// FFWS Goal Message
// ===========================

const goalMessage = document.createElement("div");

goalMessage.innerHTML = `

<h2 style="
color:#00bfff;
text-align:center;
margin-top:40px;
text-shadow:0 0 20px cyan;
">

🏆 OUR DREAM

</h2>

<p style="
text-align:center;
font-size:18px;
margin-top:20px;
color:white;
">

We are training every day with dedication and discipline.

Our goal is to compete in the Free Fire World Series (FFWS) in the future.

Thank you to everyone who supports SLAYERS.

</p>

`;

const countdownSection = document.querySelector(".countdown");

if(countdownSection){

countdownSection.appendChild(goalMessage);

}

// ===========================
// AI Status Text
// ===========================

const status = document.createElement("p");

status.innerHTML = "⚡ AI System Status: ONLINE";

status.style.color = "#00ffff";
status.style.textAlign = "center";
status.style.marginTop = "20px";
status.style.fontWeight = "bold";
status.style.textShadow = "0 0 10px cyan";

if(countdownSection){

countdownSection.appendChild(status);

}
<!DOCTYPE html>
<html lang="en">
<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>SLAYERS | PLAYERS</title>

<link rel="stylesheet" href="css/style.css">
<link rel="stylesheet" href="css/animations.css">

<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700;900&display=swap" rel="stylesheet">

</head>

<body>

<header>

<div class="logo">

<img src="assets/logo.png">

<h1>SLAYERS</h1>

</div>

<nav>

<a href="index.html">HOME</a>

<a href="players.html">PLAYERS</a>

<a href="gallery.html">GALLERY</a>

<a href="tournaments.html">TOURNAMENT</a>

<a href="schedule.html">SCHEDULE</a>

</nav>

</header>

<section>

<h1>SLAYERS ROSTER</h1>

<div class="player-grid">

<!-- Tornado -->

<div class="card glow">

<img src="assets/tornado.png">

<h2>SL.Tornado</h2>

<h3>FIRST RUSHER</h3>

<p>
The fearless front-line attacker who opens every fight.
</p>

<hr>

<p>

🔥 Role : Entry Fragger

⚡ Aggression : 100%

🎯 Aim : 96%

🛡 Team Support : 88%

🏃 Speed : 99%

❤️ Specialty :

"The first one in. The last one standing."

</p>

</div>

<!-- Ismail -->

<div class="card glow">

<img src="assets/ismail.png">

<h2>SL.Ismail</h2>

<h3>SUPPORT RUSHER</h3>

<p>

Supports Tornado during every push and protects teammates.

</p>

<hr>

<p>

⚡ Teamwork : 100%

🎯 Aim : 94%

🛡 Defense : 96%

❤️ Revive Expert

🔥 Specialty :

"Every great rusher needs a reliable partner."

</p>

</div>

<!-- Abuhasan -->

<div class="card glow">

<img src="assets/abuhasan.png">

<h2>SL.Abuhasan</h2>

<h3>GRENADIER</h3>

<p>

Explosive specialist.

Master of grenade throws and area control.

</p>

<hr>

<p>

💣 Grenade Accuracy : 98%

🎯 Tactical IQ : 96%

⚡ Utility Usage : 100%

🔥 Specialty :

"If you're hiding, you're already in danger."

</p>

</div>

<!-- Faisal -->

<div class="card glow">

<img src="assets/faisal.png">

<h2>SL.Faisal</h2>

<h3>SNIPER</h3>

<p>

Long-range support.

Protects teammates from distance.

</p>

<hr>

<p>

🎯 Accuracy : 99%

👁 Vision : 100%

⚡ Calmness : 98%

🔫 Weapons :

AWM

M82B

Woodpecker

SKS

🌊 Skyler

👁 Moco

🎯 Rafael

💰 Suzy

</p>

</div>

</div>

</section>

<section>

<h1>TEAM GOAL</h1>

<p>

Our mission is to become one of the strongest Free Fire teams in Bangladesh and continue improving through dedication, teamwork, and discipline. We are preparing ourselves to compete at the highest level in future Free Fire tournaments.

</p>

</section>

<footer>

<h2>SLAYERS ESPORTS</h2>

<p>

Rush. Dominate. Conquer.

</p>

</footer>

<script src="js/script.js"></script>

</body>

</html>
<!DOCTYPE html>
<html lang="en">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>SLAYERS | Gallery</title>

<link rel="stylesheet" href="css/style.css">

<link rel="stylesheet" href="css/animations.css">

<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700;900&display=swap" rel="stylesheet">

</head>

<body>

<header>

<div class="logo">

<img src="assets/logo.png">

<h1>SLAYERS</h1>

</div>

<nav>

<a href="index.html">HOME</a>

<a href="players.html">PLAYERS</a>

<a href="gallery.html">GALLERY</a>

<a href="tournaments.html">TOURNAMENT</a>

<a href="schedule.html">SCHEDULE</a>

</nav>

</header>

<section>

<h1>MEDIA GALLERY</h1>

<p>

Every battle tells a story.

Every victory creates history.

</p>

<div class="gallery-grid">

<img src="assets/gallery/1.jpg">

<img src="assets/gallery/2.jpg">

<img src="assets/gallery/3.jpg">

<img src="assets/gallery/4.jpg">

<img src="assets/gallery/5.jpg">

<img src="assets/gallery/6.jpg">

<img src="assets/gallery/7.jpg">

<img src="assets/gallery/8.jpg">

</div>

</section>

<section>

<h1>TEAM HIGHLIGHTS</h1>

<div class="player-grid">

<div class="card">

<h2>BEST RUSH</h2>

<p>

SL.Tornado leading the push while

SL.Ismail covers the attack.

</p>

</div>

<div class="card">

<h2>BEST GRENADE</h2>

<p>

SL.Abuhasan controls the battlefield

with accurate grenade throws.

</p>

</div>

<div class="card">

<h2>BEST SNIPE</h2>

<p>

SL.Faisal provides long-range

cover with precision shots.

</p>

</div>

</div>

</section>

<section>

<h1>VIDEOS</h1>

<div class="player-grid">

<div class="card">

<video controls width="100%">

<source src="assets/videos/video1.mp4"

type="video/mp4">

</video>

<h3>Scrim Highlights</h3>

</div>

<div class="card">

<video controls width="100%">

<source src="assets/videos/video2.mp4"

type="video/mp4">

</video>

<h3>Training Session</h3>

</div>

</div>

</section>

<section>

<h1>OUR MOTTO</h1>

<h2 style="text-align:center;color:#00bfff;">

⚔️

Rush.

Dominate.

Conquer.

⚔️

</h2>

</section>

<footer>

<h2>

SLAYERS ESPORTS

</h2>

<p>

Professional Free Fire Team

</p>

<p>

©2026 SLAYERS ESPORTS

</p>

</footer>

<script src="js/script.js"></script>

</body>

</html><!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SLAYERS | Tournament</title>

<link rel="stylesheet" href="css/style.css">
<link rel="stylesheet" href="css/animations.css">

<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700;900&display=swap" rel="stylesheet">

</head>

<body>

<header>

<div class="logo">
<img src="assets/logo.png">
<h1>SLAYERS</h1>
</div>

<nav>
<a href="index.html">HOME</a>
<a href="players.html">PLAYERS</a>
<a href="gallery.html">GALLERY</a>
<a href="tournaments.html">TOURNAMENT</a>
<a href="schedule.html">SCHEDULE</a>
</nav>

</header>

<section>

<h1>OUR JOURNEY</h1>

<p>

SLAYERS is dedicated to improving every day through practice,
discipline, and teamwork. Our goal is to compete in higher-level
Free Fire tournaments and continue growing as a team.

</p>

</section>

<section>

<h1>FUTURE GOALS</h1>

<div class="player-grid">

<div class="card">

<h2>🔥 Daily Training</h2>

<p>

Scrims every week

Improve teamwork

Practice strategy

Review gameplay

</p>

</div>

<div class="card">

<h2>🏆 Tournament Goal</h2>

<p>

Participate in more competitive events and continue working toward future FFWS qualification.

</p>

</div>

<div class="card">

<h2>🌎 Our Dream</h2>

<p>

Represent Bangladesh with pride through dedication, sportsmanship, and strong team performance.

</p>

</div>

</div>

</section>

<section>

<h1>UPCOMING SCHEDULE</h1>

<div class="match">

<div>

<h2>Community Scrim</h2>

<p>Date: Coming Soon</p>

</div>

<div>

<h2>Status</h2>

<p>Preparing</p>

</div>

</div>

<div class="match">

<div>

<h2>Training Session</h2>

<p>Every Week</p>

</div>

<div>

<h2>Status</h2>

<p>Active</p>

</div>

</div>

</section>

<section>

<h1>CONTACT</h1>

<p>Email: slayers.esports@gmail.com</p>

<p>Country: Bangladesh</p>

<p>Rush. Dominate. Conquer.</p>

</section>

<footer>

<h2>SLAYERS ESPORTS</h2>

<p>Professional Free Fire Team</p>

<p>© 2026 SLAYERS ESPORTS</p>

</footer>

<script src="js/script.js"></script>

</body>
</html>
