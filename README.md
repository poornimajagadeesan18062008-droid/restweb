# Ex.07 Restaurant Website
## Date:08/10/2025

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
home.html

<html>
    <head>
        <title>Home</title>
        <link rel="stylesheet" href="home1.css">
    </head>
    <body>
        <div class="background">
        <div class="contents">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
        <div class="restname">
            <h1><b><i>Seoul City Restaurant</i></b></h1>
        </div >
       
        <div class="lines">
            <i>"Taste the bold flavors of Korea"</i>
            <p>"Discover the soul of Korea in Seoul City Restaurant, through our authentic dishes, crafted with the vibrant, bold flavors that define Korean cuisine and transport your senses to a culinary adventure like no other".</p>
        </div>
        <div class="image1">
            <img src="ambi1.jpeg" width="600" height="300">
        </div>
        <div class="image2">
            <img src="ambi2.jpeg" width="600" height="300">
        </div>
        <footer class="copyrights">
            &copy; POORNIMA J - (25015718)
        </footer>
        </div>
    </body>
</html>

home1.css

.background {
    width: 1470px;
    height: 680px;
    color:purple;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family:'Times New Roman', Times, serif;
    background-image: url(background.jpeg);
    background-size: cover;
}

.contents {
    width: 550px;
    height: 25px;
    border: 2px solid ;
    padding: 10px;
    background-color: rgb(19, 112, 194);
    text-align: center;
    top: 5px;
    left: 900px;
    position: relative;
    word-spacing: 70px;
}

.restname {
    color:;
    font-family: Verdana;
    text-align: left;
    position: relative;
    font-size: 200%;
    top: -50px;
}



.lines {
    color: brown;
    font-family: Verdana;
    text-align: center;
    position: relative;
    font-size: 130%;
    top: -100px;
}

.image1 {
    position: relative;
    top: -90px;
    left: 100px;
    background-size:contain;
}

.image2 {
    position: relative;
    top: -390px;
    left: 800px;
    background-size:contain;
}

.copyrights{
    width: 1510px;
    height: 20px;
    background-color: gray;
    text-align: center;
    top: -330px;
    left: -20px;
    position: relative;
}

menu.html

<html>
    <head>
        <title>Home</title>
        <link rel="stylesheet" href="menu1.css">
    </head>
    <body>
        <div class="background">
        <div class="contents">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
        <div class="menu">
            <h1><b>MENU</b></h1>
        </div >
        <div class="menugrid">
            <div class="menuitem">
                <img src="cold soy milk noodles.jpeg" width="300" height="150">
                <h1>cold milk noodles</h1>
                <p>Rs.200</p>
            </div>
            <div class="menuitem">
                <img src="hotpot.jpeg" width="300" height="150">
                <h1>Hotpot</h1>
                <p>Rs.500</p>
            </div>
            <div class="menuitem">
                <img src="Jajangmyeon.jpeg" width="300" height="150">
                <h1>Jajangmyeon</h1>
                <p>Rs.800</p>
            </div>
            <div class="menuitem">
                <img src="Kimchi-Jeon.jpeg" width="300" height="150">
                <h1>Kimchi-Jeon</h1>
                <p>Rs.300</p>
            </div>
            <div class="menuitem">
                <img src="Soft Tofu Stew.jpeg" width="300" height="150">
                <h1>Tofu stew</h1>
                <p>Rs. 700</p>
            </div>
            <div class="menuitem">
                <img src="Tteokbokki.jpeg" width="300" height="150">
                <h1>Tteokbokki</h1>
                <p>Rs. 450</p>
            </div>
            <div class="menuitem">
                <img src="mochi.jpeg" width="300" height="150">
                <h1>Blueberry Mochi</h1>
                <p>Rs. 150</p>
            </div>
            
        </div>
        <footer class="copyrights">
            &copy; POORNIMA J (25015718)
        </footer>
        </div>
    </body>
</html>

menu1.css

.background {
    width: 1470px;
    height: 680px;
    color:purple;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family:'Times New Roman', Times, serif;
    background-image: url(background.jpeg);
    background-size: cover;
}

.contents {
    width: 550px;
    height: 25px;
    border: 2px solid black;
    padding: 10px;
    background-color: blue;
    text-align: center;
    top: 5px;
    left: 900px;
    position: relative;
    word-spacing: 70px;
}

.menu {
    color: brown;
    font-family: Verdana;
    text-align: left;
    position: relative;
    font-size: 200%;
    top: -50px;
}

.menugrid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(90px, 1fr));;
    gap: 50px;
    justify-items: center;
    padding: 20px;
    margin-top: -50px;
}

.menuitem {
    background-color: beige;
    border-radius: 10px;
    text-align: center;
    padding: 20px;
    width: 100%;
}

.menuitem img {
    border-radius: 10px;
    width: 100%;
    height: 180px;
    object-fit: cover;
}

.menuitem h1 {
    font-size: 1.5em;
    color: black;
    margin-top: 15px;
}

.menuitem p {
    color: black;
    margin-bottom: 0px;
}

