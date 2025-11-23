# Bloomz-store
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Bloomz - One File Store</title>
    <style>
        body { margin: 0; font-family: Arial, sans-serif; background: #fafafa; }
        header { text-align: center; padding: 20px; background: #ff4f8b; color: white; }
        .products { display: flex; gap: 20px; padding: 20px; justify-content: center; flex-wrap: wrap; }
        .product-card { width: 250px; background: white; padding: 15px; border-radius: 10px; box-shadow: 0 2px 8px rgba(0,0,0,0.1); text-align: center; }
        .product-card img { width: 100%; border-radius: 10px; }
        button { margin-top: 10px; padding: 10px 15px; border: none; background: #ff4f8b; color: white; border-radius: 5px; cursor: pointer; }
        footer { text-align: center; padding: 15px; margin-top: 20px; color: #555; }
    </style>
</head>
<body>
    <header>
        <h1>Bloomz</h1>
        <p>Your all-in-one shopping destination</p>
    </header>

    <section class="products">
        <div class="product-card">
            <img src="https://images.unsplash.com/photo-1513709630908-bf4c60a43f6c" />
            <h3>Wireless Earbuds</h3>
            <p>High-quality sound with noise cancellation.</p>
            <button onclick="addToCart('Wireless Earbuds')">Add to Cart</button>
        </div>

        <div class="product-card">
            <img src="https://images.unsplash.com/photo-1503602642458-232111445657" />
            <h3>Smart Watch</h3>
            <p>Track fitness, calls & notifications.</p>
            <button onclick="addToCart('Smart Watch')">Add to Cart</button>
        </div>
    </section>

    <footer>
        <p>© 2025 Bloomz Store</p>
    </footer>

    <script>
        function addToCart(product) {
            alert(product + " added to cart!");
        }
    </script>
</body>
</html>