# sya7i
 <!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>سياحي</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- رأس الموقع -->
    <header>
        <h1>مرحبًا بك في تطبيق "سياحي"</h1>
        <nav>
            <button id="homeBtn">القائمة الرئيسية</button>
            <button id="searchBtn">البحث</button>
            <button id="giftsBtn">الهدايا</button>
        </nav>
    </header>

    <!-- المحتوى الرئيسي -->
    <main id="mainContent">
        <!-- هذه هي الصفحة الرئيسية -->
        <section id="homePage" class="active">
            <h2>المناطق السياحية المشهورة</h2>
            <div class="card-container">
                <div class="card">
                    <img src="images/location1.jpg" alt="المكان 1">
                    <h3>برج خليفة - دبي</h3>
                    <p>أطول برج في العالم.</p>
                    <a href="#" class="details-btn">عرض المزيد</a>
                </div>
                <div class="card">
                    <img src="images/location2.jpg" alt="المكان 2">
                    <h3>الأهرامات - مصر</h3>
                    <p>عجائب الدنيا السبع.</p>
                    <a href="#" class="details-btn">عرض المزيد</a>
                </div>
            </div>
        </section>

        <!-- صفحة البحث -->
        <section id="searchPage" class="hidden">
            <h2>البحث عن الأماكن السياحية</h2>
            <input type="text" id="searchInput" placeholder="اكتب اسم المكان...">
            <button id="searchAction">بحث</button>
            <div id="searchResults"></div>
        </section>

        <!-- صفحة الهدايا -->
        <section id="giftsPage" class="hidden">
            <h2>الهدايا والتذكارات</h2>
            <div class="card-container">
                <div class="card">
                    <img src="images/gift1.jpg" alt="هدية 1">
                    <h3>تمثال الأهرامات</h3>
                    <p>هدية تذكارية فريدة.</p>
                    <button class="buy-btn">شراء</button>
                </div>
                <div class="card">
                    <img src="images/gift2.jpg" alt="هدية 2">
                    <h3>كرة برج خليفة</h3>
                    <p>هدية تعكس جمال دبي.</p>
                    <button class="buy-btn">شراء</button>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer>
        <p>© 2024 تطبيق سياحي - لتسهيل السفر والسياحة</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
