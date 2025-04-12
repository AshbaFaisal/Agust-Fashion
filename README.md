<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Agust Fashion</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #6791eb;
            color: #1a1a1a;
        }

        header {
            background-color: #f0eef5;
            padding: 30px;
            text-align: center;
            border-bottom: 1px solid #e0e0e0;
        }

        header h1 {
            font-size: 32px;
            margin: 0;
            font-weight: 500;
            letter-spacing: 1px;
        }

        nav {
            display: flex;
            justify-content: center;
            gap: 30px;
            padding: 20px 0;
            background-color: #fafafa;
            border-bottom: 1px solid #ddd;
        }

        nav a {
            color: #111;
            text-decoration: none;
            font-size: 14px;
            font-weight: 500;
            text-transform: uppercase;
        }

        nav a:hover {
            color: #555;
        }

        .hero-section {
            background-image: url('https://via.placeholder.com/1500x700/fff/000?text=Agust+Fashion+Spring+Drop');
            background-size: cover;
            background-position: center;
            height: 75vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: #111;
        }

        .hero-section h1 {
            font-size: 42px;
            margin-bottom: 15px;
        }

        .hero-section p {
            font-size: 18px;
            margin-bottom: 25px;
        }

        .btn-shop {
            background-color: #111;
            color: #fff;
            padding: 12px 28px;
            border: none;
            font-size: 14px;
            cursor: pointer;
            text-transform: uppercase;
        }

        .btn-shop:hover {
            background-color: #333;
        }

        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(240px, 1fr));
            gap: 24px;
            padding: 40px 20px;
        }

        .product {
            background-color: #fff;
            padding: 15px;
            border: 1px solid #eaeaea;
            border-radius: 8px;
            text-align: center;
        }

        .product img {
            width: 100%;
            height: 280px;
            object-fit: cover;
            border-radius: 6px;
        }

        .product-info h3 {
            font-size: 16px;
            margin: 15px 0 5px;
        }

        .price {
            color: #111;
            font-weight: bold;
        }

        .faq-section, .reviews-section, .benefits-section {
            background-color: #fff;
            padding: 50px 20px;
        }

        .faq-section h2, .reviews-section h2, .benefits-section h2 {
            text-align: center;
            font-size: 28px;
            margin-bottom: 30px;
        }

        .faq-item h3 {
            font-size: 18px;
            cursor: pointer;
            margin-bottom: 10px;
        }

        .faq-item p {
            display: none;
            color: #666;
            font-size: 14px;
        }

        .faq-item.active p {
            display: block;
        }

        .review {
            background: #fafafa;
            border-radius: 6px;
            padding: 20px;
            margin-bottom: 20px;
        }

        .review-info {
            display: flex;
            justify-content: space-between;
        }

        .stars {
            color: #f5a623;
        }

        .review-text {
            margin-top: 10px;
            color: #444;
        }

        .benefit-item {
            margin-bottom: 20px;
            text-align: center;
            font-size: 14px;
        }

        footer {
            background-color: #111;
            color: white;
            text-align: center;
            padding: 30px 20px;
            font-size: 14px;
        }

        footer a {
            color: white;
            margin: 0 8px;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }

        @media (max-width: 768px) {
            nav {
                flex-direction: column;
                gap: 15px;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>Agust Fashion</h1>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">Shop</a>
        <a href="#">New In</a>
        <a href="#">Sale</a>
        <a href="#">Contact</a>
    </nav>

    <section class="hero-section">
        <h1>Spring '25 Collection</h1>
        <p>Effortless looks. Minimal vibes.</p>
        <button class="btn-shop">Shop Now</button>
    </section>

    <section class="product-grid">
        <div class="product">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQSJbE9Yz5DzeWoWULS6uQBGeZYM_DR66LRZQ&s" alt="Tote Bag">
            <div class="product-info">
                <h3>Tote Bag</h3>
                <div class="price">$129.99</div>
            </div>
        </div>
        <div class="product">
            <img src="https://darkaesthetic.store/cdn/shop/files/Reaper_FLH_back.png?v=1727537071">
            <div class="product-info">
                <h3>Fleece Hoodie</h3>
                <div class="price">$199.99</div>
            </div>
        </div>
        <div class="product">
            <img src="https://y2kdream.com/cdn/shop/files/Y2K-Afterthought-Graphic-T-Shirt-2.webp?v=1722610035&width=800">
            <div class="product-info">
                <h3>Graphic T-Shirt</h3>
                <div class="price">$29.99</div>
            </div>
        </div>
        <div class="product">
            <img src="https://aesthetic-clothing.com/cdn/shop/products/aesthetic-clothing-high-waisted-black-cargo-pants-525.jpg?v=1635406067">
            <div class="product-info">
                <h3>Cargo Pants</h3>
                <div class="price">$49.99</div>
            </div>
        </div>
        <div class="product">
            <img src="https://img.kwcdn.com/product/Fancyalgo/VirtualModelMatting/46b9b6cd2a289a4a80a3ce9d0efc8340.jpg">
            <div class="product-info">
                <h3>Platform Sneakers</h3>
                <div class="price">$49.99</div>
            </div>
        </div>
    </section>

    <section class="faq-section">
        <h2>FAQs</h2>
        <div class="faq-item">
            <h3>Return Policy?</h3>
            <p>Returns accepted within 30 days with proof of purchase.</p>
        </div>
        <div class="faq-item">
            <h3>Shipping Time?</h3>
            <p>Typically 5-7 business days based on location.</p>
        </div>
        <div class="faq-item">
            <h3>Do you offer gift cards?</h3>
            <p>Yes, digital gift cards are available online.</p>
        </div>
    </section>

    <section class="reviews-section">
        <h2>Customer Reviews</h2>
        <div class="review">
            <div class="review-info">
                <span class="stars">⭐⭐⭐⭐⭐</span>
                <span>Jane D.</span>
            </div>
            <p class="review-text">Amazing quality and super fast delivery. Love Agust Fashion!</p>
        </div>
        <div class="review">
            <div class="review-info">
                <span class="stars">⭐⭐⭐⭐</span>
                <span>Mark S.</span>
            </div>
            <p class="review-text">Cool designs! Would love more size options though.</p>
        </div>
    </section>

    <section class="benefits-section">
        <h2>Why Agust Fashion?</h2>
        <div class="benefit-item">Free Shipping on Orders $50+</div>
        <div class="benefit-item">Easy Exchanges</div>
        <div class="benefit-item">24/7 Support</div>
    </section>

    <footer>
        <p>&copy; 2025 Agust Fashion. All rights reserved.</p>
        <p><a href="#">About</a> | <a href="#">Privacy</a> | <a href="#">Terms</a></p>
    </footer>

    <script>
        document.querySelectorAll('.faq-item h3').forEach((item) => {
            item.addEventListener('click', () => {
                item.parentElement.classList.toggle('active');
            });
        });
    </script>

</body>
</html>
