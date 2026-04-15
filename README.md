<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>Fashion KZ</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>🛍 Fashion KZ</h1>
    <p>Онлайн магазин одежды</p>
</header>

<nav>
    <button onclick="filter('all')">Все</button>
    <button onclick="filter('Футболка')">Футболки</button>
    <button onclick="filter('Худи')">Худи</button>
</nav>

<section class="products" id="products">

<div class="card" data-name="Футболка">
<img src="https://images.unsplash.com/photo-1521572163474-6864f9cf17ab">
<h3>Футболка Oversize</h3>
<p>5 000 ₸</p>
<button onclick="addToCart('Футболка')">Купить</button>
</div>

<div class="card" data-name="Худи">
<img src="https://images.unsplash.com/photo-1556821840-3a63f95609a7">
<h3>Худи</h3>
<p>12 000 ₸</p>
<button onclick="addToCart('Худи')">Купить</button>
</div>

<div class="card" data-name="Футболка">
<img src="https://images.unsplash.com/photo-1542272604-787c3835535d">
<h3>Джинсы</h3>
<p>15 000 ₸</p>
<button onclick="addToCart('Джинсы')">Купить</button>
</div>

</section>

<section class="cart">
<h2>🛒 Корзина</h2>
<ul id="cart-list"></ul>
<p id="total">Итого: 0 ₸</p>
</section>

<footer>
<p>© 2026 Fashion KZ | Казахстан</p>
</footer>

<script src="script.js"></script>
</body>
</html>
