# ACSTOR<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AC Store</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #eaeaea;
            margin: 0;
            padding: 0;
            color: #333;
            scroll-behavior: smooth;
        }
        header {
            background-color: #232f3e;
            color: white;
            padding: 10px 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }
        .logo {
            display: flex;
            align-items: center;
        }
        .logo img {
            width: 40px;
            height: 40px;
            margin-right: 10px;
        }
        .logo span {
            font-size: 24px;
            font-weight: bold;
            color: #febd69;
        }
        .search-bar {
            display: flex;
            flex: 1;
            margin: 0 20px;
        }
        .search-bar input {
            width: 100%;
            padding: 10px;
            border: none;
            border-radius: 4px 0 0 4px;
        }
        .search-bar button {
            padding: 10px 20px;
            border: none;
            background-color: #febd69;
            color: #232f3e;
            border-radius: 0 4px 4px 0;
            cursor: pointer;
        }
        .nav-icons {
            display: flex;
            align-items: center;
        }
        .nav-icons a {
            color: white;
            margin-left: 20px;
            text-decoration: none;
            display: flex;
            align-items: center;
        }
        .nav-icons a img {
            width: 20px;
            height: 20px;
            margin-right: 5px;
        }
        .main-content {
            padding: 20px;
        }
        .banner {
            background-color: #131921;
            color: white;
            text-align: center;
            padding: 40px 20px;
            border-radius: 10px;
        }
        .banner h2 {
            margin: 0;
            font-size: 48px;
            color: #febd69;
        }
        .banner p {
            font-size: 24px;
            color: #ddd;
        }
        .sections {
            display: flex;
            justify-content: space-between;
            margin-top: 20px;
        }
        .section-item {
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            flex: 1;
            margin: 0 10px;
            box-shadow: 0 5px 10px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .section-item:hover {
            transform: scale(1.02);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
        }
        footer {
            background-color: #232f3e;
            color: white;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">
            <span>AC Store</span>
        </div>
        <div class="search-bar">
            <input type="text" placeholder="ابحث عن منتجات...">
            <button><img src="https://via.placeholder.com/20" alt="Search"></button>
        </div>
        <div class="nav-icons">
            <a href="#"><img src="https://via.placeholder.com/20" alt="User"> Sign In</a>
            <a href="#"><img src="https://via.placeholder.com/20" alt="Cart"> Cart (0)</a>
        </div>
    </header>
    <div class="main-content">
        <div class="banner">
            <h2>مرحبا بكم في AC Store</h2>
            <p>تسوق أفضل المنتجات بأفضل الأسعار</p>
        </div>
        <div class="sections">
            <div class="section-item">الأقسام</div>
            <div class="section-item">المنتجات</div>
            <div class="section-item">العروض الخاصة</div>
        </div>
        <section id="contact" class="section-item">
            <h2>اتصل بنا</h2>
            <p class="contact-info">للتواصل معنا عبر الهاتف: <a href="tel:0915385891">0915385891</a></p>
        </section>
    </div>
    <footer>
        <p>جميع الحقوق محفوظة &copy; 2024 AC Store</p>
    </footer>
</body>
</html>
