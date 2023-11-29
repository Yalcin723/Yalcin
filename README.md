<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Yalcin Web</title>
    
    <link rel="stylesheet" href="style.css" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  </head>
  <body>
    <div class="box">
      <img src="399024399_368005605744286_1527003328154971142_n.jpg">
      <h1>Yalcin Ege</h1>
      <h5>Web Developer - Web Designer</h5>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vel soluta ad similique eum! Aut quo, minima laboriosam accusantium dolore iure sed porro excepturi eaque, fugit magnam quos corrupti a odio.</p>
      <ul>
        <li><a href="https://github.com/Yalcin723"><i class="fab fa-github"  ></i></a></li>
        <li><a href="#"><i class="fab fa-twitter"  ></i></a></li>
        <li><a href="#"><i class="fab fa-instagram"  ></i></a></li>
        <li><a href="#"><i class="fab fa-discord"  ></i></a></li>
      </ul>
    </div>
</html>

body {
  margin: 0;
  padding: 0;
  background: url(kanye2.jpg);
  background-size: auto;
}
.box {
  width: 500px;
  background-color: grey;
  padding: 50px;
  text-align: center;
  margin: auto;
  margin-top: 5%;
  color: floralwhite;
  font-family: sans-serif;
  transition: 0.5s;
}
.box img {
  border-radius: 50%;
  height: 350px;
  width: 350px;
  cursor: pointer;
}
.box img:hover {
  transform: scale(0.9);
}
.box h1 {
  font-size: 40px;
  letter-spacing: 4px;
  font-weight: 100;
}
.box h5 {
  font-size: 20px;
  font-weight: 100;
  letter-spacing: 3px;
}
.box p {
  text-align: center;
}
ul {
  margin: 0;
  padding: 0;
}
.box li {
  display: inline-block;
  margin: 6px;
  list-style: none;
}
.box li a {
  font-size: 60px;
  color: floralwhite;
  transition: all ease-in-out 250ms;
}
.box li a:hover {
  color: forestgreen;
}
