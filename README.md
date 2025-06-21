<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>صالون طارق</title>
  <link href="https://fonts.googleapis.com/css2?family=Cairo&display=swap" rel="stylesheet" />
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: #000;
      color: #d4af37;
      font-family: 'Cairo', sans-serif;
    }
    header {
      text-align: center;
      padding: 40px 10px 20px 10px;
    }
    header h1 {
      font-size: 3em;
      color: #d4af37;
    }
    header p {
      font-size: 1.2em;
      color: #bfa746cc;
    }
    nav {
      text-align: center;
      margin: 20px 0;
    }
    nav a {
      color: #d4af37;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
      font-size: 1.1em;
    }
    section {
      background-color: #121212;
      padding: 30px 20px;
      margin: 20px auto;
      border-radius: 12px;
      max-width: 900px;
    }
    section h2 {
      text-align: center;
      color: #d4af37;
      margin-bottom: 20px;
    }
    .services-grid {
      display: flex;
      flex-wrap: wrap;
      gap: 25px;
      justify-content: center;
    }
    .service-item {
      background-color: #1a1a1a;
      border-radius: 12px;
      padding: 20px;
      width: 260px;
      text-align: center;
    }
    .service-item img {
      max-width: 100%;
      border-radius: 10px;
      margin-bottom: 15px;
    }
    .service-item h3 {
      margin-bottom: 10px;
      color: #d4af37;
    }
    .service-item p {
      color: #c9b454cc;
    }
    details summary {
      cursor: pointer;
      margin-top: 10px;
      font-weight: bold;
      color: #d4af37;
    }
    details ul {
      list-style: none;
      padding: 10px;
      color: #c9b454cc;
      text-align: right;
    }
    form {
      max-width: 420px;
      margin: auto;
      background-color: #1a1a1a;
      padding: 25px 20px;
      border-radius: 12px;
    }
    form input, form textarea {
      width: 100%;
      padding: 12px;
      margin-bottom: 18px;
      border: none;
      border-radius: 8px;
      background-color: #222;
      color: #d4af37;
      font-family: 'Cairo', sans-serif;
    }
    form button {
      background-color: #d4af37;
      border: none;
      padding: 14px;
      color: #000;
      font-weight: bold;
      width: 100%;
      border-radius: 10px;
      cursor: pointer;
    }
    footer {
      text-align: center;
      padding: 20px;
      color: #666633cc;
      background-color: #0a0a0a;
    }
    @media (max-width: 700px) {
      .services-grid {
        flex-direction: column;
        align-items: center;
      }
      .service-item {
        width: 90%;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>صالون طارق</h1>
    <p>لحلاقة راقية وأناقة لا تُضاهى 💈</p>
    <nav>
      <a href="#about">من نحن</a>
      <a href="#services">الخدمات</a>
      <a href="#contact">تواصل معنا</a>
    </nav>
  </header>

  <section id="about">
    <h2>من نحن</h2>
    <p>صالون طارق هو المكان المثالي للرجل العصري الذي يهتم بمظهره. نقدم لك أفضل خدمات الحلاقة بأسلوب كلاسيكي وحديث، باستخدام منتجات عالية الجودة وأيدي خبيرة.</p>
  </section>

  <section id="services">
    <h2>الخدمات</h2>
    <div class="services-grid">
      <div class="service-item">
        <img src="https://images.unsplash.com/photo-1573496779741-425b2d14aeb3?auto=format&fit=crop&w=400&q=80" alt="قص شعر رجالي" />
        <h3>✂️ قص شعر رجالي</h3>
        <p>قصات عصرية وكلاسيكية تناسب جميع الأذواق</p>
        <details>
          <summary>قائمة الأسعار</summary>
          <ul>
            <li>قص الشعر العادي - 50 درهم</li>
            <li>قص الشعر مع غسيل - 70 درهم</li>
            <li>قص الشعر مع تصفيف - 90 درهم</li>
          </ul>
        </details>
      </div>

      <div class="service-item">
        <img src="https://images.unsplash.com/photo-1504384308090-c894fdcc538d?auto=format&fit=crop&w=400&q=80" alt="تهذيب وتحديد لحية" />
        <h3>🧔 تهذيب وتحديد لحية</h3>
        <p>دقة في التحديد وأناقة في المظهر</p>
        <details>
          <summary>قائمة الأسعار</summary>
          <ul>
            <li>تهذيب لحية فقط - 40 درهم</li>
            <li>تحديد لحية مع تنظيف - 60 درهم</li>
            <li>باقة لحية متكاملة - 80 درهم</li>
          </ul>
        </details>
      </div>

      <div class="service-item">
        <img src="https://images.unsplash.com/photo-1560184897-d0f1645b512a?auto=format&fit=crop&w=400&q=80" alt="صبغ شعر أو لحية" />
        <h3>🎨 صبغ شعر أو لحية</h3>
        <p>ألوان طبيعية وثبات طويل</p>
        <details>
          <summary>قائمة الأسعار</summary>
          <ul>
            <li>صبغ شعر - 120 درهم</li>
            <li>صبغ لحية - 80 درهم</li>
            <li>تلوين طبيعي - 150 درهم</li>
          </ul>
        </details>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>احجز الآن</h2>
    <form>
      <input type="text" placeholder="اسمك" required>
      <input type="tel" placeholder="رقم الهاتف" required>
      <textarea placeholder="ملاحظات أو نوع الخدمة المطلوبة" rows="4"></textarea>
      <button type="submit">إرسال</button>
    </form>
  </section>

  <footer>
    &copy; 2025 صالون طارق. جميع الحقوق محفوظة.
  </footer>

</body>
</html>
