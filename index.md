
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
  <h2>
 <iframe width="420" height="315"
src="https://www.youtube.com/embed/tgbNymZ7vqY">
</iframe>
  </h2>
</header>

<section>
  <nav>
    <ul>
      <li><a href="#">Nurses and Doctors</a></li>
      <li><a href="#">Firefighters</a></li>
      <li><a href="#">filler</a></li>
    </ul>
  </nav>
  
  <article>
    <h1>Nurses and Doctors</h1>
    <p>Thank you for working very hard and sacrificing your lives for the sick and injured. The community is very grateful for all of the work you have done. We will always support you and help you in your most troubled times.</p>
  </article>
  
  <article>
  <h1>Firefighters</h1>
  <p>Thank you for protecting the community and always being on high alert in case of fires. We appreciate all you have done for the community and we understand that being a firefighter is not an easy task.We will always be there for you and give a hand to help. Thank you for all you have done.</p>
</section>

<footer>
  <p>Footer</p>
</footer>

</body>
</html>
