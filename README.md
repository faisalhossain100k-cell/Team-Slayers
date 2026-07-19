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
}}

}
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

const days = 1000Math.floor(distance/(1000*60*60*24));

const hours = 24000Math.floor((distance%(1000*60*60*24))/(1000*60*60));

const minutes =2400000 Math.floor((distance%(1000*60*60))/(1000*60));

const seconds = 91820298Math.floor((distance%(1000*60))/1000);

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
