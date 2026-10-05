موقع هتغرب هنا
================
التشغيل:
1. فك الضغط.
2. افتح index.html في أي متصفح.

تعديل الشقق ورقم الواتساب:
- افتح index.html في Notepad أو VS Code.
- دوّر على السطر اللي فيه: <script type="application/json" id="data">
  فيه رقم الواتساب (whatsapp) وقائمة الشقق (flats).
- كل شقة بين { } وفيها: title, area, type, price, rooms, baths, floor,
  features, appliances, address, lat, lng, note, photos.
- الصور: حط الصور في فولدر img وكتب مسارها هنا:
  "photos":["img/flat1-1.jpg","img/flat1-2.jpg"]
- لازم تفضل الصيغة JSON سليمة (علامات الاقتباس والفواصل).

النشر على الإنترنت:
- ارفع الفولدر كله (index.html + img) على Netlify Drop أو GitHub Pages.

ملاحظة: زرار "لوحة الإدارة" بيشتغل بس على نسخة Claude المنشورة،
ومش بيظهر في النسخة دي. التعديل هنا بيتم يدوياً من الملف.
تسجيل الدخول في الموقع تجريبي ومحفوظ في متصفح كل زائر.
