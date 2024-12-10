# Ex.07 Restaurant Website
## Date:10/12/2024

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
web.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web app</title>
    <link rel="stylesheet" href="web.css">
</head>
<body>
    <div align="center" id="template">

        <img src="template.png" alt="">
        <a href="Ocean_food.html" id="tag" >Ocean foods</a>
        <a href="order_now.html" id="order">Order Now </a>
        <a href="contact.html" id="contact">Contact</a>
        <a href="administration.html" id="offers">Administraion</a>
        <input type="text" placeholder="search" id="search">

    </div>
    <footer align="center" id="copywrite">
        Designed and devloped by Ameen Basha &copy 2024
    </footer>
</body>
</html>
```
```
web.css

*{
    margin: 0px;
    padding: 0px;
}

#template
{
    align-items: center;
    width: 100%;
    object-fit: cover;
    /* height: 800px; */
}
#tag
{
    position: absolute;
    top:40px;
    left: 280px;
    text-decoration: none;
    color: antiquewhite;
    font-weight: 400;
    color: orange;
    text-transform: capitalize;
    font-size: 40px;
    
}
#order
{
    position: absolute;
    top:50px;
    left: 540px;
    text-decoration: none;
    color: antiquewhite;
    font-weight: 400;
    font-size: 30px;
}
#contact
{
    position: absolute;
    top:50px;
    left: 800px;
    text-decoration: none;
    color: antiquewhite;
    font-weight: 400;
    font-size: 30px; 
}
#offers
{
    position: absolute;
    top:50px;
    left: 1000px;
    text-decoration: none;
    color: antiquewhite;
    font-weight: 400;
    font-size: 30px;   
}
#search
{
    position: absolute;
    top:50px;
    left: 1350px;
    text-decoration: none;
    color: antiquewhite;
    font-weight: 400;
    font-size: 30px; 
    background-color: rgba(255,255,255,0.2); 
    border-color: black;
    font-size: 25px;
}
#copywrite
{
    background-color: rgb(255, 115, 0);
    color:black;
    font-size: large;
}
```

```
order_now.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>order now</title>
    <style>
        body{
            background-color: rgba(255, 60, 0, 0.733);
        }
        #body
        {
            border: 5px solid black;
           color: black;
           background-color:wheat;
            border-radius: 25px;
            height: 600px;
        }
         img
        {
                margin-top: 100px;
                height: 200px;
                width: auto;
                margin-left: 25px;

        } 
        #fish
        {
            height: 200px;
            width: 300px;
        }
        .dish
        {
           margin-left: 240px;
        }
        #dish1
        {
            margin-left: 280px;
        }
        #dish2
        {
            margin-left: 150px;
        }
        p{
            margin-top: 75px;
            margin-left: 250px;
            font-size: 25px;
        }
    </style>
</head>
<body>
    <div id="body">
    <h1 align="center">Order our best food options</h1>
    <div>
        <img src="crab.jpg" alt="crab">
        
        <img src="shrimp_fry.jpg" alt="">
        <img id ="fish" src="salmon.avif" alt="">
        <img src="labster.webp" alt="">
        <b class ="dish"  id="dish2"> Crab curry </b>
        <b class ="dish" >shrimp fry</b>
        <b class ="dish " id="dish1" > Slamon</b>
        <b class ="dish" >grilled labster </b>
        <p > - Delicious Choices Crafted for Every Tast, Order the dish and enjoy</p>
    </div>
    </div>
</body>
</html>
```
```
Ocean_food.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ocean Foods</title>
    <style>
        pre{
            padding: 15px;
            font-size: large;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
            
        }
       #order
        {
                display: inline;
                margin-left: 10px;
                color: blueviolet;
        }
        #h1
        {
            text-align: center;
            font-style: oblique;
            margin-top: 10px;
            padding: 25px;
            position: relative;
            top: 50px;
            left: 0px;
            background-color: rgb(185, 255, 232);
        }
        body
        {
            background-color: rgba(238, 207, 212,0.3);
        }
    </style>
</head>
<body >
    
    <h1 id="h1">About Us - Ocean Foods</h1>
    <pre>
        

