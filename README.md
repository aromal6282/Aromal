<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Toy Store</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f7f7f7; }
        header { background: #ff6f61; color: white; padding: 20px; text-align: center; font-size: 28px; }
        .hero { padding: 40px; background: #ffe8e5; text-align: center; }
        .hero h1 { font-size: 40px; margin-bottom: 10px; }
        .hero p { font-size: 18px; }
        .products { display: flex; flex-wrap: wrap; justify-content: center; padding: 20px; }
        .card { background: white; width: 250px; margin: 15px; border-radius: 12px; overflow: hidden; box-shadow: 0 4px 10px rgba(0,0,0,0.1); }
        .card img { width: 100%; }
        .card h3 { padding: 10px; font-size: 20px; }
        .card p { padding: 0 10px 10px; font-size: 14px; color: #555; }
        .card button { width: 100%; padding: 12px; border: none; background: #ff6f61; color: white; cursor: pointer; font-size: 16px; }
        footer { background: #333; color: white; text-align: center; padding: 15px; margin-top: 20px; }
    </style>
</head>
<body>
    <header>Toy Store</header>

    <section class="hero">
        <h1>Welcome to Our Toy Shop!</h1>
        <p>Find the best toys for kids of all ages.</p>
    </section>

    <section class="products">
        <div class="card">
            <img src="https://via.placeholder.com/250x200" alt="Toy 1">
            <h3>Toy Car</h3>
            <p>High‑quality mini racing car for kids.</p>
            <button>Buy Now</button>
        </div>

        <div class="card">
            <img src="https://via.placeholder.com/250x200" alt="Toy 2">
            <h3>Teddy Bear</h3>
            <p>Soft and cuddly teddy bear for children.</p>
            <button>Buy Now</button>
        </div>

        <div class="card">
            <img src="https://via.placeholder.com/250x200" alt="Toy 3">
            <h3>Building Blocks</h3>
            <p>Colorful blocks to boost creativity.</p>
            <button>Buy Now</button>
        </div>
    </section>

    <footer>
        © 2025 Toy Store. All rights reserved.
    </footer>
</body>
</html>
