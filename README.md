# Ex.06 Restaurant Website
## Date:18-12-2025

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
        <title>Homepage - Le Boissy d'Anglas</title>
        <link href="style.css" rel="stylesheet">
    </head>
    <body class="img1">
        <nav class="id1">
        <a href="home.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </nav>
    <div class="content">
        <h1 class="head">Le Boissy d'Anglas</h1>
        <font class="quote">"A cup of coffee shared with a friend is happiness tasted and time well spent."</font><br><br>
        <font class="info">This is one of the best cafes in town, known for its cozy atmosphere and delicious brews.</font>      
        <div class="images">
            <img src="cafe1.png" alt="Cafe Interior">
            <img src="cafe2.png" alt="Coffee and Pastries">
        </div>
        <footer class="footer">
    &copy; Ranjen Munuswamy K B [25010574]
        </footer> </div>
</body>
</html>
    </body>
</html>

menu.html

<html>
    <head>
        <title>Menu - Le Boissy d'Anglas</title>
        <link href="style3.css" rel="stylesheet">
    </head>
    <body class="img1">
        <nav class="id1">
        <a href="home.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </nav>
    <div class="box"><br><br>
        <font class="head">MENU</font>
        <div class="row">
            <div class="food">
                <img src="egg.png">
                <div class="detail"><br>Organic eggs with mayonnaise<br><font class="high">$ 10.8</font></div>
            </div>
            <div class="food">
                <img src="rust.png">
                <div class="detail"><br>Rustic meat spread<br><font class="high">$ 13.2</font></div>
            </div>
            <div class="food">
                <img src="filate.png">
                <div class="detail"><br>Filet de hareng, pomme tiede<br><font class="high">$ 18.5</font></div>
            </div>
            <div class="food">
                <img src="ice.png">
                <div class="detail"><br>Ice cream sundaes<br><font class="high">$ 13</font></div>
            </div>
            <div class="food">
                <img src="board.png">
                <div class="detail"><br>Charcuterie board (assorted cured meats)<br><font class="high">$ 28</font></div>
            </div>
            <div class="food">
                <img src="avo.png">
                <div class="detail"><br>Avocat crevettes sauce cocktail<br><font class="high">$ 17.8</font></div>
            </div>
        </div>

    </div>
        <footer class="footer">
        &copy; Ranjen Munuswamy K B [25010574]
    </footer>
    </body>
</html>


admin.html

<html>
    <head>
        <title>Admin - Le Boissy d'Anglas</title>
        <link href="style1.css" rel="stylesheet">
    </head>
    <body class="img1">
        <nav class="id1">
        <a href="home.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </nav>
    <div class="box"><br><br>
        <font class="head">Administration Team</font>
        <div class="row">
            <div class="admin">
                <img src="me.jpg">
                <div class="detail"><br>Ranjen K B<br><font class="high">[CEO]</font></div>
            </div>
            <div class="admin">
                <img src="bow.jpg">
                <div class="detail"><br>Bowbow Lee<br><font class="high">[Marketing Manager]</font></div>
            </div>
            <div class="admin">
                <img src="SUL.jpg">
                <div class="detail"><br>Sultaan<br><font class="high">[Operations Manager]</font></div>
            </div>
            <div class="admin">
                <img src="god.jpg">
                <div class="detail"><br>Painter<br><font class="high">[HR Manager]</font></div>
            </div>
            <div class="admin">
                <img src="kingmaker.jpg">
                <div class="detail"><br>Nithish<br><font class="high">[Executive Chef]</font></div>
            </div>
            <div class="admin">
                <img src="disco.jpg">
                <div class="detail"><br>Jovan<br><font class="high">[Asst. Chef]</font></div>
            </div>
        </div>

    </div>
        <footer class="footer">
        &copy; Ranjen Munuswamy K B [25010574]
    </footer>
    </body>
</html>


contact.html

<html>
    <head>
        <title>Contact - Le Boissy d'Anglas</title>
        <link href="style2.css" rel="stylesheet">
    </head>
    <body class="img1">
        <nav class="id1">
        <a href="home.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </nav>
    <div class="content">
        <h1 class="head">Contact Us</h1>
        <div class="info">
            <h2>Visit us at:</h2>
            <div>Le Boissy d'Anglas</div>
            <div>45, Rue Boissy d'Anglas,</div>
            <div>Paris, France 75008</div>

            <h2>Phone:</h2>
            <div>+33 1 23 45 67 89</div>

            <h2>Email:</h2>
            <div>leboissy.paris@gmail.com</div>
        </div>
        <footer class="footer">
    &copy; Ranjen Munuswamy K B [25010574]
        </footer>
    </div>
    </body>
</html>

style.css

.img1
{
    background-image: url('img1.png');
    background-repeat: no-repeat;
    background-position: center;
}
.id1 
{
    background:linear-gradient(60deg,gold,white,gold);
    padding: 5px;
    width: 50%;
    border: solid 3px black;
    border-radius: 15px;
    display: flex;
    justify-content: space-evenly;
    flex-direction: row-reverse;
    margin: auto;
}

