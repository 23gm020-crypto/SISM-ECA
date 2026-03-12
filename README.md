
<!DOCTYPE html>
<html>
<head>
<title>SISM-Extra-curriculum</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Arial;
  margin: 0;
}

/* Header */
header {
  padding: 60px;
  text-align: center;
  background: #486fa3;
  color: white;
}

/* Top navigation bar */
.navbar {
  display: flex;
  background-color: #333;
}

/* Navigation bar links */
.navbar a {
  color: white;
  padding: 14px 20px;
  text-decoration: none;
  text-align: center;
}

/* Change color on hover */
.navbar a:hover {
  background-color: #ddd;
  color: black;
}

/* Column container */
.container {  
  display: flex;
  flex-wrap: wrap;
}

/* Sidebar/left column */
.side {
  flex: 30%;
  background-color: #f1f1f1;
  padding: 20px;
}

/* Main column */
.main {
  flex: 70%;
  background-color: white;
  padding: 20px;
}

/* Fake image, just for this example */
.fakeimg {
  background-color: #aaa;
  width: 100%;
  padding: 20px;
}


/* Responsive layout - when the screen is less than 700px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 700px) {
  .container, .navbar {   
    flex-direction: column;
  }
}
</style>
</head>
<body>

<!-- Note -->


<!-- Header -->
<header>
  <h1>Soka International School Malaysia</h1>
  <p>ECA  <b>at</b> SISM</p>
</header>

<!-- Navigation Bar -->
<div class="navbar">
  <a href="index.html">About ECA</a>
  <a href="football.html">Football ECA</a>
  <a href="archery.html">Archery ECA</a>
</div>

<!-- Content Container -->
<div class="container">
  <div class="side">
   
  <div class="main">
    <h2>Extra-Curriculum At SISM</h2>
    <h5>FOOTBALL!!!!!</h5>
 <img src="2.jpg">
 <br>
    <h2>Football</h2>
    <h5>mar 3, 2026</h5>
    <p>Football ECA is a extra curricular activity that involves 2 teams of 11 players on a field. There are 2 goals, one for each team, and the goal is to score the ball into the opponents goal while protecting your own goal. The winner is decided by who has the most points after a 90 minute match. Football ECA is a great way to have fun and exercise at the same time, and dont worry about the heat as it is played at night!</p>

<video width="350" controls>
<source src="ICT.mp4" type="video/mp4">
</video>
    </div>
</div>

</body>
</html>
