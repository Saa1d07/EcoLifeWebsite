index.html
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EcoLife Solutions</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            background-color: #f9f9f9;
        }
        header {
            background: #4CAF50;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            background: #333;
            color: #fff;
            padding: 0.5rem 0;
        }
        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            padding: 2rem;
            text-align: center;
        }
        footer {
            background: #4CAF50;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
            margin-top: 2rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>مرحبا بكم في EcoLife Solutions</h1>
        <p>منتجات صديقة للبيئة من أجل مستقبل مستدام</p>
    </header>
    <nav>
        <a href="index.html">الرئيسية</a>
        <a href="products.html">المنتجات</a>
        <a href="contact.html">اتصل بنا</a>
    </nav>
    <section>
        <h2>عن شركتنا</h2>
        <p>EcoLife Solutions هي شركة محلية تقدم حلولًا مستدامة وبيئية لمساعدتك في تحقيق أسلوب حياة أكثر صداقة للبيئة.</p>
    </section>
    <footer>
        <p>جميع الحقوق محفوظة &copy; 2025 EcoLife Solutions</p>
    </footer>
</body>
</html>
products.html
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>منتجاتنا</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>منتجاتنا</h1>
    </header>
    <nav>
        <a href="index.html">الرئيسية</a>
        <a href="products.html">المنتجات</a>
        <a href="contact.html">اتصل بنا</a>
    </nav>
    <section>
        <h2>منتجات صديقة للبيئة</h2>
        <ul>
            <li>منتج 1 - وصف قصير - $10</li>
            <li>منتج 2 - وصف قصير - $15</li>
            <li>منتج 3 - وصف قصير - $20</li>
            <li>منتج 4 - وصف قصير - $25</li>
            <li>منتج 5 - وصف قصير - $30</li>
        </ul>
    </section>
    <footer>
        <p>جميع الحقوق محفوظة &copy; 2025 EcoLife Solutions</p>
    </footer>
</body>
</html>
contact.html
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>اتصل بنا</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>اتصل بنا</h1>
    </header>
    <nav>
        <a href="index.html">الرئيسية</a>
        <a href="products.html">المنتجات</a>
        <a href="contact.html">اتصل بنا</a>
    </nav>
    <section>
        <h2>نموذج التواصل</h2>
        <form action="#">
            <label for="name">الاسم:</label><br>
            <input type="text" id="name" name="name" required><br>
            <label for="email">البريد الإلكتروني:</label><br>
            <input type="email" id="email" name="email" required><br>
            <label for="message">رسالتك:</label><br>
            <textarea id="message" name="message" rows="5" required></textarea><br>
            <button type="submit">إرسال</button>
        </form>
    </section>
    <footer>
        <p>جميع الحقوق محفوظة &copy; 2025 EcoLife Solutions</p>
    </footer>
</body>
</html> 
