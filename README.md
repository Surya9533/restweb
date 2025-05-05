# Ex.07 Restaurant Website
## Date: 05.05.2025

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
home.html
<html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>restweb</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-image: url("bg.web.jpg");
            background-size: cover;
            background-attachment: fixed;
            background-position: center;
            color: #333;
        }
        header {
            background-color: rgba(108, 142, 191, 0.8); /* Mild blue with transparency */
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: rgba(51, 51, 51, 0.8);
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: rgba(108, 142, 191, 0.8);
        }
        .content {
            padding: 20px;
            background-color: rgba(255, 255, 255, 0.8); /* White with transparency for readability */
            margin: 20px auto;
            border-radius: 10px;
            max-width: 1200px;
        }
        .menu-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
        }
        .menu-item {
            background-color: white;
            padding: 10px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .admin-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
        }
        .admin-item {
            text-align: center;
        }
        footer {
            background-color: rgba(51, 51, 51, 0.8);
            color: white;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>DEEN BIRIYANI</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#menu">Menu</a>
        <a href="#administration">Administration</a>
        <a href="#contact">Contact Us</a>
    </nav>
    <div id="home" class="content">
        <h2>Welcome to Deen Biriyani</h2>
        <p><strong>Biriyani</strong> is a dish that captures the essence of Indian cuisine. It's a flavorful medley of aromatic rice, tender meat, and fragrant spices, creating a dish that’s loved around the world. Each spoonful is a journey through layers of flavor, tradition, and culture.</p>
        <p><strong>Deen Biriyani</strong> has been delighting customers with authentic and rich flavors since its inception in 2000. Our biriyani is made with carefully selected ingredients and cooked to perfection using traditional methods. Whether it's the iconic Mutton Biriyani or the spicy Chicken Tandoori, every dish is crafted to ensure an unforgettable dining experience.</p>
        <p>At Deen Biriyani, we aim to serve not just food but memories. With over 20 years of excellence, we have become a household name for biriyani lovers. Come, join us for an experience filled with delicious food, warm hospitality, and the legacy of biriyani.</p>
    </div>
    <div id="menu" class="content">
        <h2>Menu</h2>
        <div class="menu-grid">
            <div class="menu-item">Mutton Biriyani</div>
            <div class="menu-item">Chicken Biriyani</div>
            <div class="menu-item">Beef Biriyani</div>
            <div class="menu-item">Ambur Dum Biriyani</div>
            <div class="menu-item">Dindigul Biriyani</div>
            <div class="menu-item">Hyderabad Biriyani</div>
            <div class="menu-item">Al-Fam Chicken</div>
            <div class="menu-item">Chicken Tandoori</div>
            <div class="menu-item">Grilled Chicken</div>
            <div class="menu-item">Fish Fry</div>
            <div class="menu-item">Prawn Biriyani</div>
            <div class="menu-item">Egg Biriyani</div>
            <div class="menu-item">Paneer Biriyani</div>
            <div class="menu-item">Bread Halwa</div>
            <div class="menu-item">Gulab Jamun</div>
            <div class="menu-item">Carrot Halwa</div>
            <div class="menu-item">Falooda</div>
            <div class="menu-item">Lassi</div>
        </div>
    </div>
    <div id="administration" class="content">
        <h2>Administration</h2>
        <div class="admin-grid">
            <div class="admin-item">
                <img src="image1.jpg" alt="Admin 1" style="width:100px;height:100px;border-radius:50%;">
                <p>Mushafina Riyasudeen</p>
                <p>Chief Executive Officer</p>
            </div>
            <div class="admin-item">
                <img src="imag2.jpg" alt="Admin 2" style="width:100px;height:100px;border-radius:50%;">
                <p>Prathosh Ramachandran</p>
                <p>Chief Operating Officer</p>
            </div>
            <div class="admin-item">
                <img src="image3.jpg" alt="Admin 3" style="width:100px;height:100px;border-radius:50%;">
                <p>Nakshathira Rajesh</p>
                <p>Chief Financial Officer</p>
            </div>
        </div>
    </div>
    <div id="contact" class="content">
        <h2>Contact Us</h2>
        <p>Address: Abirami Colony,Anna Nagar,Chennai-60056,TamilNadu</p>
        <p>Phone: 9879656789</p>
        <p>Email: deenbiriyani@gmail.com</p>
    </div>
    <footer>
        <p>&copy; DEVELOPED BY MUSHAFINA (24008061)</p>
    </footer>
</body>
</html>


## OUTPUT:
![image](https://github.com/user-attachments/assets/e63d5cc6-df44-46bb-b988-7abbe19409d4)



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
