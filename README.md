# Resturant-Project

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <link href="./ResturantPro.CSS" type="text/css" rel="stylesheet"> 
   <link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Roboto+Slab&display=swap" rel="stylesheet">
<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Satisfy&display=swap" rel="stylesheet">
<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Bad+Script&display=swap" rel="stylesheet">
   <title>Document</title>
   </head>
   <header>
    <div>
      <p>
        <button class="menu">contact</button>
      </p>
      <p>
        <button class="contact menu">menu</button>
      </p>
  </div>
       <h1 style="color:rgb(160, 74, 31)">Coffee <br>Cafe</h1>
       
   <div class="border-header">Welcome to <span style="color:chocolate">Coffee Cafe!</span> <br> The Best Coffee in Town.</div>
   </header>
   <main>
 <body>


<div class="grid">
 <div class="image1 a"><img src="https://www.caffesociety.co.uk/assets/recipe-images/latte-small.jpg">
<p style="text-align: center; color: white;">Cappuccino <br> $4.95</p>
</div>

 <div class="image2 b"><img src="https://www.acouplecooks.com/wp-content/uploads/2019/03/Coffee-Cold-Brew-004s.jpg">
  <p style="text-align: center; color: white;">Cold Brew <br> $3.95</p>
</div>

 <div class="image3 c"><img src="https://bakingmischief.com/wp-content/uploads/2019/12/caramel-latte-image-square.jpg">
  <p style="text-align: center; color: white;">Caramel Latte <br> $3.25</p>
</div>

 <div class="image4 d"><img src="https://images.immediate.co.uk/production/volatile/sites/30/2020/08/chai-latte-4e5fe2f.jpg?quality=90&webp=true&resize=440,400">
  <p style="text-align: center; color: white;">Chai Tea Latte <br> $5.75</p>
</div>

</div>
  
</body>
 </main>
</html>

 html {
    background-image: url("https://images.unsplash.com/photo-1463797221720-6b07e6426c24?ixid=MXwxMjA3fDB8MHxzZWFyY2h8MXx8Y29mZmVlJTIwc2hvcHxlbnwwfHwwfA%3D%3D&ixlib=rb-1.2.1&w=1000&q=80");
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
    height: 500px;
}

.menu, .contact {
    border: none;
    display: block;
    padding: 8px 16px;
    text-align: center;
    cursor: pointer;
    font-size: 28px;
    font-family: "Roboto Slab";
    float: right;
    clear: none;
    margin-top: 20px;
    opacity: 0.95;
}

.menu:hover {
    background-color: lightsalmon;
}

h1 {

text-align: center;
font-family: "Satisfy";
font-size: 60px;
text-shadow: 3px 3px 3px;
letter-spacing: 20px;
margin-bottom: 200px;
padding-top: 8px;
padding-bottom: 8px;
padding-left: 10px;
width: 20%;
opacity: 1;
background-color: rgba(221, 183, 134, 0.9);
border-radius: 70px;
}




.border-header {
    text-align: center;
    font-weight: bold;
    font-size: 50px;
    background-color: rgba(221, 195, 176, 0.9);
    font-family: 'Bad Script';
    width: 50%;
    margin-top: 20px;
    margin-left: 350px;
    padding: 10px;
    border-radius: 10px;
}

.grid {
    display: grid;
    width: 1400px;
    height: 1400px;
    grid-template: repeat(4, 1fr) / repeat(4, 1fr);
    grid-row-gap: 15px;
    grid-column-gap: 90px;
    margin-top: 100px;
}

div.image1  {
box-shadow: 3px 3px;
background-color:rgb(210, 105, 30, 0.8);
padding: 20px;
padding-bottom: 120px;
}

div.image2 {
box-shadow: 3px 3px;
background-color: rgba(210, 105, 30, 0.8);
padding: 20px;
padding-bottom: 120px;
}

div.image3 {
box-shadow: 3px 3px;
background-color:rgba(210, 105, 30, 0.8);
padding: 20px;
padding-bottom: 120px;
}

div.image4 {
box-shadow: 3px 3px;
background-color: rgb(210, 105, 30, 0.8);
padding: 20px;
padding-bottom: 120px;
}


.a {
font-family: 'Bad Script';
letter-spacing: 2.5px;
font-size: 20px;
}

.b {
 font-family: 'Bad Script';
 letter-spacing: 2px;
font-size: 20px;
}

.c {
font-family: 'Bad Script';
letter-spacing: 2px;
font-size: 20px;
}

.d {
font-family: 'Bad Script';
letter-spacing: 2px;
font-size: 20px;
}


img {
    object-fit: cover;
    width: 100%;
    height: 100%;
}



