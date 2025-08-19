<!DOCTYPE html>
<html lang="he" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nike | פשוט עשה זאת</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts - Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f5f5f5; /* רקע בהיר */
        }
        /* אפקטים נוספים לכפתורים */
        .btn-primary {
            background-color: #1f2937; /* כהה יותר, קרוב לשחור */
            color: white;
            padding: 1rem 2rem;
            border-radius: 9999px; /* Rounded-full */
            font-weight: 600; /* Font-semibold */
            transition: all 0.3s ease-in-out;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .btn-primary:hover {
            background-color: #374151; /* כהה יותר בהובר */
            transform: scale(1.05);
            box-shadow: 0 10px 15px rgba(0, 0, 0, 0.2);
        }
        .btn-secondary {
            background-color: #3b82f6; /* כחול */
            color: white;
            padding: 0.75rem 1.5rem;
            border-radius: 9999px;
            font-weight: 600;
            transition: all 0.3s ease-in-out;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .btn-secondary:hover {
            background-color: #2563eb; /* כחול כהה יותר בהובר */
            transform: scale(1.05);
            box-shadow: 0 10px 15px rgba(0, 0, 0, 0.2);
        }
    </style>
</head>
<body class="text-gray-800">
    <!-- כותרת עליונה (Header) -->
    <header class="bg-white shadow-md p-4 sticky top-0 z-50 rounded-b-lg">
        <div class="container mx-auto flex justify-between items-center flex-wrap">
            <!-- לוגו נייק -->
            <a href="#" class="text-3xl font-bold text-gray-900 rounded-md">
                <!-- לוגו נייק מעודכן -->
                <img src="https://www.oneprojectshop.com/cdn/shop/files/Nike.png?v=1668428736" onerror="this.src='https://placehold.co/80x30/000000/ffffff?text=NIKE'" alt="לוגו נייק" class="h-8 md:h-10 object-contain">
            </a>

            <!-- ניווט ראשי (Desktop) -->
            <nav class="hidden md:flex space-x-6 text-lg">
                <a href="#" class="text-gray-700 hover:text-gray-900 font-medium transition duration-300 ease-in-out rounded-md p-2">גברים</a>
                <a href="#" class="text-gray-700 hover:text-gray-900 font-medium transition duration-300 ease-in-out rounded-md p-2">נשים</a>
                <a href="#" class="text-gray-700 hover:text-gray-900 font-medium transition duration-300 ease-in-out rounded-md p-2">ילדים</a>
                <a href="#" class="text-gray-700 hover:text-gray-900 font-medium transition duration-300 ease-in-out rounded-md p-2">מכירה</a>
                <a href="#" class="text-gray-700 hover:text-gray-900 font-medium transition duration-300 ease-in-out rounded-md p-2">מותגים</a>
            </nav>

            <!-- אייקונים (סל קניות, חיפוש) -->
            <div class="flex items-center space-x-4">
                <button class="text-gray-700 hover:text-gray-900 transition duration-300 ease-in-out rounded-md p-2">
                    <svg class="h-6 w-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path></svg>
                </button>
                <button class="text-gray-700 hover:text-gray-900 transition duration-300 ease-in-out rounded-md p-2">
                    <svg class="h-6 w-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13v8a1 1 0 001 1h8a1 1 0 001-1v-8m-11 0h8"></path></svg>
                </button>
            </div>
        </div>
        <!-- ניווט ראשי (Mobile Toggle Button) -->
        <button class="md:hidden mt-2 p-2 rounded-md bg-gray-100 hover:bg-gray-200 text-gray-700 w-full flex justify-center items-center" onclick="document.getElementById('mobile-menu').classList.toggle('hidden');">
            תפריט
            <svg class="h-5 w-5 ml-2" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path></svg>
        </button>
        <!-- ניווט ראשי (Mobile) -->
        <nav id="mobile-menu" class="md:hidden hidden flex flex-col items-center mt-4 space-y-2">
            <a href="#" class="text-gray-700 hover:text-gray-900 font-medium transition duration-300 ease-in-out rounded-md p-2 w-full text-center">גברים</a>
            <a href="#" class="text-gray-700 hover:text-gray-900 font-medium transition duration-300 ease-in-out rounded-md p-2 w-full text-center">נשים</a>
            <a href="#" class="text-gray-700 hover:text-gray-900 font-medium transition duration-300 ease-in-out rounded-md p-2 w-full text-center">ילדים</a>
            <a href="#" class="text-gray-700 hover:text-gray-900 font-medium transition duration-300 ease-in-out rounded-md p-2 w-full text-center">מכירה</a>
            <a href="#" class="text-gray-700 hover:text-gray-900 font-medium transition duration-300 ease-in-out rounded-md p-2 w-full text-center">מותגים</a>
        </nav>
    </header>

    <!-- קטע גיבור (Hero Section) -->
    <main class="container mx-auto mt-8 p-4">
        <section class="relative bg-gray-900 text-white rounded-lg overflow-hidden shadow-lg mb-12">
            <!-- תמונת גיבור אמיתית -->
            <img src="https://marketimg.marmelada.co.il/photos/thumbnails_1129_1000_detailed_2F6567_2FDH2987-101.jpg" onerror="this.src='https://placehold.co/1200x500/1a202c/ffffff?text=Just+Do+It'" alt="Just Do It" class="w-full h-96 object-cover object-center opacity-70">
            <div class="absolute inset-0 flex flex-col justify-center items-center text-center p-6 bg-black bg-opacity-40 rounded-lg">
                <h1 class="text-4xl md:text-6xl font-extrabold mb-4 animate-pulse">פשוט עשה זאת.</h1>
                <p class="text-lg md:text-xl mb-8 max-w-2xl">
                    גלו את הקולקציה החדשה שלנו וקחו את הביצועים שלכם לשלב הבא.
                </p>
                <button class="btn-primary">
                    קנו עכשיו
                </button>
            </div>
        </section>

        <!-- קטגוריות מוצרים -->
        <section class="mb-12">
            <h2 class="text-3xl font-bold text-center mb-8">חקרו את הקטגוריות שלנו</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <!-- קטגוריה: נעליים -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden transform hover:scale-105 transition duration-300 ease-in-out">
                    <!-- תמונת קטגוריה אמיתית -->
                    <img src="https://marketimg.marmelada.co.il/photos/thumbnails_1129_1000_detailed_2F6567_2FDH2987-101.jpg" onerror="this.src='https://placehold.co/400x250/333333/ffffff?text=נעליים'" alt="נעליים" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">נעליים</h3>
                        <p class="text-gray-600 mb-4">גלו את המגוון הרחב של נעלי ספורט ויומיום.</p>
                        <a href="#" class="text-blue-600 hover:underline font-medium">צפו בקולקציה &rarr;</a>
                    </div>
                </div>
                <!-- קטגוריה: ביגוד -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden transform hover:scale-105 transition duration-300 ease-in-out">
                    <img src="https://placehold.co/400x250/444444/ffffff?text=ביגוד" alt="ביגוד" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">ביגוד</h3>
                        <p class="text-gray-600 mb-4">נוחות וסטייל לכל אימון וכל יום.</p>
                        <a href="#" class="text-blue-600 hover:underline font-medium">צפו בקולקציה &rarr;</a>
                    </div>
                </div>
                <!-- קטגוריה: אביזרים -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden transform hover:scale-105 transition duration-300 ease-in-out">
                    <img src="https://placehold.co/400x250/555555/ffffff?text=אביזרים" alt="אביזרים" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">אביזרים</h3>
                        <p class="text-gray-600 mb-4">השלימו את המראה עם אביזרי נייק.</p>
                        <a href="#" class="text-blue-600 hover:underline font-medium">צפו בקולקציה &rarr;</a>
                    </div>
                </div>
            </div>
        </section>

        <!-- מוצרים מומלצים -->
        <section class="mb-12">
            <h2 class="text-3xl font-bold text-center mb-8">מוצרים מומלצים</h2>
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
                <!-- מוצר 1 -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden p-4 transform hover:scale-105 transition duration-300 ease-in-out">
                    <!-- תמונת מוצר אמיתית -->
                    <img src="https://marketimg.marmelada.co.il/photos/thumbnails_1129_1000_detailed_2F6567_2FDH2987-101.jpg" onerror="this.src='https://placehold.co/300x200/666666/ffffff?text=Nike+Air+Max'" alt="Nike Air Max" class="w-full h-40 object-cover rounded-md mb-4">
                    <h3 class="text-lg font-semibold mb-1">נייק אייר מקס 270</h3>
                    <p class="text-gray-600 text-sm mb-2">נעלי ריצה נוחות במיוחד.</p>
                    <p class="text-xl font-bold text-gray-900">₪ 599</p>
                    <button class="btn-primary w-full text-sm py-2 px-4">הוספה לעגלה</button>
                </div>
                <!-- מוצר 2 -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden p-4 transform hover:scale-105 transition duration-300 ease-in-out">
                    <img src="https://marketimg.marmelada.co.il/photos/thumbnails_1129_1000_detailed_2F6567_2FDH2987-101.jpg" onerror="this.src='https://placehold.co/300x200/777777/ffffff?text=Nike+Dri-FIT'" alt="Nike Dri-FIT T-Shirt" class="w-full h-40 object-cover rounded-md mb-4">
                    <h3 class="text-lg font-semibold mb-1">חולצת דריי-פיט</h3>
                    <p class="text-gray-600 text-sm mb-2">נושמת וקלה לאימונים.</p>
                    <p class="text-xl font-bold text-gray-900">₪ 149</p>
                    <button class="btn-primary w-full text-sm py-2 px-4">הוספה לעגלה</button>
                </div>
                <!-- מוצר 3 -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden p-4 transform hover:scale-105 transition duration-300 ease-in-out">
                    <img src="https://marketimg.marmelada.co.il/photos/thumbnails_1129_1000_detailed_2F6567_2FDH2987-101.jpg" onerror="this.src='https://placehold.co/300x200/888888/ffffff?text=Nike+Leggings'" alt="Nike Leggings" class="w-full h-40 object-cover rounded-md mb-4">
                    <h3 class="text-lg font-semibold mb-1">טייץ נייק לנשים</h3>
                    <p class="text-gray-600 text-sm mb-2">גמיש ותומך לכל פעילות.</p>
                    <p class="text-xl font-bold text-gray-900">₪ 249</p>
                    <button class="btn-primary w-full text-sm py-2 px-4">הוספה לעגלה</button>
                </div>
                <!-- מוצר 4 -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden p-4 transform hover:scale-105 transition duration-300 ease-in-out">
                    <img src="https://marketimg.marmelada.co.il/photos/thumbnails_1129_1000_detailed_2F6567_2FDH2987-101.jpg" onerror="this.src='https://placehold.co/300x200/999999/ffffff?text=Nike+Cap'" alt="Nike Cap" class="w-full h-40 object-cover rounded-md mb-4">
                    <h3 class="text-lg font-semibold mb-1">כובע נייק קלאסי</h3>
                    <p class="text-gray-600 text-sm mb-2">הגנה מהשמש בסטייל.</p>
                    <p class="text-xl font-bold text-gray-900">₪ 89</p>
                    <button class="btn-primary w-full text-sm py-2 px-4">הוספה לעגלה</button>
                </div>
            </div>
        </section>

        <!-- הרשמה לניוזלטר / קריאה לפעולה -->
        <section class="bg-gray-800 text-white p-8 rounded-lg text-center shadow-lg">
            <h2 class="text-3xl font-bold mb-4">הצטרפו לקהילת נייק</h2>
            <p class="mb-6 max-w-xl mx-auto">
                קבלו עדכונים על השקות חדשות, מבצעים בלעדיים וסיפורים מעוררי השראה ישירות לתיבת הדואר שלכם.
            </p>
            <form class="flex flex-col sm:flex-row justify-center items-center gap-4">
                <input type="email" placeholder="הכנס כתובת אימייל" class="p-3 rounded-full border border-gray-600 focus:outline-none focus:ring-2 focus:ring-blue-500 text-gray-900 w-full sm:w-auto flex-grow max-w-sm">
                <button type="submit" class="btn-secondary w-full sm:w-auto">
                    הירשמו עכשיו
                </button>
            </form>
        </section>
    </main>

    <!-- פוטר (Footer) -->
    <footer class="bg-gray-900 text-gray-300 p-8 mt-12 rounded-t-lg">
        <div class="container mx-auto grid grid-cols-1 md:grid-cols-4 gap-8">
            <!-- עמודות קישורים -->
            <div>
                <h4 class="text-white text-lg font-semibold mb-4">עזרה</h4>
                <ul>
                    <li class="mb-2"><a href="#" class="hover:underline">סטטוס הזמנה</a></li>
                    <li class="mb-2"><a href="#" class="hover:underline">משלוחים</a></li>
                    <li class="mb-2"><a href="#" class="hover:underline">החזרות והחלפות</a></li>
                    <li class="mb-2"><a href="#" class="hover:underline">אפשרויות תשלום</a></li>
                    <li class="mb-2"><a href="#" class="hover:underline">צור קשר</a></li>
                </ul>
            </div>
            <div>
                <h4 class="text-white text-lg font-semibold mb-4">אודות נייק</h4>
                <ul>
                    <li class="mb-2"><a href="#" class="hover:underline">חדשות</a></li>
                    <li class="mb-2"><a href="#" class="hover:underline">קריירה</a></li>
                    <li class="mb-2"><a href="#" class="hover:underline">משקיעים</a></li>
                    <li class="mb-2"><a href="#" class="hover:underline">קיימות</a></li>
                </ul>
            </div>
            <div>
                <h4 class="text-white text-lg font-semibold mb-4">הצטרפו אלינו</h4>
                <ul>
                    <li class="mb-2"><a href="#" class="hover:underline">Nike App</a></li>
                    <li class="mb-2"><a href="#" class="hover:underline">Nike Run Club</a></li>
                    <li class="mb-2"><a href="#" class="hover:underline">Nike Training Club</a></li>
                    <li class="mb-2"><a href="#" class="hover:underline">SNKRS</a></li>
                </ul>
            </div>
            <!-- מדיה חברתית -->
            <div>
                <h4 class="text-white text-lg font-semibold mb-4">עקבו אחרינו</h4>
                <div class="flex space-x-4 text-white text-2xl">
                    <!-- אייקוני מדיה חברתית -->
                    <a href="#" class="hover:text-blue-500 transition duration-300"><img src="https://placehold.co/24x24/ffffff/000000?text=F" alt="פייסבוק" class="rounded-full"></a>
                    <a href="#" class="hover:text-blue-500 transition duration-300"><img src="https://placehold.co/24x24/ffffff/000000?text=I" alt="אינסטגרם" class="rounded-full"></a>
                    <a href="#" class="hover:text-blue-500 transition duration-300"><img src="https://placehold.co/24x24/ffffff/000000?text=X" alt="טוויטר" class="rounded-full"></a>
                    <a href="#" class="hover:text-blue-500 transition duration-300"><img src="https://placehold.co/24x24/ffffff/000000?text=Y" alt="יוטיוב" class="rounded-full"></a>
                </div>
            </div>
        </div>
        <div class="border-t border-gray-700 mt-8 pt-8 text-center text-gray-500 text-sm">
            <p>&copy; 2025 Nike, Inc. כל הזכויות שמורות.</p>
            <div class="flex justify-center space-x-4 mt-2">
                <a href="#" class="hover:underline">מדיניות פרטיות</a>
                <a href="#" class="hover:underline">תנאי שימוש</a>
                <a href="#" class="hover:underline">מפות אתר</a>
            </div>
        </div>
    </footer>
</body>
</html>
