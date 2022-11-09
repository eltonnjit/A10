# <!DOCTYPE html>
<html lang="en">

<head>
<meta charset="utf-8">
<title>San Joaquin Valley Town Hall</title>
<link rel="shortcut icon" href="images/favicon.ico">
<link rel="stylesheet" href="styles/main.css">
</head>

<body>
<header>
<img src="images/town_hall_logo.gif" alt="Town Hall logo" height="80">
<h2>San Joaquin Valley Town Hall</h2>
<h3>Celebrating our <span class="shadow">75<sup>th</sup></span> Year</h3>
</header>
<nav>
<ul>
<li><a class="current" href="index.html">Home</a></li>
<li><a href="#">Speakers</a></li>
<li><a href="#">Luncheons</a></li>
<li><a href="#">Tickets</a></li>
<li><a class="lastitem" href="#">About Us</a></li>
</ul>
</nav>
<main>
<section>
<h2>Our Mission</h2>
<p>San Joaquin Valley Town Hall is a non-profit organization that is run by an
all-volunteer board of directors. Our mission is to bring nationally and
internationally renowned, thought-provoking speakers who inform, educate,
and entertain our audience! As one or our members told us:</p>
<blockquote>&ldquo;Each year I give a ticket package to each of our family members.
I think of it as the gift of knowledge...and that is priceless.&rdquo;</blockquote>

<h1>Speaker of the Month</h1>
<article>
<h2>Fossil Threads in the Web of Life</h2>
<img src="images/sampson_dinosaur.jpg" alt="Scott Sampson with dinosaur">
<h3>February<br>
Scott Sampson</h3>
<p>What's 75 million years old and brand spanking new? A teenage Utahceratops!
Come to the Saroyan, armed with your best dinosaur roar, when Scott Sampson, Research
Curator at the Utah Museum of Natural History, steps to the podium. Sampson's research
has focused on the ecology and evolution of late Cretaceous dinosaurs and he has conducted
fieldwork in a number of countries in Africa.</p>
<p><a href="#">Read more.</a>&nbsp;<b>Or meet us there!</b></p>
</article>

<h2>Our Ticket Packages</h2>
<ul>
<li>Season Package: $95</li>
<li>Patron Package: $200</li>
<li>Single Speaker: $25</li>
</ul>
</section>
<aside>
<h2>Guest speakers</h2>
<h3>October<br><a href="#">Jeffrey Toobin</a></h3>
<img src="images/toobin75.jpg" alt="Jeffrey Toobin photo">
<h3>November<br><a href="#">Andrew Ross Sorkin</a></h3>
<img src="images/sorkin75.jpg" alt="Andrew Ross Sorkin photo">
<h3>January<br><a href="#">Amy Chua</a></h3>
<img src="images/chua75.jpg" alt="Amy Chua photo">
<h3>February<br><a href="#">Scott Sampson</a></h3>
<img src="images/sampson75.jpg" alt="Scott Sampson photo">
</aside>
</main>
<footer>
<p>&copy; 2016, San Joaquin Valley Town Hall, Fresno, CA 93755</p>
</footer>
</body>
</html>



main.css:

/* the styles for the elements */
* {
margin: 0;
padding: 0;
}
html {
background-color: white;
}
body {
font-family: Arial, Helvetica, sans-serif;
font-size: 100%;
width: 850px;
margin: 0 auto;
border: 3px solid #931420;
background-color: #fffded;
}
a:focus, a:hover {
font-style: italic;
}

/* the styles for the header */
header {
padding: 1.5em 0 2em 0;
border-bottom: 3px solid #931420;
background-image: -moz-linear-gradient(
30deg, #f6bb73 0%, #f6bb73 30%, white 50%, #f6bb73 80%, #f6bb73 100%);
background-image: -webkit-linear-gradient(
30deg, #f6bb73 0%, #fffded 30%, white 50%, #fffded 80%, #f6bb73 100%);
background-image: -o-linear-gradient(
30deg, #f6bb73 0%, #fffded 30%, white 50%, #fffded 80%, #f6bb73 100%);
background-image: linear-gradient(
30deg, #f6bb73 0%, #fffded 30%, white 50%, #fffded 80%, #f6bb73 100%);
}
header h2 {
font-size: 175%;
color: #800000;
}
header h3 {
font-size: 130%;
font-style: italic;
}
header img {
float: left;
padding: 0 30px;
}
.shadow {
text-shadow: 2px 2px 2px #800000;
}

/* the styles for the navigation menu */
nav {
clear: both;
}
nav ul {
list-style: none;
}
nav ul li {
float: left;
}
nav ul li a {
text-align: center;
display: block;
width: 168px;
padding: 1em 0;
text-decoration: none;
background-color: #931420;
color: #fffded;
font-weight: bold;
border-right: 2px solid #fffded;
}
nav ul li a.lastitem {
width: 170px;
border-right: none;
}
nav ul li a.current {
color: yellow;
}

/* the styles for the main content */
main {
clear: left;
}

/* the styles for the section */
section {
width: 575px;
float: right;
padding: 0 20px 20px 20px;
}
section h1 {
font-size: 150%;
padding: .5em 0 .25em 0;
margin: 0; /* If you remove this, the margins in normalize.css will be applied. */
}
section h2 {
color: #800000;
font-size: 130%;
padding: .5em 0 .25em 0;
}
section p {
padding-bottom: .5em;
}
section blockquote {
padding: 0 2em;
font-style: italic;
}
section ul {
padding: 0 0 .25em 1.25em;
}
section li {
padding-bottom: .35em;
}

/* the styles for the article */
article {
padding: .5em 0;
border-top: 2px solid #800000;
border-bottom: 2px solid #800000;
}
article h2 {
padding-top: 0;
}
article h3 {
font-size: 105%;
padding-bottom: .25em;
}
article img {
float: right;
margin: .5em 0 1em 1em;
border: 1px solid black;
}

/* the styles for the aside */
aside {
width: 215px;
float: right;
padding: 0 0 20px 20px;
}
aside h2 {
color: #800000;
font-size: 130%;
padding: .5em 0 .25em 0;
}

aside h3 {
font-size: 105%;
padding-bottom: .25em;
}
aside img {
padding-bottom: 1em;
}

/* the styles for the footer */
footer {
background-color: #931420;
clear: both;

}
footer p {
text-align: center;
color: white;
padding: 1em 0;
}
