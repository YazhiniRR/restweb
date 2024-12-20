# Ex.07 Restaurant Website
## Date:13.12.2024

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
index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HOTEL GRAND</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="home-header">
        <div class="banner">
            <h>HOTEL GRAND</h>
            <p>Delightful Food, Memorable Experiences</p>
        </div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="welcome">
            <h2>HOTEL GRAND</h2>
            <p>A new culinary journey begins today-be a part of it.</p>
        </section>
        <section class="featured">
            <h2>OUR SPECIALITIES</h2>
            <div class="featured-items">
                <div class="featured-item">
                    <img src="food 1.jpg" alt="GRILLED SALMON">
                    <p>GRILLED SALMON</p>
                </div>
                <div class="featured-item">
                    <img src="food 2.jpg" alt="CHICKEN BIRIYANI">
                    <p>CHICKEN BIRIYANI</p>
                </div>
                <div class="featured-item">
                    <img src="food 6.png" alt="FULL NON VEG MEALS">
                    <p>FULL NON VEG MEALS</p>
                </div>
            </div>
        </section>
    </main>
    <footer>
        <p>Designed by YAZHINI.R.R | hotel grand © 2024</p>
    </footer>
</body>
</html>
```
menu.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - HOTEL GRAND</title>
    <link rel="stylesheet" href="styless.css">
</head>
<body>
    <header>
        <div class="banner">
            <h1>hotel grand</h1>
        </div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h2>Our Menu</h2>
        <div class="menu-card">
            <div class="menu-item">
                <img src="Mutton-Biryani-.jpg" alt="Mutton biriyani">
                <div class="menu-details">
                    <h3>Mutton biriyani</h3>
                    <p>fresh and juicy mutton with bhasmathi rice</p>
                    <p class="price">Rs 399</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="food 3.jpg" alt="freshly fish fried ">
                <div class="menu-details">
                    <h3>freshly fish fried</h3>
                    <p>A classic south spicy fry.</p>
                    <p class="price">Rs 199</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="food 5.jpg" alt="full veg meals">
                <div class="menu-details">
                    <h3>full veg meals</h3>
                    <p>plant based and blooming.</p>
                    <p class="price">Rs 249</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="food 4.jpg" alt="Tandoori Chicken">
                <div class="menu-details">
                    <h3>Tandoori Chicken</h3>
                    <p>Marinated chicken cooked in a traditional clay oven.</p>
                    <p class="price">Rs 399</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="desert 2.jpg" alt="Choclate brownie">
                <div class="menu-details">
                    <h3>Chocolate brownie</h3>
                    <p>Rich chocolate cake with a molten center served with ice cream.</p>
                    <p class="price">Rs 199</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="desert 1.jpg" alt="donut">
                <div class="menu-details">
                    <h3>donut</h3>
                    <p>A delicious melted donut.</p>
                    <p class="price">Rs 299</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="desert 4.jpg" alt="pine with blue berry">
                <div class="menu-details">
                    <h3>pine with blue berry</h3>
                    <p>Cake love at first sight.</p>
                    <p class="price">Rs 249</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="desert 5.jpg" alt="Creamy cake">
                <div class="menu-details">
                    <h3>Creamy cake</h3>
                    <p>desert crepe filled with cream.</p>
                    <p class="price">Rs 159</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="desert 3.jpg" alt="ice creams">
                <div class="menu-details">
                    <h3>ice creamsk</h3>
                    <p>A sweet ending after a meal.</p>
                    <p class="price">Rs 149</p>
                </div>
            </div>
    </main>
    <footer>
        <p>Designed YAZHINI.R.R | HOTEL GRAND © 2024</p>
    </footer>
</body>
</html>
```
administration.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - hotel grand</title>
    <link rel="stylesheet" href="sty.css">
</head>
<body>
    <header>
        <div class="banner">
            <h1>hotel grand</h1>
        </div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <div class="admin-container">
            <div class="admin-header">
                <h2>Meet Our Team</h2>
                <p>Our exceptional team is dedicated to delivering the finest dining experience with expertise and passion.</p>
            </div>
            <div class="admin-grid">
                <!-- Team Member 1 -->
                <div class="admin-card">
                    <img src="chef 1.jpg" alt="Piquant">
                    <h3>Piquant</h3>
                    <p>General Manager</p>
                    <p class="experience">Piquant has over 15 years of experience in hospitality management, ensuring excellence in every detail of our service.</p>
                </div>
                <!-- Team Member 2 -->
                <div class="admin-card">
                    <img src="rangaraj.jpg" alt="Rangaraj">
                    <h3>Rangaraj</h3>
                    <p>Head Chef</p>
                    <p class="experience">Rangaraj with innovative mind and creative dishes.</p>
                </div>
                <!-- Team Member 3 -->
                <div class="admin-card">
                    <img src="chef 5.jpg" alt="Dhamu">
                    <h3>Dhamu</h3>
                    <p>Pastry Chef</p>
                    <p class="experience">Dhamu with more than 50 years of experience.</p>
                </div>
                <!-- Team Member 4 -->
                <div class="admin-card">
                    <img src="chef 2.png" alt="Sarah George">
                    <h3>Sarah George</h3>
                    <p>Event Coordinator</p>
                    <p class="experience">Sarah has organized hundreds of events,ensuring every celebration as perfect in hotel grand.</p>
                </div>
            </div>
        </div>
    </main>
    <footer>
        <p>Designed by YAZHINI.R.R | HOTEL GRAND © 2024</p>
    </footer>
