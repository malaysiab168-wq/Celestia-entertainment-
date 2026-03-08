<!DOCTYPE html>
<html>
<head>
<title>Celestia Entertainment</title>

<style>
body{
font-family: Arial;
margin:0;
background:linear-gradient(#0f0c29,#302b63,#24243e);
color:white;
text-align:center;
}

header{
font-size:40px;
padding:30px;
font-weight:bold;
}

nav{
background:rgba(255,255,255,0.1);
padding:15px;
}

nav a{
color:white;
margin:10px;
font-size:18px;
cursor:pointer;
text-decoration:none;
}

nav a:hover{
color:#ffd700;
}

section{
display:none;
padding:40px;
}

.active{
display:block;
}

img{
width:200px;
border-radius:15px;
margin:10px;
}
</style>

<script>
function showPage(page){
document.querySelectorAll("section").forEach(s=>s.classList.remove("active"));
document.getElementById(page).classList.add("active");
}
</script>

</head>

<body>

<header>⭐ Celestia Entertainment ⭐</header>

<nav>
<a onclick="showPage('home')">Home</a>
<a onclick="showPage('starlight')">Starlight</a>
<a onclick="showPage('lumin')">LUM1N</a>
<a onclick="showPage('fandom')">Fandom</a>
<a href="https://discord.gg/NbuGfYrhYl">Auditions</a>
<a href="https://www.tiktok.com/@celestia.entertai24">TikTok</a>
</nav>

<section id="home" class="active">
<h2>Welcome</h2>
<p>Celestia Entertainment is a K-pop inspired entertainment company.</p>
<p>Home to rising groups and talented trainees.</p>
</section>

<section id="starlight">
<h2>Starlight</h2>

<h3>Remi</h3>
<img src="https://i.postimg.cc/fWps1Ydq/IMG-0494.jpg">
<p>Status: Trainee</p>

</section>

<section id="lumin">
<h2>LUM1N</h2>

<h3>Yungchic</h3>
<img src="https://i.postimg.cc/PfZY8Qdw/IMG-0485.jpg">
<p>Status: Trainee</p>

</section>

<section id="fandom">
<h2>Fandoms</h2>

<p>⭐ Starlight fans are called <b>Orbits</b></p>
<p>⭐ LUM1N fans are called <b>Aluminum</b></p>

</section>

</body>
</html>
