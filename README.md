- 👋 Hi, I’m @halalgloballink
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
halalgloballink/halalgloballink is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple E-commerce</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1em;
        }

        .product-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            padding: 20px;
        }

        .product {
            border: 1px solid #ccc;
            border-radius: 5px;
            padding: 10px;
            margin: 10px;
            width: 300px;
        }

        .product img {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>
    <header>
        <h1>Simple E-commerce</h1>
    </header>

    <div class="product-container">
        <div class="product">
            <img src="product1.jpg" alt="Product 1">
            <h3>Product 1</h3>
            <p>Description of Product 1.</p>
            <p>$50.00</p>
            <button onclick="addToCart('Product 1', 50.00)">Add to Cart</button>
        </div>

        <div class="product">
            <img src="product2.jpg" alt="Product 2">
            <h3>Product 2</h3>
            <p>Description of Product 2.</p>
            <p>$75.00</p>
            <button onclick="addToCart('Product 2', 75.00)">Add to Cart</button>
        </div>
    </div>

    <script>
        function addToCart(productName, price) {
            alert(`Added ${productName} to cart. Total Price: $${price}`);
            // Implement logic to add to the shopping cart
        }
    </script>
</body>
</html>