</body>
</html>
```
contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - HOTEL GRAND</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="banner">
            <h1>HOTEL GRAND</h1>
        </div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h2>Contact Us</h2>
        <p>Address: diamond street,kk nagar,chennai</p>
        <p>Phone: (123) 987-345</p>
        <p>Email: contact@hotelgrand.com</p>
    </main>
    <footer>
        <p>Designed by YAZHINI.R.R | HOTEL GRAND © 2024</p>
    </footer>
</body>
</html>
```
sty.css
```
/* Administration Page */
.admin-container {
    max-width: 1200px;
    margin: 20px auto;
    padding: 20px;
}

.admin-header {
    text-align: center;
    margin-bottom: 30px;
}

.admin-header h2 {
    font-size: 2em;
    color: #333;
}

.admin-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); /* Responsive columns */
    gap: 20px;
    padding: 10px;
}

.admin-card {
    text-align: center;
    background: #f9f9f9;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    padding: 15px;
    transition: transform 0.2s;
}

.admin-card:hover {
    transform: scale(1.05); /* Subtle zoom on hover */
}

.admin-card img {
    width: 100%;
    height: 200px;
    object-fit: cover; /* Ensures consistent image size */
    border-radius: 8px;
    margin-bottom: 10px;
}

.admin-card h3 {
    font-size: 1.4em;
    color: #333;
    margin-bottom: 5px;
}

.admin-card p {
    font-size: 1em;
    color: #666;
    margin: 5px 0;
}

.admin-card .experience {
    font-size: 0.9em;
    color: #555;
    margin-top: 10px;
    line-height: 1.4;
}

/* Footer */
footer {
    text-align: center;
    padding: 15px;
    background: #333;
    color: white;
    margin-top: 20px;
}
```
styles.css
```
/* Background Image for Home Page */
.home-header {
    background: url('variety-of-indian-food.jpg') no-repeat center center/cover;
    height: 100vh; /* Full screen height */
    color: white;
    display: flex;
    flex-direction: column;
    justify-content: center;
    text-align: center;
}

.home-header .banner h1 {
    font-size: 3em;
    margin-bottom: 10px;
    text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
}

.home-header .banner p {
    font-size: 1.2em;
    text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
}

/* Navigation Styles */
nav ul {
    display: flex;
    justify-content: center;
    gap: 20px;
    padding: 10px;
    background: rgba(0, 0, 0, 0.5);
    list-style: none;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
    font-size: 1.1em;
}

nav ul li a:hover {
    text-decoration: underline;
}

/* Featured Section */
.featured {
    margin: 20px 0;
    text-align: center;
    color: #333;
}

.featured-items {
    display: flex;
    justify-content: space-around;
    gap: 20px;
}

.featured-item img {
    width: 200px;
    height: 150px;
    object-fit: cover;
    border-radius: 8px;
}

.featured-item p {
    text-align: center;
    margin-top: 5px;
    font-weight: bold;
}
/* Footer */
footer
 {
    text-align: center;
    padding: 15px;
    background: #333;
    color: white;
    margin-top: 20px;
}
```
styless.css
```
/* Menu Card Layout */
.menu-card {
    max-width: 1000px;
    margin: 20px auto;
    padding: 20px;
}

.menu-item {
    display: flex;
    align-items: center;
    gap: 20px;
    margin-bottom: 20px;
    padding: 10px;
    background: #f9f9f9;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.menu-item img {
    width: 150px;
    height: 150px;
    object-fit: cover;
    border-radius: 8px;
}

.menu-details {
    flex: 1;
}

.menu-details h3 {
    font-size: 1.5em;
    color: #333;
}

.menu-details p {
    color: #666;
    margin-top: 5px;
}

.menu-details .price {
    color: #333;
    font-size: 1.2em;
    font-weight: bold;
    margin-top: 10px;
}
```

    

## OUTPUT:
![alt text](<pic 1.png>) 
![alt text](<pic 2.png>)
![alt text](<pic 3.png>) 
![alt text](<pic 4.png>) 
![alt text](<pic 5.png>) 
![alt text](<pic 6-1.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
