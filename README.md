<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<title>Happy Birthday Inka</title>

<style>

body{
margin:0;
font-family:Arial, sans-serif;
background:linear-gradient(135deg,#ff6a88,#ff99ac);
text-align:center;
color:white;
overflow:hidden;
}

.container{
margin-top:120px;
padding:20px;
}

h1{
font-size:55px;
margin-bottom:10px;
}

h2{
margin-top:-5px;
font-size:28px;
}

.message{
max-width:600px;
margin:auto;
font-size:18px;
line-height:1.6;
}

button{
margin-top:30px;
padding:14px 28px;
border:none;
border-radius:12px;
background:white;
color:#ff4f81;
font-size:16px;
cursor:pointer;
}

button:hover{
transform:scale(1.05);
}

.cake{
font-size:80px;
margin:20px;
animation:float 3s ease-in-out infinite;
}

@keyframes float{
0%{transform:translateY(0)}
50%{transform:translateY(-15px)}
100%{transform:translateY(0)}
}

.heart{
position:absolute;
color:white;
font-size:20px;
animation:fall linear infinite;
}

@keyframes fall{
to{
transform:translateY(110vh);
}
}

</style>
</head>

<body>

<div class="container">

<h1>🎉 Happy Birthday 🎉</h1>

<h2>Nurhajijah (Inka)</h2>

<div class="cake">🎂</div>

<p class="message">
Semoga dengan bertambahnya umur, kamu bisa menjadi pribadi yang
lebih baik lagi. Semoga panjang umur, sehat selalu,
dan semua harapan baikmu bisa tercapai.
</p>

<p class="message">
Semoga hari ini penuh kebahagiaan,
tawa, dan momen indah bersama orang-orang yang kamu sayangi.
</p>

<button onclick="playMusic()">Putar Musik 🎵</button>

<audio id="music">
<source src="https://www.bensound.com/bensound-music/bensound-happyrock.mp3" type="audio/mpeg">
</audio>

</div>

<script>

function playMusic(){
document.getElementById("music").play();
}

function createHearts(){
for(let i=0;i<40;i++){
let heart=document.createElement("div");
heart.className="heart";
heart.innerHTML="❤";
heart.style.left=Math.random()*100+"vw";
heart.style.animationDuration=(4+Math.random()*4)+"s";
heart.style.top="-10px";
document.body.appendChild(heart);
}
}

createHearts();

</script>

</body>
</html>
