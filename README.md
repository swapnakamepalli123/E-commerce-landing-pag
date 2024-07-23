<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E-Commerce Landing Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .header {
            background-color: #333;
            color: rgba(245, 248, 250, 0.918);
            padding: 10px 0;
            text-align: center;
        }
        .header a {
            color: rgba(225, 230, 233, 0.87);
            text-decoration: none;
            padding: 0 15px;
        }
        .hero {
            background: url('hero-image.jpg') no-repeat center center/cover;
            height: 300px;
            color: white;
            text-align: center;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        .hero h1 {
            font-size: 3em;
        }
        .nav {
            display: flex;
            justify-content: center;
            background-color: #f4f4f4;
            padding: 10px 0;
        }
        .nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #333;
        }
        .products {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            padding: 20px;
        }
        .product {
            border: 1px solid #ddd;
            padding: 10px;
            margin: 10px;
            width: 200px;
            text-align: center;
        }
        .product img {
            max-width: 100%;
            height: auto;
        }
        .cta-button {
            display: inline-block;
            padding: 10px 20px;
            color: white;
            background-color: #007bff;
            text-decoration: none;
            border-radius: 5px;
        }
        .cta-button:hover {
            background-color: #0056b3;
        }
        .footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
        .footer a {
            color: white;
            text-decoration: none;
            margin: 0 10px;
        }
    </style>
</head>
<body>

    <div class="header">
        <a href="#">Home</a>
        <a href="#">Shop</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
        <a href="#" style="float: right;">Sign Up / Login</a>
    </div>

    <div class="hero">
        <h1>Welcome to Our Store</h1>
    </div>

    <div class="nav">
        <a href="#">Men</a>
        <a href="#">Women</a>
        <a href="#">Electronics</a>
        <a href="#">Accessories</a>
    </div>

    <div class="products">
        <div class="product">
            <img src="product1.jpg" alt="Product 1">
            <h3>Product 1</h3>
            <p>$29.99</p>
            <a href="#" class="cta-button">Buy Now</a>
        </div>
        <div class="product">
            <img src="product2.jpg" alt="Product 2">
            <h3>Product 2</h3>
            <p>$49.99</p>
            <a href="#" class="cta-button">Buy Now</a>
        </div>
        <!-- Add more products as needed -->
    </div>

    <div class="footer">
        <a href="#">Privacy Policy</a>
        <a href="#">Terms of Service</a>
        <a href="#">Contact Us</a>
        <p>&copy; 2024 Your Company</p>
    </div>

</body>
</html>
