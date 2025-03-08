<!DOCTYPE html>
 <html lang="ar" dir="rtl">
 <head>
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>رمضان في مدرسة الحياة - Oran</title>
   <link rel="stylesheet" href="styles.css">
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
   <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap">
   <script src="script.js"></script>
 </head>
 <body>
   <header>
     <div class="container">
 <img class="hayat" src="/home/a2m/Bureau/logo.png" ALT="" />
       <h1 id="header-title">مرحبًا بكم في مدرسة الحياة</h1>
       <button id="language-toggle">Français</button>
     </div>
   </header>
 
   <nav>
     <div class="container">
       <ul>
         <li><a href="index.html">الرئيسية</a></li>
         <li><a href="prayer-times.html">أوقات الصلاة</a></li>
         <li><a href="mosques.html">المساجد</a></li>
         <li><a href="advice.html">نصائح رمضانية</a></li>
         <li><a href="recipes.html">فئات متنوعة</a></li>
         <li><a href="contact.html">اتصل بنا</a></li>
       </ul>
     </div>
   </nav>
 
 
   <main>
     <section id="home" class="section">
       <div class="container">
         <h2>رمضان كريم</h2>
         <p>موقع شامل لكل ما يتعلق برمضان في وهران.</p>
       </div>
     </section>
 
     <section id="prayer-times" class="section">
       <div class="container">
         <h2 id="prayer-times-title">أوقات الصلاة</h2>
         <ul id="prayer-list">
           <li>الفجر: <span id="fajr-time">--:--</span></li>
           <li>الظهر: <span id="dhuhr-time">--:--</span></li>
           <li>العصر: <span id="asr-time">--:--</span></li>
           <li>المغرب: <span id="maghrib-time">--:--</span></li>
           <li>العشاء: <span id="isha-time">--:--</span></li>
         </ul>
       </div>
     </section>
 
     <section id="mosques" class="section">
       <div class="container">
         <h2 id="mosques-title">المساجد</h2>
         <ul id="mosques-list"></ul>
       </div>
     </section>
 
     <section id="advice" class="section">
       <div class="container">
         <h2 id="advice-title">نصائح رمضانية</h2>
         <p>نصائح مفيدة لصيام صحي ومثمر.</p>
       </div>
     </section>
 
     <section id="contact" class="section">
       <div class="container">
         <h2 id="contact-title">اتصل بنا</h2>
         <form id="contact-form">
           <input type="text" id="name" placeholder="اسمك" required>
           <input type="email" id="email" placeholder="بريدك الإلكتروني" required>
           <textarea id="message" placeholder="رسالتك" required></textarea>
           <button type="submit">إرسال</button>
         </form>
       </div>
     </section>
   </main>
 
   <footer>
     <div class="container">
       <p>© 2025 موقع رمضان. جميع الحقوق محفوظة.</p>
     </div>
   </footer>
 
   <script src="script.js"></script>
 </body>
 </html>
