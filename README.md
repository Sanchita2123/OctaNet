# OCTONET (Index.html)
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="utf-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="viewport" content=
	  "width=device-width, initial-scale=1.0">
	<link rel="stylesheet" href="style.css">
	<title>Landing Page</title>
</head>
<body>
	   <nav></nav>
		<div class="heading">Landing Page</div>
	  	<span class="sideMenuButton"
	  	     onclick="openNavbar()">
	  	     &#9776
	  	     </span>
	  	     <div class="navbar">
	  	     	<ul>
	  	     		<li><a href="#Home">Home</a></li>
	  	     		<li><a href="#">About</a></li>
                    <li><a href="#">Sign up</a></li>
	  	     	</ul>	
	  	     </div>
	  	</nav>

	<div class="sideNavigationBar"
	id="sideNavigationBar">
	<a href="#" class="closeButton"
	  onclick="closeNavbar()">
	  </a>
	  <a href="#">Home</a>
	  <a href="#">About</a>
	  <a href="#">Sign up</a>
    </div>
    <div class="line" id="Home">
</body>
<div class="line" id="Home">
	<div class="side1">
		<button>
			<a href=
			"https://www.geeksforgeeks.org/">
			    Explore more
			</a>
		</button>

	</div>

	<div class="side2">
		<img src="https://media.geeksforgeeks.org/wp-content/cdn-uploads/20220401124017/HTML-Tutorail.png"
		width="500">
	</div>
</div>
<section class="about" id="My Files">
	<div class="content">
		<div class="title">
			<span>Courses</span>
		</div>
		<div class="topic">
			<a href=""target="_blank">
				DSA
			</a>
	</div>
	<p>
		The team DSA stands for data structures and algorithms. It is a combination of two separate yet interrelated topics.
	</p>
</div>
</html>
------------------------------------------------------------------------------------------------------------------------------------------------

#SCRIPT.JS:
function openNavbar() {
	document.getElementById("sideNavigationBar")
	     .style.width = "50%";
}
function closeNavbar() {
	document.getElementById("sideNavigationBar")
	    .style.width = "0%";
}

------------------------------------------------------------------------------------------------------------------------------------------------

#STYLE.CSS:
{
	padding: 0;
	margin: 0;
	box-sizing: border-box;
}

body{
	background-color: white;
	color: black;
	font-family: "Fira Sans", sans-serif;
	background-color: white;
}

nav{
	width:100%;
	height: 80px;
	display: flex;
	justify-content: space-between;
	padding: 20px 5%;
	background-color: white;
}

nav.heading{
	font-size: 30px;
	font-weight: 700;
	color: white;
}

nav ul{
	display: flex;
	list-style: none;
}

nav ul li{
	padding: 8px 15px;
	border-radius: 10px;
}
