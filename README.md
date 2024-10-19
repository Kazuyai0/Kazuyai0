
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Elegant Sales Website</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-color: #2c3e50;
            color: white;
            padding: 20px 0;
            text-align: center;
            font-size: 24px;
        }
        nav {
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }
        .hero {
            background: url('your-image.jpg') no-repeat center center/cover;
            height: 60vh;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-align: center;
        }
        .hero h1 {
            font-size: 48px;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 40px 20px;
        }
        .product {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .product-item {
            background-color: white;
            margin: 20px;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            width: 300px;
            text-align: center;
        }
        .product-item img {
            width: 100%;
            height: auto;
            border-bottom: 1px solid #ccc;
        }
        .product-item h2 {
            font-size: 22px;
            margin: 10px 0;
        }
        .product-item p {
            font-size: 18px;
            margin: 10px 0;
        }
        .product-item button {
            background-color: #2980b9;
            color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            border-radius: 5px;
        }
        .product-item button:hover {
            background-color: #3498db;
        }
        footer {
            text-align: center;
            padding: 20px 0;
            background-color: #2c3e50;
            color: white;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Elegant Sales Website</h1>
    </header>

    <!-- Navigation -->
    <nav>
        <a href="#">Home</a>
        <a href="#">Products</a>
        <a href="#">Contact</a>
    </nav>

    <!-- Hero Section -->
    <section class="hero">
        <h1>Discover Our Latest Products</h1>
    </section>

    <!-- Product Section -->
    <div class="container">
        <h2>Featured Products</h2>
        <div class="product">
            <div class="product-item">
                <img src="product1.jpg" alt="Product 1">
                <h2>Product 1</h2>
                <p>$49.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="product-item">
                <img src="product2.jpg" alt="Product 2">
                <h2>Product 2</h2>
                <p>$59.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="product-item">
                <img src="product3.jpg" alt="Product 3">
                <h2>Product 3</h2>
                <p>$39.99</p>
                <button>Add to Cart</button>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Elegant Sales Website. All rights reserved.</p>
    </footer>

</body>
</html>
<!---
Kazuyai0/Kazuyai0 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
