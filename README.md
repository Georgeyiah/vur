<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blue Sky Gardening</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #e0f7fa;
        }
        header {
            background-color: #00796b;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            margin: 10px 0;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }
        section {
            padding: 20px;
        }
        .portfolio img {
            width: 100%;
            max-width: 400px;
            margin: 10px;
            border-radius: 8px;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #004d40;
            color: white;
        }
        @media (max-width: 600px) {
            nav a {
                display: block;
                margin: 5px 0;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Blue Sky Gardening</h1>
    <nav>
        <a href="#services">Services</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section id="services">
    <h2>Our Services</h2>
    <p>At Blue Sky Gardening, we specialize in creating beautiful outdoor spaces while prioritizing eco-friendly practices. Our services include:</p>
    <ul>
        <li>Custom Garden Design</li>
        <li>Organic Lawn Care</li>
        <li>Patio and Deck Installation</li>
        <li>Tree and Shrub Maintenance</li>
        <li>Water Feature Creation</li>
    </ul>
</section>

<section id="portfolio">
    <h2>Our Portfolio</h2>
    <div class="portfolio">
        <img src="https://i.imgur.com/oRemHHy.jpeg" alt="Garden Design 1">
        <img src="https://i.imgur.com/Z9Ycumq.jpeg" alt="Garden Design 2">
        <img src="https://i.imgur.com/xpfbHt7.jpeg">
    </div>
</section>

<section id="about">
    <h2>About Us</h2>
    <p>Blue Sky Gardening is dedicated to transforming your outdoor spaces into lush, serene retreats. Our experienced team combines creativity with sustainability to enhance your gardens.</p>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <form>
        <label for="name">Name:</label><br>
        <input type="text" id="name" name="name"><br>
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email"><br>
        <label for="message">Message:</label><br>
        <textarea id="message" name="message"></textarea><br>
        <input type="submit" value="Submit">
    </form>
</section>

<footer>
    <p>&copy; 2024 Blue Sky Gardening. All rights reserved.</p>
</footer>

</body>
</html>
