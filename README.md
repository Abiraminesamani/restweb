# Ex.07 Restaurant Website
## Date:04.11.2024

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
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Delicious Bites</title>
    <style>
        body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
    background-color: aquamarine;
}

header {
    background-color: #ff6f61;
    color: aqua;
    padding: 1rem 0;
    text-align: center;
}

header .banner {
    background-image: url('banner.jpg');
    background-size: cover;
    background-position: center;
    padding: 2rem;
    color: pink;
}

nav ul {
    list-style: none;
    padding: 0;
    display: flex;
    justify-content: center;
    background-color: blue;
    margin: 0;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: yellow;
    text-decoration: none;
    font-weight: bold;
}

main {
    padding: 20px;
}

#menu .menu-items {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
}

#menu .item {
    background-color: #fff3e0;
    padding: 10px;
    border: 1px solid #e0e0e0;
    text-align: center;
    border-radius: 8px;
    background-color: blueviolet;
}

#administration .team {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
    background-color:skyblue;
}

#administration .person {
    text-align: center;
    margin: 10px;

}

#administration .person img {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    object-fit: cover;
}

footer {
    background-color: #e84a27;
    color: palegreen;
    text-align: center;
    padding: 10px 0;
    margin-top: 20px;
}

    </style>
</head>
<body>
    <header>
        <div class="banner">
            <h1>Welcome to Delicious Bites</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#menu">Menu</a></li>
                <li><a href="#administration">Administration</a></li>
                <li><a href="#contact">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <!-- Home Section -->
        <section id="home">
            <h2>About Us</h2>
            <p>Welcome to Delicious Bites! We offer a delightful range of food that will tantalize your taste buds.</p>
        </section>

        <!-- Menu Section -->
        <section id="menu">
            <h2>Our Menu</h2>
            <div class="menu-items">
                <div class="item">Idly - Rs.20</div>
                <div class="item">Dosa - Rs.50</div>
                <div class="item">Poori - Rs.45</div>
                <div class="item">Salad - Rs.90</div>
                <div class="item">Vaada - Rs.10</div>
                <div class="item">Mini Tiffin - Rs.120</div>
                <div class="item">Tea - Rs.20</div>
                <div class="item">Coffee - Rs.25</div>
                <div class="item">Ice Cream - Rs.80</div>
                <div class="item">Milkshake - Rs.150</div>
                <div class="item">Biriyani- Rs.350</div>
                <div class="item">Mini Meals - Rs170</div>
            </div>
        </section>


        <section id="administration">
            <h2>Meet Our Team</h2>
            <div class="team">
                <div class="person">
                    <img src="photo.jpg" alt="Manager">
                    <p>Abi - Manager</p>
                </div>
                <div class="person">
                    <img src="che.png" alt="Chef">
                    <p>Kamali - Head Chef</p>
                </div>
                <div class="person">
                    <img src="ache.png" alt="Assistant">
                    <p>John - Assistant Chef</p>
                </div>
                <div class="person">
                    <img src="ser.png" alt="Server">
                    <p>Raj - Server</p>
                </div>
                <div class="person">
                    <img src="bar.png" alt="Bartender">
                    <p>Paul - Bartender</p>
                </div>
                <div class="person">
                    <img src="cle.png" alt="Cleaner">
                    <p>Anne - Cleaner</p>
                </div>
            </div>
        </section>


        <!-- Contact Section -->
        <section id="contact">
            <h2>Contact Us</h2>
            <p>Address: 123 Foodie Lane, Guindy-99</p>
            <p>Phone: +123467890</p>
            <p>Email: contact@deliciousbites.com</p>
        </section>
    </main>

    <footer>
        <p>Designed by [N. ABIRAMI]</p>
    </footer>
</body>
</html>

```

## OUTPUT!
![alt text](s1.png)
![alt text](s2.png)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
