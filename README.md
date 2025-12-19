# Ex.06 Restaurant Website
## Date:19-12-2025

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
rest.html

<html>
    <head>
        <title>Tsuki Tei</title>
        <link href="rest.css" rel="stylesheet">
    </head>
    <body>
        <div class="restname">
            <h1>Tsuki Tei</h1>
        </div>
        <div class="caption">
            <p>"Tsuki Tei — Where the Moon Inspires Every Flavor"</p>
        </div>
        <div  class="link">
            <a href="rest.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Administration</a>
            <a href="cont.html">Contact</a>
        </div>
        <div class="footer">&copy; Suruthika V(25000884)</div>  
    </body>
</html>

rest.css

body
{
    background-image: url('admin-bg.jpg');
    background-repeat: no-repeat;
    background-size: cover;
   
    

}
.restname
{
   position: fixed;
   padding-left: 500px;
   font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
   margin-left: 5px;
   font-size: 50;
   color: rgb(251, 247, 191);
}
.footer
{
    position: fixed;
    bottom: 0;
    width: 100%;
    background-color: bisque;
    color: rgb(6, 6, 6);
    text-align: center;
    padding:5px;
    left:0;
}
.caption
{
    
    
    margin-left: 5px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    font-size: 30;
    color: rgb(249, 137, 137);
    padding-left: 470px;
    padding-top: 200px;
    
    
}

.link {
  display: flex;
  position: fixed;
  top: 10;
  justify-content: space-evenly;
  width: 800px;
  height: 55px;
  font-size: 22px;
  margin-left: 330px;
}

a {
  text-decoration: none;
  color: rgb(215, 241, 249);
}

menu.html

<html>
    <head>
        <title>Menu</title>
        <link href="menu.css" rel="stylesheet">
    </head>
    <body>
        <div class="link">
            <a href="rest.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Administration</a>
            <a href="cont.html">Contacts</a>
        </div>
        <div class="restname">
            <p>Tsuki Tei</p>
        </div>
        <div class="mainmenu">
            <div class="menu-item">
                <img src="miso.jpg">
                <h2>Miso Soup</h2>
                <h4>A serene opening: slow-brewed soybean broth, silken tofu, and hand-cut scallions</h4>
            </div>
            <div class="menu-item">
                <img src="tofu.jpg">
                <h2>Agedashi Tofu</h2>
                <h4>Gently crisped tofu resting in fragrant dashi, finished with grated daikon</h4>
            </div>
            <div class="menu-item">
                <img src="nigiri.jpg">
                <h2>Salmon Nigiri</h2>
                <h4>Line-caught salmon, delicately sliced and placed upon perfectly seasoned sushi rice</h4>
            </div>
            <div class="menu-item">
                <img src="sushi.jpg">
                <h2>Spicy Tuna Roll</h2>
                <h4>Finely minced tuna balanced with subtle heat, rolled with precision and restraint</h4>
            </div>
            <div class="menu-item">
                <img src="tempura.jpg">
                <h2>Vegetable Tempura</h2>
                <h4>Seasonal vegetables enrobed in an ethereal batter, fried to golden lightness</h4>
            </div>
            <div class="menu-item">
                <img src="teriyaki.jpg">
                <h2>chicken Teriyaki</h2>
                <h4>Char-grilled chicken lacquered with a house-crafted soy glaze, tender and aromatic</h4>
            </div>
            <div class="menu-item">
                <img src="ramen.jpeg">
                <h2>Miso Ramen</h2>
                <h4> A deep, comforting bowl: matured miso broth, spring noodles, and thoughtfully layered garnishes</h4>
            </div>
            <div class="menu-item">
                <img src="sea.jpeg">
                <h2>Edamame no Shio</h2>
                <h4>Young soybeans gently steamed and finished with natural sea salt</h4>
            </div>
            <div class="menu-item">
                <img src="tuna.jpeg">
                <h2>Maguro Sashimi</h2>
                <h4>Hand-cut bluefin tuna, presented in its purest form</h4>
            </div>
            <div class="menu-item">
                <img src="mochi.jpg">
                <h2>Matcha Mochi Ice Cream</h2>
                <h4>A graceful finale of earthy matcha ice cream wrapped in soft rice mochi</h4>
            </div>
            <div class="menu-item">
                <img src="tea.jpeg">
                <h2>Sencha Green Tea</h2>
                <h4>First-flush Japanese green tea, delicately steamed and hand-brewed for a clean, grassy finish</h4>
            </div>
            <div class="menu-item">
                <img src="soda.jpeg">
                <h2>Ramune</h2>
                <h4>Iconic Japanese marble soda, lightly effervescent with a crisp, nostalgic sweetness</h4>
            </div>
        </div>
        <div class="footer">&copy; Suruthika V(25000884)</div>
    </body>
</html>

menu.css

body
{
    background-image: url('back4.jpeg');
    background-repeat: no-repeat;
    background-size: cover;
}
.title
{
    position: relative;
    top:0;
    margin: left 5px;
    font-size: 35px;
    font-weight: bold;
    color: aquamarine;
}

