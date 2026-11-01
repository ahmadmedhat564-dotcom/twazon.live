# توازن | Tawazon

تطبيق ويب (PWA) بالعربي والإنجليزي: خطة يوم، تسجيل أكل (186 أكلة + إضافة أكلة جديدة)، وتمارين متحركة.
A bilingual (AR/EN) PWA: daily plan, food logging with custom foods, animated workouts.

## التشغيل المحلي / Run locally
    python3 -m http.server 8080   # ثم افتح http://localhost:8080

## النشر على GitHub Pages / Deploy
1. ارفع كل الملفات في هذا المجلد على repo جديد.
2. Settings → Pages → Branch: main / root → Save.
3. افتح الرابط من الموبايل واختر "Add to Home Screen" لتثبيته كتطبيق.

## ملاحظات / Notes
- الحسابات وبيانات المستخدم محفوظة في `localStorage` على الجهاز فقط، وهي ليست نظام تسجيل دخول آمن.
- الخطوط: Cairo للعربي وMontserrat للإنجليزي (من Google Fonts).

## بناء ملف APK
Actions ← Build Android APK ← Run workflow، وبعد ما يخلص نزّل tawazon-apk من Artifacts.
