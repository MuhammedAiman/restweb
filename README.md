# Ex.07 Restaurant Website
## Date:18/12/2024

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
rest.html
```
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Delicious Restaurant</title>
    <link rel="stylesheet" href="rest.css">
</head>
<body bgcolor="beige">
    <header>
        <h1>MACOFA</h1>
        <nav>
            <ul>
                <li><a href="#about">About Us</a></li>
                <li><a href="#menu">Menu</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About Us</h2>
        <p> MACOFA is a decadent dessert haven where sweet dreams come true. 
            Nestled in the heart of the city, this charming eatery invites guests to indulge in an array of mouthwatering confections, 
            from elegantly crafted pastries to creamy gelatos and rich, velvety cakes. 
            Each dessert is meticulously prepared using the finest ingredients, offering a perfect blend of creativity and tradition. 
            With its cozy, modern ambiance and a menu that evolves with the seasons,
            MACOFA creates a delightful escape for those seeking an unforgettable treat. 
            Whether you're savoring a classic or exploring a daring new flavor,
            MACOFA is the ultimate destination for anyone with a passion for dessert.</p>
    </section>

    <section id="menu">
        <h2>Melting Desserts</h2>
        <div class="menu-container">
            <div class="menu-left">
                <ul>
                    <li>
                        <img src="kunafa.jpg" width="300">
                        <b>Kunafa - ₹500</b>
                    </li>
                    <li>
                        <img src="brownie.jpg" width="300" height="310">
                        <b>Melting Brownie - ₹150</b>
                    </li>
                    <li>
                        <img src="waffle.jpg" width="300">
                        <b>Waffle - ₹250</b>
                        </li> 
                    </li>
                </ul>
            </div>
            <div class="menu-right">
                <ul>
                    <li>
                        <img src="mousse.jpg"  width="400" height="240">
                        <b>Chocolate Mousse - ₹220</b>
                    </li>
                    <li>
                        <img src="cheesecake.jpg"  width="400" height="300">
                       <b> Red Velvet Cheesecake - ₹150</b>
                    </li>
                    <li>
                        <img src="baklava.jpg"  width="400" height="300">
                         <b> Persian Flavoured Baklava - ₹145</b>
                    </li>
                </ul>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: Macofadesserts@gmail.com</p>
        <p>Phone: +91 8870167403</p>
        <p>Address: 12345, chennai </p>
    </section>

    <footer>
        <p>&copy; Macofa. All rights reserved.</p>
    </footer>
</body>
</html>

```
rest.css
```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
    font-size: large;
    background-image: url('pur.jpg');
    background-size: cover; 
    background-position: center; 
    background-repeat: no-repeat; 
    padding: 20px;
    color: rgb(0, 0, 0);
}

header {
    background: burlywood; 
    color: rgb(0, 0, 0);
    padding: 10px 0;
    text-align: center;
    font-style: oblique;
    border-radius: 20px;
}



nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: rgb(15, 14, 14);
    text-decoration: none;
    font-weight: bold;
}

section {
    padding: 20px;
    margin: 10px;
}

h2 {
    color: #571111; 
}

footer {
    text-align: center;
    padding: 10px 0;
    background:brown;
    color: rgb(0, 0, 0);
    position: relative;
    bottom: 0;
    width: 100%;
}
.menu-container {
    display: flex;
    justify-content: space-between;
}

.menu-left, .menu-right {
    width: 48%; 
}

.menu-left ul, .menu-right ul {
    list-style: none;
    padding: 0;
    font-size: large;
}

.menu-left li, .menu-right li {
    display: flex;
    align-items: center;
    margin-bottom: 20px;
}

.menu-left li img, .menu-right li img {
    margin-right: 10px;
    border-radius: 45px;
}

```

## OUTPUT:


![alt text](<Screenshot (57).png>)

![alt text](<Screenshot (58).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
