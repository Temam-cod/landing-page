<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Auto-GRADAX</title>

<style>
:root {
    --primary: #ff6600;
    --bg: #f5f7fa;
}
body {
    margin: 0;
    font-family: Tahoma;
    direction: rtl;
    background: var(--bg);
}

.hero {
    background: linear-gradient(135deg,#0f172a,#1e3a8a);
    color: white;
    text-align: center;
    padding: 80px 20px;
}

.btn {
    background: var(--primary);
    color: white;
    padding: 10px 15px;
    border-radius: 8px;
    text-decoration: none;
    cursor: pointer;
}

.section {
    padding: 40px;
    max-width: 1100px;
    margin: auto;
}

.products {
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(250px,1fr));
    gap: 20px;
}

.product {
    background: white;
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
}

.product img {
    width: 100%;
    height: 180px;
    object-fit: cover;
}

.product-content {
    padding: 15px;
}

.product-content h3 {
    margin: 0 0 10px;
}

.product-content p {
    font-size: 14px;
    color: #555;
}

.form-box {
    background: white;
    padding: 20px;
    border-radius: 10px;
}

input, select {
    width: 100%;
    padding: 10px;
    margin: 6px 0;
}

.whatsapp {
    position: fixed;
    bottom: 20px;
    left: 20px;
    background: #25D366;
    width: 60px;
    height: 60px;
    border-radius: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
}
</style>
</head>

<body>

<section class="hero">
<h1>قطع غيار سيارات أصلية</h1>
<p>توصيل سريع + الدفع عند الاستلام</p>
<a class="btn" href="#order">اطلب الآن</a>
</section>

<section class="section">
<h2>منتجاتنا</h2>
<div class="products">

<!-- منتج 1 -->
<div class="product">
<img src="https://images.unsplash.com/photo-1605559424843-9e4c228bf1c2" alt="">
<div class="product-content">
<h3>فلتر زيت</h3>
<p>فلتر زيت عالي الجودة يحافظ على محرك السيارة ويطيل عمره.</p>
<p><b>السعر: 2500 دج</b></p>
<button class="btn" onclick="selectProduct('فلتر زيت')">اطلب الآن</button>
</div>
</div>

<!-- منتج 2 -->
<div class="product">
<img src="https://images.unsplash.com/photo-1619642751034-765dfdf7c58e" alt="">
<div class="product-content">
<h3>Plaquette frein</h3>
<p>فرامل قوية وآمنة، مقاومة للحرارة وتدوم طويلاً.</p>
<p><b>السعر: 4500 دج</b></p>
<button class="btn" onclick="selectProduct('Plaquette frein')">اطلب الآن</button>
</div>
</div>

<!-- منتج 3 -->
<div class="product">
<img src="https://images.unsplash.com/photo-1581092580497-e0d23cbdf1dc" alt="">
<div class="product-content">
<h3>بوجيهات</h3>
<p>تشغيل سريع للمحرك وتحسين استهلاك الوقود.</p>
<p><b>السعر: 2200 دج</b></p>
<button class="btn" onclick="selectProduct('بوجيهات')">اطلب الآن</button>
</div>
</div>

</div>
</section>

<!-- الفورم -->
<section class="section" id="order">
<h2>تأكيد الطلب</h2>

<div class="form-box">
<input type="text" id="name" placeholder="الاسم">
<input type="tel" id="phone" placeholder="رقم الهاتف">

<input type="text" id="product" placeholder="المنتج المختار">

<input type="number" id="qty" placeholder="الكمية">

<select id="wilaya">
<option>اختر الولاية</option>
<option>الجزائر</option>
<option>البليدة</option>
<option>وهران</option>
<option>قسنطينة</option>
<option>سطيف</option>
<option>عنابة</option>
<option>باتنة</option>
<option>بسكرة</option>
<option>اختر الولاية</option>
<option>الجزائر</option>
<option>البليدة</option>
<option>وهران</option>
<option>قسنطينة</option>
<option>سطيف</option>
<option>عنابة</option>
<option>باتنة</option>
<option>بسكرة</option>
<option>اختر الولاية</option>
<option>الجزائر</option>
<option>البليدة</option>
<option>وهران</option>
<option>قسنطينة</option>
<option>سطيف</option>
<option>عنابة</option>
<option>باتنة</option>
<option>بسكرة</option>
<option>اختر الولاية</option>
<option>الجزائر</option>
<option>البليدة</option>
<option>وهران</option>
<option>قسنطينة</option>
<option>سطيف</option>
<option>عنابة</option>
<option>باتنة</option>
<option>بسكرة</option>
<option>اختر الولاية</option>
<option>الجزائر</option>
<option>البليدة</option>
<option>وهران</option>
<option>قسنطينة</option>
<option>سطيف</option>
<option>عنابة</option>
<option>باتنة</option>
<option>بسكرة</option>
<option>اختر الولاية</option>
<option>الجزائر</option>
<option>البليدة</option>
<option>وهران</option>
<option>قسنطينة</option>
<option>سطيف</option>
<option>عنابة</option>
<option>باتنة</option>
<option>بسكرة</option>
<option>اختر الولاية</option>
<option>الجزائر</option>
<option>البليدة</option>
<option>وهران</option>
<option>قسنطينة</option>
<option>سطيف</option>
<option>عنابة</option>
<option>باتنة</option>
<option>بسكرة</option>
<option>اختر الولاية</option>
<option>الجزائر</option>
<option>البليدة</option>
<option>وهران</option>
<option>قسنطينة</option>
<option>سطيف</option>
<option>عنابة</option>
<option>باتنة</option>
<option>بسكرة</option>
<option>اختر الولاية</option>
<option>الجزائر</option>
<option>البليدة</option>
<option>وهران</option>
<option>قسنطينة</option>
<option>سطيف</option>
<option>عنابة</option>
<option>باتنة</option>
<option>بسكرة</option>
<option>اختر الولاية</option>
<option>الجزائر</option>
<option>البليدة</option>
<option>وهران</option>
<option>قسنطينة</option>
<option>سطيف</option>
<option>عنابة</option>
<option>باتنة</option>
<option>بسكرة</option>
<option>اختر الولاية</option>
<option>الجزائر</option>
<option>البليدة</option>
<option>وهران</option>
<option>قسنطينة</option>
<option>سطيف</option>
<option>عنابة</option>
<option>باتنة</option>
<option>بسكرة</option>
</select>

<p>الدفع عند الاستلام</p>

<button class="btn" onclick="sendOrder()">تأكيد الطلب</button>
</div>
</section>

<a class="whatsapp" id="wa">💬</a>

<script>
const phoneNumber = "213557626213";

function selectProduct(name){
    document.getElementById("product").value = name;
    window.location.href = "#order";
}

function sendOrder(){
    let name     = document.getElementById("name").value;
    let phone    = document.getElementById("phone").value;
    let product  = document.getElementById("product").value;
    let qty      = document.getElementById("qty").value;
    let wilaya   = document.getElementById("wilaya").value;

    let msg = `طلب جديد:
الاسم: ${name}
الهاتف: ${phone}
المنتج: ${product}
الكمية: ${qty}
الولاية: ${wilaya}
الدفع: عند الاستلام`;

    window.open(`https://wa.me/${phoneNumber}?text=${encodeURIComponent(msg)}`);
}

document.getElementById("wa").href =
`https://wa.me/${phoneNumber}?text=مرحبا اريد الاستفسار`;
</script>

</body>
</html>
