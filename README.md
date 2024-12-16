# Ex.07 Restaurant Website
## Date:12/12/24

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
administration.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - Multi-cusine restaurant</title>
    <link rel="stylesheet" href="sty.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="administration">
        <h1>Meet Our Team</h1>
        <div class="team-grid">
            <div class="team-member">
                <img src="chef.1.jpeg" alt="Admin 1">
                <h2>lavanya</h2>
                <p>General Manager</p>
            </div>
            <div class="team-member">
                <img src="chef 2.jpeg" alt="Admin 2">
                <h2>hema</h2>
                <p>Head Chef</p>
            </div>
            <div class="team-member">
                <img src="chef 3.jpeg" alt="Admin 3">
                <h2>radha</h2>
                <p>Operations Manager</p>
            </div>
            <div class="team-member">
                <img src="chef.4.jpeg" alt="Admin 4">
                <h2>mohan</h2>
                <p>Marketing Manager</p>
            </div>
            <div class="team-member">
                <img src="chef.5.jpeg" alt="Admin 5">
                <h2>anu</h2>
                <p>HR Manager</p>
            </div>
            <div class="team-member">
                <img src="chef.6.jpeg" alt="Admin 6">
                <h2>raji</h2>
                <p>Head Waiter</p>
            </div>
        </div>
    </section>

    <footer>
        <p>Designed by [Hema]</p>
    </footer>
</body>
</html>
index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Family Diner</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="banner">
        <div class="banner-content">
            <h1>Welcome to Our Restaurant</h1>
            <p>We serve the finest dishes made with fresh ingredients. Come visit us!</p>
        </div>
    </section>

    <footer>
        <p>Designed by [Hema]</p>
    </footer>
</body>
</html>
menu.html
!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - multi-cusine restaurant</title>
    <link rel="stylesheet" href="styless.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="menu">
        <h1>Our Menu</h1>
        <div class="menu-grid">
            <div class="menu-item">
                <img src="menu.1.jpeg" alt="chicken biryani">
                <h2>chicken biryani</h2>
                <p>south asian mixed rice dish made with marinated chicken,basmati rice,and a blen of aromatic spices</p>
                <p class="price">rs.250</p>
            </div>
            <div class="menu-item">
            <img src="menu.2.jpeg" alt="Panipuri">
                <h2>panipuri</h2>
                <p>A flavorful explosion of crispy puris,tangy tamarid water,and spicy chutneys</p>
                <p class="price">rs.50</p>
            </div>
            <div class="menu-item">
                <img src="menu.3.jpeg" alt="parota with chicken">
                <h2>parota with chicken</h2>
                <p>soft,flaky parotas served with tender chicken cooked in a rich,soicy gravy</p>
                <p class="price">rs.100</p>
            </div>
            <div class="menu-item">
                <img src="menu.4.jpeg" alt="pasta">
                <h2>pasta</h2>
                <p>class="rich and creamy fettucine padta tossed in a parmesan sauce</p> 
                <p class="price">rs.150</p>
            </div>
            <div class="menu-item">
                <img src="menu.5.jpeg" alt="chicken nuggets">
                <h2>chicken nuggets</h2>
                <p>Chicken nuggets are a popular fast food item that are made from small pieces of deboned chicken that are battered </p>
                <p class="price">rs.200</p>
            </div>
            <div class="menu-item">
                <img src="menu.6.jpeg" alt="pulihora">
                <h2>pulihora</h2>
                <p>A tangy and savory rice dish, infused with the flavors of tamarind, turmeric, and coriander.</p>
                <p class="price">rs.200</p>
            </div>
        <div class="menu-item">
            <img src="menu.7.jpeg" alt="masala dosa">
            <h2>masala dosa</h2>
            <p> A flavorful and crispy dosa filled with aromatic spiced potatoes, served with coconut chutney and sambar."</p>
            <p class="price">rs.70</p>
        </div>
        <div class="menu-item">
            <img src="menu.8.jpeg" alt="pasta">
            <h2> mamos</h2>
            <p>A selection of pasta, served with a variety of chutneys and sauces."</p>
            <p class="price">rs.120</p>
        </div>
        <div class="menu-item">
            <img src="menu.9.jpeg" alt="mamos">
            <h2>mamos</h2>
            <p>A selection of steamed and pan-fried momos, served with a variety of chutneys and sauces."</p>
            <p class="price">rs.170</p>
        </div>
        <div class="menu-item">
            <img src="menu.10.jpeg" alt="french fries">
            <h2>french fries</h2>
            <p>crispy golden fries", "thick-cut fries", "shoestring fries", "hand-cut fries", or "classic fries" depending on the style served. </p>
            <p class="price">rs.100</p>
        </div>
        <div class="menu-item">
            <img src="menu.11.jpeg" alt="gobi munchurian">
            <h2>gobi munchurian</h2>
            <p>a dish made with fried cauliflower in a spicy, tangy sauce, commonly found in Indian-Chinese cuisine.</p>
            <p class="price">rs.60</p>
        </div>
        <div class="menu-item">
            <img src="menu 12.jpeg" alt="nun better">
            <h2>nun better</h2>
            <p>aan" (a type of Indian flatbread) and "butter chicken" (a creamy, tomato-based chicken curry)</p>
            <p class="price">rs.300</p>
        </div>





    </section>

    <footer>
        <p>Designed by [Hema]</p>
    </footer>