.head 
{
    color: whitesmoke;
    font-weight: bold;
    font-size: 60px;
    width: 40%;
    padding: 8px;
}
.quote 
{
    font-style: italic;
    font-size: 25px;
    color: yellow;
}

.info 
{
    font-size: 18px;
    font-weight: bold;
    color: yellow;
}

.images 
{
    display: flex;
    justify-content: space-evenly;
    margin-top: 40px;
}

img 
{
    width: 400px;
    height:300px;
    border-radius: 10px;
    border: 2px solid;
}
.content{
    text-align: center;
    padding:10px;
    margin:auto;
}
.footer {
    position: fixed;      
    bottom: 0;          
    left: 0;
    width: 100%;          
    text-align: center;
    padding: 3px;
    font-size: 15px;
    background-color: white;
    border-top: 2px solid black;
}

style1.css

.img1
{
    background-image: url('img1.png');
    background-repeat: no-repeat;
    background-position: center;
}
.id1 
{
    background:linear-gradient(60deg,gold,white,gold);
    padding: 5px;
    width: 50%;
    border: solid 3px black;
    border-radius: 15px;
    display: flex;
    justify-content: space-evenly;
    flex-direction: row-reverse;
    margin: auto;
}
.head 
{
    color: whitesmoke;
    font-weight: bold;
    font-size: 60px;
    width: 40%;
    padding: 8px;
}
.footer {
    position: fixed;      
    bottom: 0;          
    left: 0;
    width: 100%;          
    text-align: center;
    padding: 3px;
    font-size: 15px;
    background-color: white;
    border-top: 2px solid black;
}
.row {
    display: flex;             
    justify-content: space-evenly;                
    gap: 20px;                 
    margin-top: 40px;
}

.admin {
    text-align: center;
    background-color: rgb(255, 255, 255);
    padding: 10px;
    border-radius: 10px;
    border: 2px solid orangered;
    width: 200px;          
}
img {
    width: 180px;
    height: 250px;
    border-radius: 10px;
    border: 2px solid orangered;
}
.detail{
    font-size: 16px;
    color: rgb(0, 0, 0);
    font-weight: bold;
    padding: 10px;
}
.high{
    color: orangered;
}

style2.css

.img1
{
    background-image: url('img1.png');
    background-repeat: no-repeat;
    background-position: center;
}
.id1 
{
    background:linear-gradient(60deg,gold,white,gold);
    padding: 5px;
    width: 50%;
    border: solid 3px black;
    border-radius: 15px;
    display: flex;
    justify-content: space-evenly;
    flex-direction: row-reverse;
    margin: auto;
}
.head 
{
    color: whitesmoke;
    font-weight: bold;
    font-size: 60px;
    width: 40%;
    padding: 8px;
}
.content{

    padding:10px;
    margin:auto;
}
.footer {
    position: fixed;      
    bottom: 0;          
    left: 0;
    width: 100%;          
    text-align: center;
    padding: 3px;
    font-size: 15px;
    background-color: white;
    border-top: 2px solid black;
}
.info 
{
    font-size: 18px;
    font-weight: bold;
    color: yellow;
}

style3.css

.img1
{
    background-image: url('img1.png');
    background-repeat: no-repeat;
    background-position: center;
}
.id1 
{
    background:linear-gradient(60deg,gold,white,gold);
    padding: 5px;
    width: 50%;
    border: solid 3px black;
    border-radius: 15px;
    display: flex;
    justify-content: space-evenly;
    flex-direction: row-reverse;
    margin: auto;
}
.head 
{
    color: whitesmoke;
    font-weight: bold;
    font-size: 60px;
    width: 40%;
    padding: 8px;
}
.footer {
    position: fixed;      
    bottom: 0;          
    left: 0;
    width: 100%;          
    text-align: center;
    padding: 3px;
    font-size: 15px;
    background-color: white;
    border-top: 2px solid black;
}
.row {
    display: flex;             
    justify-content: space-evenly;                
    gap: 20px;                 
    margin-top: 40px;
}

.food {
    text-align: center;
    background-color: rgb(255, 255, 255);
    padding: 10px;
    border-radius: 10px;
    border: 2px solid orangered;
    width: 200px;          
}
img {
    width: 180px;
    height: 250px;
    border-radius: 10px;
    border: 2px solid orangered;
}
.detail{
    font-size: 16px;
    color: rgb(0, 0, 0);
    font-weight: bold;
    padding: 10px;
}
.high{
    color: orangered;
}

```

## OUTPUT:
![alt text](<Screenshot 2025-12-18 183857.png>)
![alt text](<Screenshot 2025-12-18 183907.png>)
![alt text](<Screenshot 2025-12-18 183914.png>)
![alt text](<Screenshot 2025-12-18 183921.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
