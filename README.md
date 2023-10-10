```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Clothing Store</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
        }

        nav {
            background-color: #444;
            text-align: center;
            padding: 10px;
        }

        nav a {
            text-decoration: none;
            color: #fff;
            margin: 0 10px;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .product {
            display: inline-block;
            margin: 10px;
            background-color: #fff;
            border: 1px solid #ddd;
            padding: 10px;
            text-align: center;
            border-radius: 5px;
        }

        .contact {
            text-align: center;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Our Clothing Store</h1>
    </header>
    <nav>
        <a href="index.html">Home</a>
        <a href="products.html">Products</a>
        <a href="contact.html">Contact</a>
    </nav>
    <div class="container">
        <!-- Home Page Content -->
        <h2>Latest Arrivals</h2>
        <div class="product">
            <img src="product1.jpg" alt="Product 1">
            <h3>Product 1</h3>
            <p>Price: $XX.XX</p>
        </div>
        <div class="product">
            <img src="product2.jpg" alt="Product 2">
            <h3>Product 2</h3>
            <p>Price: $XX.XX</p>
        </div>
        <!-- Products Page Content -->
        <!-- Add more products with similar structure -->

        <!-- Contact Page Content -->
        <div class="contact">
            <h2>Contact Us</h2>
            <p>If you have any questions, feel free to reach out.</p>
        </div>
    </div>
</body>
</html> 