</body>
</html>
contact.html
!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - multi-cusine restaurant</title>
    <link rel="stylesheet" href="st.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="contact">
        <h1>Contact Us</h1>
        <p>Address: 123 Restaurant St., City, Country</p>
        <p>Phone: +123 456 7890</p>
        <p>Email: contact@restaurant.com</p>
    </section>

    <footer>
        <p>Designed by [Hema]</p>
    </footer>
</body>
</html>

css

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: white;
    padding: 10px 0;
    text-align: center;
}

header nav ul {
    list-style-type: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
}

section {
    padding: 20px;
    margin: 20px;
}

section h1 {
    font-size: 2em;
    color: #333;
}

section .menu ul {
    list-style-type: none;
}

section .menu li {
    margin: 15px 0;
}

section .team-member {
    display: inline-block;
    margin: 10px;
    text-align: center;
}

section .team-member img {
    width: 100px;
    height: 100px;
    border-radius: 50%;
}

css

* General styles for the body */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4; /* fallback color */
}

/* Header styles */
header {
    background-color: rgba(0, 0, 0, 0.6); /* Semi-transparent black background */
    color: white;
    padding: 10px 0;
    text-align: center;
}

header nav ul {
    list-style-type: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

/* Administration Section */
.administration {
    padding: 40px;
    text-align: center;
    background-color: #fff;
}

.administration h1 {
    font-size: 2.5em;
    margin-bottom: 40px;
    color: #333;
}

/* Grid Layout for Team Members */
.team-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
    gap: 30px;
    justify-items: center;
    padding: 20px;
}

/* Individual Team Member Card */
.team-member {
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
    padding: 20px;
    width: 100%;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.team-member:hover {
    transform: scale(1.05); /* Slight zoom effect */
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
}

/* Team Member Image Styling */
.team-member img {
    width: 100%;
    height: 200px; /* Fixed height for uniformity */
    object-fit: cover;
    border-radius: 50%;
    margin-bottom: 15px;
}

/* Team Member Name */
.team-member h2 {
    font-size: 1.5em;
    margin: 10px 0;
    color: #333;
}

/* Team Member Designation */
.team-member p {
    font-size: 1em;
    color: #777;
    margin-top: 5px;
}

/* Footer styles */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
}

css

/*General styles for the body */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4; /* fallback color */
}

/* Header styles */
header {
    background-color: rgba(0, 0, 0, 0.6); /* Semi-transparent black background */
    color: white;
    padding: 10px 0;
    text-align: center;
}

header nav ul {
    list-style-type: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

/* Banner section with background image */
.banner {
    background-image: url('bg.1.jpeg'); /* Change this to the path of your image */
    background-size: cover;
    background-position: center;
    height: 400px; /* Adjust the height of the banner */
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    text-align: center;
    position: relative;
}

.banner-content {
    z-index: 1; /* Makes sure the text is above the background */
}

.banner h1 {
    font-size: 3em;
    margin: 0;
}

.banner p {
    font-size: 1.2em;
}

/* Footer styles */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
}

/* Other sections styling */
section {
    padding: 20px;
    margin: 20px;
}

section h1 {
    font-size: 2em;
    color: #333;
}

section .menu ul {
    list-style-type: none;
}

section .menu li {
    margin: 15px 0;
}

section .team-member {
    display: inline-block;
    margin: 10px;
    text-align: center;
}

section .team-member img {
    width: 100px;
    height: 100px;
    border-radius: 50%;
}

css

/* General styles for the body */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4; /* fallback color */
}

/* Header styles */
header {
    background-color: rgba(0, 0, 0, 0.6); /* Semi-transparent black background */
    color: white;
    padding: 10px 0;
    text-align: center;
}

header nav ul {
    list-style-type: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

/* Menu Section */
.menu {
    padding: 20px;
    text-align: center;
}

.menu h1 {
    font-size: 2.5em;
    margin-bottom: 20px;
    color: #333;
}

/* Grid Layout for Menu Items */
.menu-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
    gap: 20px;
    justify-items: center;
    padding: 20px;
}

/* Individual Menu Item Styles */
.menu-item {
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
    padding: 20px;
    width: 100%;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.menu-item:hover {
    transform: scale(1.05); /* Slight zoom effect */
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
}

/* Menu Item Image */
.menu-item img {
    width: 100%;
    height: auto;
    border-radius: 10px;
}

/* Menu Item Name */
.menu-item h2 {
    font-size: 1.5em;
    margin: 15px 0;
    color: #333;
}

/* Menu Item Description */
.menu-item p {
    color: #777;
    font-size: 1em;
    margin-bottom: 10px;
}

/* Price Styling */
.menu-item .price {
    font-size: 1.2em;
    font-weight: bold;
    color: #e60000;
}

/* Footer styles */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
}





```


## OUTPUT:
![alt text](<Screenshot (22).png>)

![alt text](<Screenshot (39).png>)

![alt text](<Screenshot (40).png>)
![alt text](<Screenshot (41).png>)

![alt text](<Screenshot (42).png>)
![alt text](<Screenshot (43).png>)
![alt text](<Screenshot (44).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.