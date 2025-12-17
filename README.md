<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HM - موقع تجاري</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #222;
            padding: 10px;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .product {
            border: 1px solid #ddd;
            padding: 10px;
            width: 200px;
            text-align: center;
        }
        .product img {
            width: 100%;
            height: 150px;
            object-fit: cover;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
        form {
            max-width: 400px;
            margin: 0 auto;
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 4px;
        }
        button {
            background-color: #333;
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
            width: 100%;
        }
        button:hover {
            background-color: #555;
        }
    </style>
</head>
<body>
    <header>
        <h1>HM</h1>
        <p>موقع تجاري للمنتجات الرائعة</p>
    </header>
    <nav>
        <a href="#home">الرئيسية</a>
        <a href="#about">عن الشركة</a>
        <a href="#products">المنتجات</a>
        <a href="#contact">الاتصال</a>
    </nav>
    
    <div class="container" id="home">
        <h2>مرحباً بك في HM</h2>
        <p>نحن نقدم أفضل المنتجات بأسعار تنافسية. استكشف مجموعتنا الواسعة!</p>
    </div>
    
    <div class="container" id="about">
        <h2>عن الشركة</h2>
        <p>HM هي شركة تجارية متخصصة في بيع المنتجات عبر الإنترنت. نحن نلتزم بالجودة والخدمة الممتازة.</p>
    </div>
    
    <div class="container" id="products">
        <h2>المنتجات</h2>
        <div class="products">
            <div class="product">
                <img src="https://via.placeholder.com/200x150?text=منتج+1" alt="منتج 1">
                <h3>منتج 1</h3>
                <p>وصف المنتج. سعر: 100 ريال.</p>
                <button>أضف إلى السلة</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/200x150?text=منتج+2" alt="منتج 2">
                <h3>منتج 2</h3>
                <p>وصف المنتج. سعر: 150 ريال.</p>
                <button>أضف إلى السلة</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/200x150?text=منتج+3" alt="منتج 3">
                <h3>منتج 3</h3>
                <p>وصف المنتج. سعر: 200 ريال.</p>
                <button>أضف إلى السلة</button>
            </div>
        </div>
    </div>
    
    <div class="container" id="contact">
        <h2>اتصل بنا</h2>
        <form>
            <input type="text" placeholder="اسمك" required>
            <input type="email" placeholder="بريدك الإلكتروني" required>
            <textarea placeholder="رسالتك" rows="5" required></textarea>
            <button type="submit">إرسال</button>
        </form>
    </div>
    
    <footer>
        <p>&copy; 2023 HM. جميع الحقوق محفوظة.</p>
    </footer>
    
    <script>
        // JavaScript بسيط للتعامل مع النموذج
        document.querySelector('form').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('شكراً لك! تم إرسال رسالتك.');
        });
    </script>
</body>
</html>
