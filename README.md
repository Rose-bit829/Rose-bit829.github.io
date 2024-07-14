

<html>
<head>
<meta charset= "utf-8">

<title>Assignment2</title>

<style>
* {
  box-sizing: border-box;
}

h1 {
  text-align: center;
}


section { 
  background-color: gray;
  border: 1px solid black;
  padding: 10px 10px 10px 10px;
  margin: 30px;
  position: relative;
  
}

p {
  position: relative;
  top: 20px;
}

.pink {
  background-color: darkSalmon;
  text-align: center
}

.blue {
  background-color: brown;
  color: white;
  text-align: center;
}

.green {
  background-color: palegoldenrod;
  text-align: center;
}

.pink, .blue, .green {
  border: 1px solid black;
  width: 80px;
  position: absolute;
  top: 0;
  right: 0;
  
}


@media (min-width: 992px) {
  section {
    width: 25%;
    float: left;
  }
  
}
  

@media (min-width: 768px) and (max-width: 991px) {
  section {
    width: 40%;
    float: left;
  }
  .beef {
    width: 40%;
    /*float: both;*/
  }
  .sushi {
    width: 90%;
    float: left;
  }
}
  

@media (max-width: 767px)

</style>
</head>
<body>

<h1>Our Menu</h1>

<section class= "chicken">
<div class= "pink">Chicken</div>
<p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Maecenas porttitor congue massa. Fusce posuere, magna sed pulvinar ultricies, purus lectus malesuada libero, sit amet commodo magna eros quis urna.
Nunc viverra imperdiet enim. Fusce est. Vivamus a tellus.
</p>
</section>

<section class= "beef">
<div class= "blue">Beef</div>
<p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Maecenas porttitor congue massa. Fusce posuere, magna sed pulvinar ultricies, purus lectus malesuada libero, sit amet commodo magna eros quis urna.
Nunc viverra imperdiet enim. Fusce est. Vivamus a tellus.
</p>
</section>

<section class = "sushi">
<div class= "green">Sushi</div>
<p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Maecenas porttitor congue massa. Fusce posuere, magna sed pulvinar ultricies, purus lectus malesuada libero, sit amet commodo magna eros quis urna.
Nunc viverra imperdiet enim. Fusce est. Vivamus a tellus.
</p>
</section>

</body>
</html>
