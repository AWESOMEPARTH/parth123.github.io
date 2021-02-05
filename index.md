<html>
<head>
	<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.0/css/all.css" integrity="sha384-lZN37f5QGtY3VHgisS14W3ExzMWZxybE1SJSEsQp9S+oqd12jhcu+A56Ebc1zFSJ" crossorigin="anonymous">
	 <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
	<title>Introduction to IoT</title>
 <meta charset="UTF-8">
  <meta name="description" content="Free Web tutorials">
  <meta name="keywords" content="HTML,CSS,XML,JavaScript">
<style>
body{
	background-color:powderblue;
	 margin: 0;
}
table{
	background-color:#ff5722;
	border-style:outset;
	font-family:century gothic; 
	color:white;
}
table tr{
	/*background-color:#ff5722;
	border-style:outset;*/
	font-family:century gothic;
}
table tr td{
	/*background-color:#ff5722;
	border-style:outset;*/
	font-family:century gothic;
}
/* Style the header 
.header {
  background-color: #f1f1f1;
  padding: 20px;
  text-align: center;
}*/

/* Style the top navigation bar */
div.topnav {
  overflow: hidden;
  background-color: #333;
   position: -webkit-sticky; /* Safari */
  position: sticky;
  top: 0;
}

/* Style the topnav links */
.topnav a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-family: Georgia;
}

/* Change color on hover */
.topnav a:hover {
  background-color: #ddd;
  color: black;
  
}
.navbar {
  overflow: hidden;
  background-color: #333;
  font-family: Arial;
}

/* Links inside the navbar */
.navbar a {
  float: left;
  font-size: 16px;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

/* The dropdown container */
.dropdown {
  float: left;
  overflow: hidden;
}

/* Dropdown button */
.dropdown .dropbtn {
  font-size: 16px; 
  border: none;
  outline: none;
  color: white;
  padding: 14px 16px;
  background-color: inherit;
  font-family: inherit; /* Important for vertical align on mobile phones */
  margin: 0; /* Important for vertical align on mobile phones */
}

/* Add a red background color to navbar links on hover */
.navbar a:hover, .dropdown:hover .dropbtn {
  background-color: red;
}

/* Dropdown content (hidden by default) */
.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f9f9f9;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}

/* Links inside the dropdown */
.dropdown-content a {
  float: none;
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  text-align: left;
}

/* Add a grey background color to dropdown links on hover */
.dropdown-content a:hover {
  background-color: #ddd;
}

/* Show the dropdown menu on hover */
.dropdown:hover .dropdown-content {
  display: block;
}

h1.h1{
	font-family:Algerian;
	background-color: green; 
}
</style>
</head>
<body>

<!<div class="header">
  <h1></h1>
</div>

	<div class="navbar">
		<a href="iot.html">Introduction&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp</a>
  <a href="history.html">History&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp</a>
  <a href="benefits.html">Benefits&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp</a>
  <!--<a href="applications.html">Applications&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp</a>-->
   <div class="dropdown">
	<button class="dropbtn">Applications
		<i class="fa fa-caret-down"></i>
	</button>
  <div class="dropdown-content" id="myDropdown">
    <a href="agriculture.html">Agriculture</a>
    <a href="cars.html">Connected Cars</a>
    <a href="home.html">Smart Home</a>
    <a href="wearables.html">Wearables</a>
    <a href="city.html">Smart City</a>
  </div>
  </div>
  <a href="resources.html">&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbspChallenges</a>
	</div>
<!<i class="fas fa-cloud"></i>
<h1 class="h1" align="center">INTRODUCTION</h1>
	<table>
		<tr>
			<td>The internet of things (IoT) is a computing concept that describes the idea of everyday physical objects being connected to the internet and being able to identify themselves to other devices. </td>
		</tr>
<tr>
	<td>The Internet of Things is actually a pretty simple concept, it means taking all the things in the world and connecting them to the internet.
When something is connected to the internet, that means that it can send information or receive information, or both. This ability to send and/or receive information makes things smart, and smart is good.<br></td>
</tr>
<tr>
	<td>In the Internet of Things, all the things that are being connected to the internet can be put into three categories:
		<ol type="1">
			<li>Things that collect information and then send it.Things that receive information and then act on it.
			<li>Things that receive information and then act on it.
			<li>Things that do both.
			</td>
	</tr>
	<tr>
<td>Over 9 billion ‘Things’ (physical objects) are currently connected to the Internet, as of now. In the near future, this number is expected to rise to a whopping 20 billion.
</td>
	</tr>
	<tr>
		<td>In the upcoming years, IoT-based technology will offer advanced levels of services and practically change the way people lead their daily lives. Advancements in medicine, power, gene therapies, agriculture, smart cities, and smart homes are just a very few of the categorical examples where IoT is strongly established.
		</td>
	</tr>
	</table><script>
/* When the user clicks on the button, 
toggle between hiding and showing the dropdown content */
function myFunction() {
  document.getElementById("myDropdown").classList.toggle("show");
}

// Close the dropdown if the user clicks outside of it
window.onclick = function(e) {
  if (!e.target.matches('.dropbtn')) {
  var myDropdown = document.getElementById("myDropdown");
    if (myDropdown.classList.contains('show')) {
      myDropdown.classList.remove('show');
    }
  }
}
</script>
	<script>
/* When the user clicks on the button, 
toggle between hiding and showing the dropdown content */
function myFunction() {
  document.getElementById("myDropdown").classList.toggle("show");
}

// Close the dropdown if the user clicks outside of it
window.onclick = function(e) {
  if (!e.target.matches('.dropbtn')) {
  var myDropdown = document.getElementById("myDropdown");
    if (myDropdown.classList.contains('show')) {
      myDropdown.classList.remove('show');
    }
  }
}
</script>
	<img src="iot2.png" alt="This is the of IoT" height="500" width="1365">
		</body>
</html>
