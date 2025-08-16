# hornet9549.github.io
Building for a silicone product of masking.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Masking Products</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">Masking Products</div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h1>Welcome to Masking Products</h1>
        <p>Your one-stop shop for premium masking solutions.</p>
    </section>

    <section id="products">
        <h2>Our Products</h2>
        <div class="product-list">
            <div class="product">
                <img src="mask1.jpg" alt="Mask 1">
		<img src="mask2.jpg" alt="Mask 2">
                <h3>Protective Mask</h3>
                <p>High-quality protective mask for daily use.</p>
                <button>Add to Cart</button>
            </div>
            <!-- Repeat for other products -->
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Masking Products. All rights reserved.</p>
    </footer>

    <script src="scripts.js"></script>
</body>
</html>
/* Reset some default styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body and general styles */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

/* Header styles */
header {
    background-color: #333;
    color: white;
    padding: 10px 0;
    text-align: center;
}

header nav ul {
    list-style: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
}

/* Section styles */
section {
    padding: 20px;
    margin: 20px 0;
}

#home {
    background-color: #fff;
    text-align: center;
}

#products {
    background-color: #e2e2e2;
}

.product-list {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

.product {
    background-color: white;
    border: 1px solid #ddd;
    padding: 20px;
    margin: 10px;
    width: 30%;
    text-align: center;
}

.product img {
    width: 100%;
    height: auto;
}

.product button {
    background-color: #333;
    color: white;
    border: none;
    padding: 10px;
    cursor: pointer;
}

.product button:hover {
    background-color: #555;
}

/* Contact form styles */
form {
    display: flex;
    flex-direction: column;
    max-width: 600px;
    margin: 0 auto;
}

form label {
    margin: 10px 0 5px;
}

form input, form textarea {
    padding: 10px;
    margin-bottom: 10px;
    border: 1px solid #ddd;
    border-radius: 5px;
}

form button {
    padding: 10px;
    background-color: #333;
    color: white;
    border: none;
    cursor: pointer;
}

form button:hover {
    background-color: #555;
}

/* Footer styles */
footer {
    text-align: center;
    padding: 10px;
    background-color: #333;
    color: white;
}
