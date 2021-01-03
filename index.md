
<html lang="en">
<head>
<title>CSS Template</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Arial, Helvetica, sans-serif;
}

/* Style the header */
header {
  background-color: #666;
  padding: 30px;
  text-align: center;
  font-size: 35px;
  color: white;
}

/* Create two columns/boxes that floats next to each other */
nav {
  float: left;
  width: 30%;
  height: 300px; /* only for demonstration, should be removed */
  background: #ccc;
  padding: 20px;
}

/* Style the list inside the menu */
nav ul {
  list-style-type: none;
  padding: 0;
}

article {
  float: left;
  padding: 20px;
  width: 70%;
  background-color: #f1f1f1;
  height: 300px; /* only for demonstration, should be removed */
}

/* Clear floats after the columns */
section:after {
  content: "";
  display: table;
  clear: both;
}

/* Style the footer */
footer {
  background-color: #777;
  padding: 10px;
  text-align: center;
  color: white;
}

/* Responsive layout - makes the two columns/boxes stack on top of each other instead of next to each other, on small screens */
@media (max-width: 600px) {
  nav, article {
    width: 100%;
    height: auto;
  }
}
</style>
</head>
<body>
  <h1>Welcome to the website Scuba!</h1>

<header>
  <h2>Pages</h2>
</header>

<section>
  <nav>
    <ul>
      <li><a href="#">Nurses and Doctors</a></li>
      <li><a href="#">Firefighters and Police Officers</a></li>
      <li><a href="#">filler</a></li>
    </ul>
  </nav>
  
  <article>
    <h1>Nurses and Doctors</h1>
    <p>Thank you for working very hard and sacrificing your lives for the sick and injured. The community is very grateful for all of the work you have done. We will always support you and help you in your most troubled times.</p>
  </article>
</section>

<footer>
  <p>Footer</p>
</footer>

</body>
</html>
