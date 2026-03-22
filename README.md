# site1_html
WebProject
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Electronics Website</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial;
}

body{
background:#f5f5f5;
}

/* NAVBAR */

.navbar{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 10%;
background:rgb(218, 206, 206);
}

.navbar ul{
display:flex;
list-style:none;
gap:25px;
}

.navbar li{
cursor:pointer;
font-weight:500;
}

/* BUTTON */

.btn{
background:#2fb4aa;
color:white;
border:none;
padding:10px 20px;
cursor:pointer;
border-radius:4px;
transition:0.3s;
}

.btn:hover{
background:#1c8f86;
transform:scale(1.05);
}


/* HERO */

.hero{
display:flex;
align-items:center;
padding:60px 10%;
gap:40px;
background:white;
}

.hero img{
width:450px;
border-radius:8px;
}

.hero-text h1{
font-size:40px;
margin-bottom:20px;
}

.hero-text p{
margin-bottom:20px;
color:gray;
}


/* TRENDING */

.trending{
background:black;
color:white;
text-align:center;
padding:60px;
}

.trending p{
margin-top:10px;
margin-bottom:20px;
}


/* TOOLS */

.tools{
display:flex;
padding:60px 10%;
gap:60px;
align-items:center;
background:#eef8f7;   /* light background added */
}

.tools-text{
max-width:350px;
}

.tools-text h2{
margin-bottom:15px;
}

.tools-grid{
display:grid;
grid-template-columns:repeat(2,180px);
gap:15px;
}

.card{
background:#47c1b6;
padding:20px;
color:white;
font-weight:bold;
text-align:center;
border-radius:6px;
transition:0.3s;
}

.card:hover{
transform:translateY(-5px);
}

.card button{
margin-top:10px;
background:white;
color:#2fb4aa;
border:none;
padding:6px 12px;
border-radius:3px;
cursor:pointer;
}


/* PROJECT */

.project{
display:flex;
margin:60px 10%;
}

.project-left{
background:#2fb4aa;
padding:60px;
color:white;
flex:1;
}

.project-left h1{
margin-bottom:20px;
}

.project-right{
flex:1;
}

.project-right img{
width:100%;
height:100%;
object-fit:cover;
}


/* SERVICES */

.services{
padding:60px 10%;
text-align:center;
}

.service-grid{
margin-top:40px;
display:grid;
grid-template-columns:repeat(3,1fr);
gap:20px;
}

.service{
background:white;
padding:30px;
box-shadow:0 0 10px rgba(0,0,0,0.1);
border-radius:5px;
transition:0.3s;
}

.service:hover{
transform:translateY(-5px);
}


/* EXTRA SECTION LIKE DESIGN */

.cta{
background:#47c1b6;
color:white;
text-align:center;
padding:40px;
margin-top:40px;
}

.cta button{
margin-top:15px;
background:white;
color:#47c1b6;
border:none;
padding:10px 20px;
border-radius:4px;
cursor:pointer;
}


/* FOOTER */

footer{
background:black;
color:white;
text-align:center;
padding:20px;
margin-top:40px;
}

</style>

</head>

<body>

<!-- NAVBAR -->

<nav class="navbar">
<h2>ClaimM4</h2>

<ul>
<li>Home</li>
<li>Tutorials</li>
<li>Reviews</li>
<li>News</li>
<li>Arduino</li>
<li>DIY</li>
</ul>

<button class="btn">Ask a Question</button>
</nav>



<!-- HERO SECTION -->

<section class="hero">

<div>
<img src="https://images.unsplash.com/photo-1519389950473-47ba0277781c">
</div>

<div class="hero-text">
<h1>Electronic FAQ</h1>

<p>

Learn electronics, DIY projects, tools reviews and tech tutorials
for engineering students.
</p>

<br/>

<br/>

<button class="btn">Learn More</button>

</div>

</section>



<!-- TRENDING -->

<section class="trending">

<h2>TRENDING NOW</h2>

<p>See the most interesting DIY projects and tech trends.</p>

<button class="btn">View More</button>

</section>



<!-- TOOLS -->

<section class="tools">

<div class="tools-text">

<h2>The 6 Best tools and accessories reviews</h2>

<p>
Explore the best electronics tools used in engineering
projects and DIY electronics builds.
</p>

<button class="btn">Explore Tools</button>

</div>


<div class="tools-grid">

<div class="card">
Welding Gun
<br>
<button>View</button>
</div>

<div class="card">
Ozone Generator
<br>
<button>View</button>
</div>

<div class="card">
Socket Organizer
<br>
<button>View</button>
</div>

<div class="card">
Gaming Mouse
<br>
<button>View</button>
</div>

<div class="card">
Soldering Iron Kits
<br>
<button>View</button>
</div>

<div class="card">
Resistor Kits
<br>
<button>View</button>
</div>

</div>

</section>



<!-- PROJECT -->

<section class="project">

<div class="project-left">

<h1>150+ Electronics Projects for Engineering Students</h1>

<button class="btn">Learn More</button>

</div>


<div class="project-right">

<img src="https://images.unsplash.com/photo-1581092160562-40aa08e78837">

</div>

</section>



<!-- SERVICES -->

<section class="services">

<h2>Our Services</h2>

<div class="service-grid">

<div class="service">Branding</div>
<div class="service">Marketing</div>
<div class="service">Development</div>
<div class="service">Web Design</div>
<div class="service">Social Media</div>
<div class="service">Ecommerce</div>

</div>

</section>



<!-- EXTRA SECTION -->

<section class="cta">

<h2>Business and Marketing Solutions</h2>

<p>Discover innovative strategies to grow your electronics projects and tech ideas.</p>

<button>View More</button>

</section>



<!-- FOOTER -->

<footer>

<p>© 2026 Electronics Website</p>

</footer>


</body>
</html>
