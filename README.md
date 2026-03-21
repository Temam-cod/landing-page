[landing-page.html](https://github.com/user-attachments/files/26161680/landing-page.html)
<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Auto-GRADAX</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    direction: rtl;
    background: #f5f7fa;
}

/* HEADER */
header {
    background: #111;
    color: white;
    padding: 15px;
    text-align: center;
    font-size: 22px;
}

/* HERO */
.hero {
    background: linear-gradient(135deg, #0f2027, #2c5364);
    color: white;
    text-align: center;
    padding: 80px 20px;
}

.hero h1 {
    font-size: 35px;
}

.hero p {
    font-size: 18px;
    margin: 15px 0;
}

.btn {
    background: #ff6600;
    color: white;
    padding: 12px 25px;
    border: none;
    cursor: pointer;
    font-size: 16px;
    margin: 10px;
    border-radius: 5px;
}

.btn:hover {
    background: #e65c00;
}

/* FEATURES */
.features {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    padding: 40px;
}

.feature {
    background: white;
    margin: 10px;
    padding: 20px;
    width: 250px;
    text-align: center;
    border-radius: 10px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
}

/* PRODUCTS */
.products {
    padding: 40px;
    text-align: center;
}

.product {
    display: inline-block;
    background: white;
    margin: 10px;
    padding: 15px;
    width: 220px;
    border-radius: 10px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
}

.product img {
    width: 100%;
    border-radius: 10px;
}

/* CTA */
.cta {
    background: #ff6600;
    color: white;
    text-align: center;
    padding: 40px;
}

/* FOOTER */
footer {
    background: #111;
    color: white;
    text-align: center;
    padding: 20px;
}

/* WHATSAPP BUTTON */
.whatsapp {
    position: fixed;
    bottom: 20px;
    left: 20px;
    background: #25D366;
    color: white;
    padding: 15px;
    border-radius: 50%;
    font-size: 20px;
    text-decoration: none;
}
</style>
</head>

<body>

<header>
Auto-GRADAX 🚗
</header>

<section class="hero">
<h1>أفضل قطع غيار السيارات في الجزائر</h1>
<p>جودة أصلية + توصيل سريع لكل الولايات</p>
<button class="btn" onclick="orderNow()">اطلب الآن</button>
</section>

<section class="features">
<div class="feature">✔ قطع أصلية</div>
<div class="feature">✔ توصيل سريع</div>
<div class="feature">✔ أسعار مناسبة</div>
<div class="feature">✔ دعم دائم</div>
</section>

<section class="products">
<h2>منتجاتنا</h2>

<div class="product">
<img src="https://via.placeholder.com/200">
<h3>فلتر زيت Clio</h3>
<p>2500 دج</p>
<button class="btn" onclick="orderNow()">اطلب</button>
</div>

<div class="product">
<img src="https://via.placeholder.com/200">
<h3>Plaquette frein</h3>
<p>4500 دج</p>
<button class="btn" onclick="orderNow()">اطلب</button>
</div>

</section>

<section class="cta">
<h2>لا تضيع الفرصة 🔥</h2>
<button class="btn" onclick="orderNow()">اطلب الآن عبر واتساب</button>
</section>

<footer>
الهاتف: +213 557 62 62 13 | Auto-GRADAX
</footer>

<a href="https://wa.me/213000000000" class="whatsapp" target="_blank">💬</a>

<script>
function orderNow() {
    window.location.href = "https://wa.me/213000000000?text=أريد طلب منتج";
}
</script>

</body>
</html>
