# IPTV Landing (KSA) — External
تسليم: ملف واحد `index.html` + جاهز للرفع على Vercel/Netlify.

## تعديل الروابط (مهم)
- استبدل جميع روابط المنتجات:
  - https://YOUR-STORE.COM/products/general
  - https://YOUR-STORE.COM/products/smarters
  - https://YOUR-STORE.COM/products/hulk
  - https://YOUR-STORE.COM/products/falcon

## Google Tag Manager (اختياري)
- فعل كود GTM الموجود في `<head>` وأدخل ID مكان `GTM-XXXXXX`.
- السكريبت يرسل حدث dataLayer باسم `select_product` عند الضغط على أي باقة.

## تمرير بارامترات الإعلان
- الكود يضيف تلقائيًا كل `gclid`/`utm_*` لرابط زر الشراء، لضمان تتبع المبيعات داخل المتجر.

## النشر السريع
- Vercel: أنشئ مشروع جديد واسحب `index.html` فقط.
- دومين مقترح: lp.yourdomain.com أو tv.yourdomain.com

تاريخ التوليد: 2025-09-02T22:21:08
