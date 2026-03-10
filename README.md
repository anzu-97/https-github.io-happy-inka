<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Happy Birthday Inka</title>

<style>
body{
margin:0;
font-family:Arial;
background:linear-gradient(135deg,#ff758c,#ff7eb3);
color:white;
text-align:center;
overflow:hidden;
}

.container{
margin-top:120px;
}

h1{
font-size:45px;
}

p{
font-size:22px;
max-width:600px;
margin:auto;
line-height:1.6;
}

.balloon{
position:absolute;
bottom:-150px;
width:40px;
height:55px;
background:red;
border-radius:50%;
animation:float 10s infinite;
}

@keyframes float{
0%{transform:translateY(0);}
100%{transform:translateY(-1200px);}
}
</style>

</head>

<body>

<div class="container">

<h1>🎉 Happy Birthday 🎂</h1>

<h2>Nurhajijah (Inka)</h2>

<p>
Semoga dengan bertambahnya umur,<br>
Inka bisa menjadi pribadi yang lebih baik lagi.<br><br>

Panjang umur, sehat selalu,<br>
dan semoga semua hal baik datang dalam hidupmu.

Note. Maaf belom bisa ngasih apa² dan maaf atas sikap dan perilaku ku semua.
</p>

</div>

<script>
for(let i=0;i<25;i++){
let b=document.createElement("div");
b.className="balloon";
b.style.left=Math.random()*100+"%";
b.style.background="hsl("+Math.random()*360+",70%,60%)";
b.style.animationDuration=(6+Math.random()*5)+"s";
document.body.appendChild(b);
}
</script>

<iframe width="0" height="0"
src="https://www.youtube.com/embed/90w2RegGf9w?autoplay=1&loop=1&playlist=90w2RegGf9w"
frameborder="0" allow="autoplay">
</iframe>

</body>
</html>