.copyrights{
    width: 1510px;
    height: 20px;
    background-color: gray;
    text-align: center;
    top: 100px;
    left: -20px;
    position: relative;
}


admin.html

<html>
    <head>
        <title>Home</title>
        <link rel="stylesheet" href="admin1.css">
    </head>
    <body>
        <div class="background">
        <div class="contents">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
        <div class="admin">
            <h1><b>ADMINISTRATION TEAM</b></h1>
        </div>
        <div class="admingrid">
            <div class="adminlist">
                <img src="Photo - Copy.jpg" width="130" height="250">
                <h1>POORNIMA J</h1>
                <p class="post">CEO</p>
            </div>
            <div class="adminlist">
                <img src="thalapathy.jpeg" width="130" height="250">
                <h1>Sachien</h1>
                <p class="post">HR</p>
            </div>
            <div class="adminlist">
                <img src="jin.jpeg" width="130" height="250">
                <h1>Mr.Kim Seok Jin</h1>
                <p class="post">Executive Chef</p>
            </div>
            <div class="adminlist">
                <img src="jeon jungkook.jpeg" width="130" height="250">
                <h1>Mr.Jeon Jungkook</h1>
                <p class="post">Assistant Chef</p>
            </div>
            <div class="adminlist">
                <img src="kimtaehyung.jpeg" width="130" height="250">
                <h1>Mr.Kim Taehyung</h1>
                <p class="post">Marketing Head</p>
            </div>
            <div class="adminlist">
                <img src="kimnamjoon.jpeg" width="130" height="250">
                <h1>Mr.Kim Namjoon</h1>
                <p class="post">Customer Service Manager</p>
            </div>
        </div>
        <footer class="copyrights">
            &copy; POORNIMA J - (25015718)
        </footer>
        </div>
    </body>
</html>

admin1.css

.background {
    width: 1470px;
    height: 680px;
    color:purple;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family:'Times New Roman', Times, serif;
    background-image: url(background.jpeg);
    background-size: cover;
}

.contents {
    width: 550px;
    height: 25px;
    border: 2px solid black;
    padding: 10px;
    background-color: blue;
    text-align: center;
    top: 5px;
    left: 900px;
    position: relative;
    word-spacing: 70px;
}

.admin {
    color: brown;
    font-family: Verdana;
    text-align: left;
    position: relative;
    font-size: 200%;
    top: -50px;
}

.admingrid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(90px, 1fr));;
    gap: 50px;
    justify-items: center;
    padding: 20px;
    margin-top: -50px;
}

.adminlist{
    background-color: beige;
    border-radius: 10px;
    text-align: center;
    padding: 20px;
    width: 100%;
}

.adminlist img {
    border-radius: 10px;
    width: 100%;
    height: 250px;
    object-fit: cover;
    border-radius: 50% / 35%;
}

.adminlist h1 {
    font-size: 1.5em;
    color: black;
    margin-top: 15px;
}

.adminlist p {
    color: black;
    margin-bottom: 0px;
}

.copyrights {
    width: 1510px;
    height: 20px;
    background-color: gray;
    text-align: center;
    top: 30px;
    left: -20px;
    position: relative;
}

contact.html

<html>
    <head>
        <title>Home</title>
        <link rel="stylesheet" href="contact1.css">
    </head>
    <body>
        <div class="background">
        <div class="contents">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
        <div class="contact">
            <h1><b>CONTACT</b></h1>
        </div>
        <div class="info">
            <h1>Visit us :</h1>
            <p>Seoul City Restaurant<br>15,East Eve,<br>Raja Annamalaipuram, Chennai, <br>Tamil Nadu India</p>
            <br>
            <h1>Phone:</h1>
            <p>+91 99909 94359</p>
            <br>
            <h1>Email ID:</h1>
            <p>seoulcityrestaurant@gmail.com</p>
        </div>
        <footer class="copyrights">
            &copy; POORNIMA J - (25015718)
        </footer>
        </div>
    </body>
</html>

contact1.css

.background {
    width: 1470px;
    height: 680px;
    color:purple;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family:'Times New Roman', Times, serif;
    background-image: url(background.jpeg);
    background-size: cover;
}

.contents {
    width: 550px;
    height: 25px;
    border: 2px solid black;
    padding: 10px;
    background-color: blue;
    text-align: center;
    top: 5px;
    left: 900px;
    position: relative;
    word-spacing: 70px;
}

.contact {
    color:blue ;
    font-family: italic;
    text-align: left;
    position: relative;
    font-size: 300%;
    top: -50px;
}

.info {
    color: purple;
    font-family: Times New Roman;
    position: relative;
    top: -130px;
    left: -20;
    text-align: center;
}

.copyrights{
    width: 1510px;
    height: 20px;
    background-color: gray;
    text-align: center;
    top: -20px;
    left: -20px;
    position: relative;
}
```

## OUTPUT:
![alt text](<Screenshot (63).png>)
![alt text](<Screenshot (64).png>)
![alt text](<Screenshot (65).png>)
![alt text](<Screenshot (66).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
