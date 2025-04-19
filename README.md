<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>متجري الإلكتروني</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>🛍️ متجري</h1>
    <nav>
      <ul>
        <li><a href="#">الصفحة الرئيسية</a></li>
        <li><a href="#">المنتجات</a></li>
        <li><a href="#">سلة المشتريات</a></li>
      </ul>
      <span id="cart-counter">السلة (0)</span>
    </nav>
  </header>

  <!-- التصنيفات -->
  <section id="categories">
    <button onclick="filterByCategory('الكل')">الكل</button>
    <button onclick="filterByCategory('ملابس')">ملابس</button>
    <button onclick="filterByCategory('أحذية')">أحذية</button>
    <button onclick="filterByCategory('اكسسوارات')">اكسسوارات</button>
  </section>

  <!-- قائمة المنتجات -->
  <main id="product-list"></main>

  <footer>
    <p>© 2025 متجري. جميع الحقوق محفوظة.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
