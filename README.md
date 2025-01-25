index.html
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EcoLife Solutions</title>
    <style>
        /* التنسيقات العامة */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
            line-height: 1.6;
        }

        /* الرأس */
        header {
            background: #4CAF50;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        header p {
            margin: 10px 0 0;
            font-size: 1.2rem;
        }

        /* شريط التنقل */
        nav {
            background: #333;
            padding: 10px 0;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-size: 1.1rem;
        }

        nav a:hover {
            text-decoration: underline;
        }

        /* الأقسام */
        section {
            padding: 20px;
            text-align: center;
        }

        /* القوائم */
        ul {
            list-style: none;
            padding: 0;
        }

        ul li {
            margin: 10px 0;
            font-size: 1.2rem;
        }

        /* النماذج */
        form {
            margin: 20px auto;
            max-width: 400px;
            padding: 20px;
            border: 1px solid #ddd;
            border-radius: 8px;
            background-color: white;
        }

        form label {
            display: block;
            margin-bottom: 8px;
            font-weight: bold;
        }

        form input,
        form textarea,
        form button {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 4px;
            font-size: 1rem;
        }

        form button {
            background: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
        }

        form button:hover {
            background: #45a049;
        }

        /* التذييل */
        footer {
            background: #4CAF50;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }

        /* التصميم المتجاوب */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2rem;
            }

            nav a {
                font-size: 1rem;
            }

            form {
                width: 90%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>مرحبا بكم في EcoLife Solutions</h1>
        <p>منتجات صديقة للبيئة من أجل مستقبل مستدام</p>
    </header>
    <nav>
        <a href="#home">الرئيسية</a>
        <a href="#products">المنتجات</a>
        <a href="#contact">اتصل بنا</a>
    </nav>

    <!-- الصفحة الرئيسية -->
    <section id="home">
        <h2>عن شركتنا</h2>
        <p>EcoLife Solutions هي شركة محلية تقدم حلولًا مستدامة وبيئية لمساعدتك في تحقيق أسلوب حياة أكثر صداقة للبيئة.</p>
    </section>

    <!-- صفحة المنتجات -->
    <section id="products">
        <h2>منتجات صديقة للبيئة</h2>
        <ul>
            <li>منتج 1 - وصف قصير - $10</li>
            <li>منتج 2 - وصف قصير - $15</li>
            <li>منتج 3 - وصف قصير - $20</li>
            <li>منتج 4 - وصف قصير - $25</li>
            <li>منتج 5 - وصف قصير - $30</li>
        </ul>
    </section>

    <!-- صفحة اتصل بنا -->
    <section id="contact">
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