.link {
  display: flex;
  position: fixed;
  top: 10;
  justify-content: space-evenly;
  width: 800px;
  height: 55px;
  font-size: 22px;
  margin-left: 550px;
}
a {
  text-decoration: none;
  color: rgb(215, 241, 249);
}
.mainmenu
{
    align-items: center;
    display: grid;
    grid-template-columns: repeat(6,1fr);
    gap: 10px;
    padding: 20px;
    background-size: 80%;
    
}

.menu-item img 
{
  width: 200px;
  height: 200px;
  bottom: 400px;
  
}
.mainmenu
{
    margin: 20px;
    text-align:center;
}
.footer
{
    position: fixed;
    bottom: 0;
    width: 100%;
    background-color: bisque;
    color: rgb(6, 6, 6);
    text-align: center;
    padding: 5px;
    left: 0;
}
h2
{
    color: aliceblue;
}
h4{
    color: aliceblue;
}

admin.html

<html>
    <head>
        <title>Administration: Tsuki Tei</title>
        <link href="admin.css" rel="stylesheet">
    </head>
    <body>
        <div class="link">
            <a href="rest.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Administration</a>
            <a href="cont.html">Contacts</a>
        </div>
        <div class="title">
            <p>ADMINISTRATION TEAM</p>
        </div>
        <div class="team">
            <div class="team-item">
                <img src="profile.JPG">
                <h2>Suruthika</h2>
                <p>CEO</p>
            </div>
            <div class="team-item">
                <img src="joong.jpeg">
                <h2>Joong Archen</h2>
                <p>Executive Head Chef</p>
            </div>
            <div class="team-item">
                <img src="bright.jpg">
                <h2>Bright Vachirawit</h2>
                <p>General Manager</p>
            </div>
            <div class="team-item">
                <img src="dunk.jpeg">
                <h2>Dunk Natachai</h2>
                <p>Sushi Master</p>
            </div>
            <div class="team-item">
                <img src="win.jpeg">
                <h2>Win Metawin</h2>
                <p>Front Office Manager</p>
            </div>
            <div class="team-item">
                <img src="flim.jpg">
                <h2>Film Thanapat</h2>
                <p>Purchase Manager</p>
            </div>
        </div>
        <div class="footer">&copy; Suruthika V(25000884)</div>
    </body>
</html>

admin.css

body {
  background-image: url("admin-bg.jpg");
  background-repeat: no-repeat;
  background-size: cover;
}
h2
{
    color:aliceblue;
}
.team-item p
{
    color: aliceblue;
}
.link {
  display: flex;
  position: fixed;
  top: 10;
  justify-content: space-evenly;
  width: 800px;
  height: 55px;
  font-size: 22px;
  margin-left: 330px;
}

a {
  text-decoration: none;
  color: rgb(215, 241, 249);
}

.title p{
  margin-top: 100px;
  font-size: 60px;
  font-weight: bolder;
  color: rgb(250, 243, 245);
  text-align: center;
}
.team{
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  margin-top: 80px;
}
.team-item{
  margin: 20px;
  text-align: center;
}

.team-item img{
  max-width: 200px;
  max-height: 200px;
  border-radius: 30px;
}
.info{
  text-decoration: none;
  color: rgb(139, 0, 0);
  text-align: center;
  margin: left 330px;;
  
  }

.footer
{
    position: fixed;
    bottom: 0;
    width: 100%;
    background-color: bisque;
    color: rgb(6, 6, 6);
    text-align: center;
    padding:5px;
    left:0;
}

cont.html

<html>
    <head>
        <title>Contact</title>
        <link href="cont.css" rel="stylesheet">
    </head>
    <body>
        <div class="link">
            <a href="rest.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Administration</a>
            <a href="cont.html">Contacts</a>
        </div>
        <div class="info">
            <h2>Contact</h2>
            <p>Visit Us At:</p>
            <p>Sakura Ln,India</p>
            <p>Phone: +91 25006 34340</p>
            <p>Email: tsukitei@gmail.com</p>
        </div>
        <div class="footer">&copy; Suruthika V(25000884)</div>
    </body>
</html>

cont.css

.link {
  display: flex;
  position: fixed;
  top: 10;
  justify-content: space-evenly;
  width: 800px;
  height: 55px;
  font-size: 22px;
  margin-left: 330px;
}

a {
  text-decoration: none;
  color: rgb(215, 241, 249);
}
body {
  background-image: url("cont-bg.jpeg");
  background-repeat: no-repeat;
  background-size: cover;
}
h2{
    color: aliceblue;
    position: relative;
    top: 250px;
    left: 1000px;
    font-size: 40;
    
}
.info p
{
    color: aliceblue;
    position: relative;
    top: 250px;
    left: 60px;
    font-size: 30;
    text-align: center;
}
.footer
{
    position: fixed;
    bottom: 0;
    width: 100%;
    background-color: bisque;
    color: rgb(6, 6, 6);
    text-align: center;
    padding:5px;
    left:0;
}

```

## OUTPUT:
![alt text](<Screenshot (38).png>)
![alt text](<Screenshot (39).png>)
![alt text](<Screenshot (40).png>)
![alt text](<Screenshot (41).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
