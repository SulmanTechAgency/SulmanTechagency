## Hi there 👋

<!--
**SulmanTechAgency/SulmanTechagency** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Digital Agency</title>
<style>
body {margin:0; font-family: Arial; background:#0d1b2a; color:white; overflow-x:hidden;}
header {padding:20px; text-align:center; background:rgba(0,0,0,0.6);}
nav {text-align:center; margin:20px;}
nav a {margin:0 10px; color:#4cc9f0; text-decoration:none; font-weight:bold;}
nav a:hover {color:#fff;}
.hero {position:relative; text-align:center; padding:100px 20px; overflow:hidden;}
.hero::before {
content:""; position:absolute; top:-50%; left:-50%; width:200%; height:200%;
background: linear-gradient(-45deg,#0d1b2a,#1b263b,#3a0ca3,#4361ee);
background-size:400% 400%;
animation: gradientMove 12s ease infinite; z-index:0;
}
@keyframes gradientMove {
0%{background-position:0% 50%;}
50%{background-position:100% 50%;}
100%{background-position:0% 50%;}
}
.hero-content {position:relative; z-index:2;}
.hero-content h1{font-size:48px; margin-bottom:20px; color:#4cc9f0;}
.hero-content p{font-size:20px; opacity:0.9; margin-bottom:30px;}
.button {padding:14px 30px; margin:10px; background:#4cc9f0; color:#0d1b2a; font-weight:bold; border-radius:8px; text-decoration:none;}
.button:hover{background:#fff; color:#000; transform:scale(1.05); transition:0.3s;}

.services {display:flex; flex-wrap:wrap; justify-content:center; margin:50px 0;}
.card {background:rgba(27,38,59,0.8); padding:20px; margin:10px; border-radius:10px; width:250px; text-align:center;}
.card h3{color:#4cc9f0;}
.card p{opacity:0.9;}
.card a{display:inline-block; margin-top:15px; padding:10px 20px; background:#4cc9f0; color:#0d1b2a; text-decoration:none; border-radius:6px;}
.card a:hover{background:#fff; color:#000; transform:scale(1.05); transition:0.3s;}

footer {text-align:center; padding:20px; background:rgba(0,0,0,0.6);}
</style>
</head>
<body>

<header>
<h2>My Digital Agency</h2>
<nav>
<a href="#home">Home</a>
<a href="#services">Services</a>
<a href="#contact">Contact</a>
</nav>
</header>

<section class="hero" id="home">
<div class="hero-content">
<h1>We Build Websites & Apps</h1>
<p>Custom Development | UI/UX Design | E-commerce | AI Automation</p>
<a href="#services" class="button">Explore Services</a>
</div>
</section>

<section class="services" id="services">
<div class="card">
<h3>Website Design & Development</h3>
<p>Professional websites starting at $899+</p>
<a href="https://wa.me/923342487879?text=I%20want%20Website%20Design">Buy Now</a>
</div>
<div class="card">
<h3>App Design & Development</h3>
<p>iOS & Android apps starting at $899+</p>
<a href="https://wa.me/923342487879?text=I%20want%20App%20Design">Buy Now</a>
</div>
<div class="card">
<h3>E-commerce Website / App</h3>
<p>Online stores & marketplaces starting at $899+</p>
<a href="https://wa.me/923342487879?text=I%20want%20E-commerce">Buy Now</a>
</div>
<div class="card">
<h3>Custom Setup / Solutions</h3>
<p>Custom projects starting at $899+</p>
<a href="https://wa.me/923342487879?text=I%20want%20Custom%20Solution">Buy Now</a>
</div>
</section>

<footer>
<p>Contact us: brandBuzzzAgency@gmail.com | WhatsApp: +923342487879</p>
<p>&copy; 2026 My Digital Agency</p>
</footer>

</body>
</html>
