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
            background-color: #fff;
            color: #333;
            line-height: 1.6;
        }

        /* الرأس */
        header {
            background: #FFA500; /* برتقالي */
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
            background: #333; /* أسود */
            padding: 10px 0;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-size: 1.1rem;
            transition: color 0.3s ease;
        }

        nav a:hover {
            color: #FFA500; /* برتقالي */
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
            margin: 20px 0;
            font-size: 1.2rem;
            background: #FFFFE0; /* أصفر فاتح */
            border: 1px solid #FFA500; /* برتقالي */
            border-radius: 8px;
            padding: 15px;
        }

        ul li img {
            width: 150px;
            height: auto;
            display: block;
            margin: 0 auto 10px;
        }

        /* النماذج */
        form {
            margin: 20px auto;
            max-width: 400px;
            padding: 20px;
            border: 1px solid #FFA500;
            border-radius: 8px;
            background-color: #FFFFE0; /* أصفر فاتح */
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
            background: #FFA500; /* برتقالي */
            color: white;
            border: none;
            cursor: pointer;
        }

        form button:hover {
            background: #FF8C00; /* برتقالي أغمق */
        }

        /* التذييل */
        footer {
            background: #333; /* أسود */
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }

        footer a {
            color: white;
            margin: 0 10px;
            text-decoration: none;
            font-size: 1.2rem;
        }

        footer a:hover {
            color: #FFA500; /* برتقالي */
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
    <script>
        function showConfirmation() {
            alert("تم إرسال رسالتك بنجاح!");
        }
    </script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
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
            <li>
                <img src="https://via.placeholder.com/150" alt="زجاجة ماء قابلة لإعادة الاستخدام">
                <p>زجاجة ماء قابلة لإعادة الاستخدام - $10</p>
            </li>
            <li>
                <img src="https://via.placeholder.com/150" alt="أكياس تسوق قماشية">
                <p>أكياس تسوق قماشية - $5</p>
            </li>
            <li>
                <img src="https://via.placeholder.com/150" alt="فرشاة أسنان خشبية">
                <p>فرشاة أسنان خشبية - $3</p>
            </li>
            <li>
                <img src="https://via.placeholder.com/150" alt="أكواب قهوة قابلة لإعادة الاستخدام">
                <p>أكواب قهوة قابلة لإعادة الاستخدام - $8</p>
            </li>
            <li>
                <img src="https://via.placeholder.com/150" alt="ألواح صابون طبيعية">
                <p>ألواح صابون طبيعية - $7</p>
            </li>
        </ul>
    </section>

    <!-- صفحة اتصل بنا -->
    <section id="contact">
        <h2>نموذج التواصل</h2>
        <form onsubmit="showConfirmation(); return false;">
            <label for="name">الاسم:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">البريد الإلكتروني:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">رسالتك:</label>
            <textarea id="message" name="message" rows="5" required></textarea>
            <button type="submit">إرسال</button>
        </form>
    </section>

    <footer>
        <p>جميع الحقوق محفوظة &copy; 2025 EcoLife Solutions</p>
        <a href="#"><i class="fab fa-facebook"></i></a>
        <a href="#"><i class="fab fa-twitter"></i></a>
        <a href="#"><i class="fab fa-instagram"></i></a>
    </footer>
</body>
</html>