<b>Welcome to Ocean Foods – Where Freshness Meets the Ocean!</b>

At Ocean Foods, we are committed to offering a dining experience that celebrates the ocean's bounty. Situated along the coast, our restaurant specializes in serving the freshest, highest quality seafood, sourced directly from local fishermen and sustainable suppliers.

Our journey started with a simple vision: to create a place where people can enjoy a variety of delicious seafood dishes made with love, care, and the finest ingredients. Whether you're a lifelong seafood lover or trying it for the first time, we promise to deliver an unforgettable meal every time.

<b>What Makes Us Special?</b>
Fresh, Local, and Sustainable
We work closely with local fishermen to ensure that every dish is prepared using the freshest seafood available. We also prioritize sustainability, supporting eco-friendly fishing practices that protect the oceans for future generations.

A Menu Full of Flavor
From our signature fish and chips to innovative seafood creations, each dish at Ocean Foods is crafted to highlight the natural flavors of the ocean. We offer something for everyone, whether you prefer grilled, fried, or steamed seafood, or something with a bit of flair.

A Warm, Welcoming Atmosphere
Our restaurant is designed with comfort in mind. Whether you're here for a casual meal with family or a special night out, we strive to create an inviting space where you can relax and enjoy your meal in good company.

<b>Why Choose Ocean Foods?</b>
Sustainability: We only source seafood from sustainable and responsible fisheries.
Freshness: We receive daily deliveries of fresh fish and seafood to ensure the best quality.
Community: We are proud to support local fishermen and the surrounding community.
Thank you for choosing Ocean Foods – we look forward to serving you ocean-fresh dishes that will delight your taste buds!

<b><a href="order_now.html" id="order" target="_blank"> Join Us Today!</a></b>Experience the taste of the ocean, right here at Ocean Foods. Whether it's a quick lunch or a special dinner, we can't wait to welcome you!

    </pre>

</body>
</html>
```
```
contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">  
    <style>
      *{
        font-family: Arial, Helvetica, sans-serif;
      }
        #contact
        {
            display: flex;
            font-size: 30px;
            gap: 10px;
            background-color:	rgba(250, 235, 215,0.2);
            border: 1px inset black;
            height: 800px;
        }
        #contact>div{
            width: 30%;
            /* border: 5px solid pink; */
            padding: 50px;
        }
        #div1
        {
            position: absolute;
            top:40px;
            right: 100px;
            border:1px inset whitesmoke;
            background-color: whitesmoke;
            border-radius: 50px;
        }
        input{
            font-size: 25px;
            margin-left: 30px;
        }
        #textarea
        {
          margin-left: 25px;
          padding: 20px;
          border: #FFFFFF;
          padding: 10px;
          border-radius: 10px;
          font-size: 20px;
        }

        #submit
        {
          background-color: #FF5200;
          border-radius: 10px;
          color: whitesmoke;
        }
        #label2
        {
          border: whitesmoke;
          padding: 10px;
          border-radius: 10px;

        }
        #label1
        {
          border: whitesmoke;
          padding: 10px;
          border-radius: 10px;
        }
        #info
        {
          padding: 20px;
          
        }

    </style>
    <script>
            function f1()
            {
                document.getElementById("label3").innerHTML="Informations are saved";
            }
    </script>
    
</head>
<body>
    <div id="contact">
      
           <div id="info">
              <b style="text-decoration: underline ;"> Ocean Food</b>
              <br>
              <br>
              <b style="font-size: 50px;">Customer <br> Support</b>
              <br>
              <p>Email:suppor@oceanfoods.in</p>
              <br><br>
              <b>Find us on</b>
              <br>
             <!-- <i class='fab fa-instagram' style='font-size:48px;color:red'></i> 
             <a href="ameenbashanawaz.123@gmail.com" class="fa fa-linkedin">	</a>
              <a href="#" class="fa fa-pinterest"></a>
               -->
               <i class="fab fa-instagram"  style="font-size: 50px; color: #E4405F ; margin-left: 20px; padding: 20px;"></i>
               <i class="fab fa-facebook-f"   style="font-size: 50px; color: #3b5998;  margin-left: 20px; padding: 20px;"></i>
               <i class="fab fa-linkedin-in"  style="font-size: 50px; color: #0077b5; margin-left: 20px; padding: 20px;"></i>
               <i class="fab fa-twitter"  style="font-size: 50px; color: #0077b5; margin-left: 20px; padding: 20px;"></i>
               <pre>
