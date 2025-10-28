<!DOCTYPE html>
<html lang="ur">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Apni Dukan - Online Shop</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <!-- Navigation -->
    <header>
        <nav class="navbar">
            <div class="logo">
                <h2>🛍️ Apni Dukan</h2>
            </div>
            <ul class="nav-links">
                <li><a href="index.html">Home</a></li>
                <li><a href="products.html">Products</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
                <li><a href="admin/index.html">Admin</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="hero-content">
            <h1>Welcome to Apni Dukan</h1>
            <p>Best quality products at affordable prices</p>
            <button class="cta-button" onclick="window.location.href='products.html'">
                Shop Now
            </button>
        </div>
    </section>

    <!-- Featured Products -->
    <section class="featured-products">
        <h2>Featured Products</h2>
        <div class="products-grid" id="featuredProducts">
            <!-- Products yahan load hongay -->
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="footer-content">
            <p>&copy; 2024 Apni Dukan. All rights reserved.</p>
            <p>Email: contact@apnidukan.com | Phone: 0300-1234567</p>
        </div>
    </footer>

    <script src="js/script.js"></script>
</body>
</html>