<b>Corporate Office</b>
No. 55, Sy No. 8-14, Ground Floor, I&J Block, Embassy TechVillage, Outer <br>Ring Road, Devarbisanahalli, Bengaluru 560 103, Karnataka, India, <br> Corporate Identity  <br>Number: U74110KA2013PLC096530 Registration Number: 096530
               </pre>
            </div>
        <div  id="div1">
            <hr style="font-style: italic;">
            <b align="center"> Get in touch </b>
            <br>
            <br>

            <label id="label2"><input type="text" id="label2" placeholder="Enter Name"></label>
            <br>
            <br>
            <label id="label1"> <input type="text" id="label1"  placeholder="Enter Number"></label>
            <br>
            <br>
            <label ><textarea  id="textarea" placeholder="Enter Message"  rows="10" cols="50"></textarea></label>
            <br>
            <br>
            <label id="label3"> <input type="submit"  id="submit" placeholder="Enter" onclick="f1()"></label>
            <hr>
        </div>

    </div>
</body>
</html>

```

```
administration.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administraion</title>
    <style>
        body
        {
            background-color: rgba(255, 60, 0, 0.733);
        }
        #container
        {
            background-color: whitesmoke;
            display: flex;
            border: 5px solid aquamarine;
            height: 500px;
            width: auto;
            justify-content: space-evenly;
            border-radius: 100px;
        }
        #main
        {
            border: 1px solid black;
        }
        .box
        {
            position: relative;
            display: inline-block;
            top: 150px;
            height: 200px;
            width: 200px;
            border: 2px solid black;
            background-color: pink;
            border-radius: 50%;
        }
        #head
        {
            text-align: center;
            font-size: 40px;
            font-family: 'Times New Roman', Times, serif;
            font-weight: 700;
            background-size:cover ;
        }
        #name
        {
            justify-content: space-evenly;
        }
        #n1
        {
            position: absolute;
            bottom: 170px;
            left: 100px;
            font-weight: 600;
            font-size: large;
            font-style: oblique;
        }
        #n2
        {
            position: absolute;
            bottom: 170px;
            left: 370px;
            font-weight: 600;
            font-size: large;
            font-style: oblique;
        }
        #n3
        {
            position: absolute;
            bottom: 170px;
            left: 600px;
            font-weight: 600;
            font-size: large;
            font-style: oblique;
        }
        #n4
        {
            position: absolute;
            bottom: 170px;
            left: 900px;
            font-weight: 600;
            font-size: large;
            font-style: oblique;
        }
        #n5
        {
            position: absolute;
            bottom: 170px;
            left: 1150px;
            font-weight: 600;
            font-size: large;
            font-style: oblique;
        }
    </style>
    
</head>
<body>
    <div align="center" id="head">Head Chef</div>
    <div id="container">

            <div ><img src="chef.jpg" alt="" class="box"></div>
            <div ><img src="sous chef.jpeg" alt="" class="box"></div>
            <div ><img src="line chef.jpg" alt="" class="box"></div>
            <div ><img src="head chef.jpg" alt="" class="box"></div>
            <div ><img src="gordon.jpg" alt="" class="box"></div>

    </div>
    <p id="n1">K. Damodharan </p> 
        <p id="n2">Vikas  Khanna</p>
         <p id="n3">Madhampatty  Rangaraj</p>
        <p id="n4">Sanjeev Kapoor</p>  
        <p id="n5">Gordon Ramsay</p>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot (72).png>)
![alt text](<Screenshot (73).png>)
![alt text](<Screenshot (74).png>)
![alt text](<Screenshot (75).png>)
![alt text](<Screenshot (76).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
