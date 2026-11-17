# صفحة ويب ChickCount

صفحة هبوط احترافية للتطبيق — ملف واحد `index.html` + فولدر `screenshots/` فيه لقطات التطبيق.

## الموقع المنشور

- **رابط الموقع:** https://mosalem-dev.github.io/chickcount-site/
- **الريبو:** https://github.com/mosalem-dev/chickcount-site
- **رابط الـ APK المباشر:** https://github.com/mosalem-dev/chickcount-site/releases/latest/download/ChickCount.apk
- ملف الـ APK مرفوع على **GitHub Releases** (مش جوه الريبو — GitHub بيرفض ملفات فوق 100MB في الريبو، والـ Releases بيقبل حتى 2GB).

## تحديث جديد (APK أو الصفحة)

1. **APK جديد:** انسخه مكان `web\ChickCount.apk` وبعدين:
   ```
   gh release upload v2.6 "web\ChickCount.apk" --repo mosalem-dev/chickcount-site --clobber
   ```
   الرابط المباشر مش بيتغير أبدًا — نفس اللينك يفضل شغال.
2. **تعديل الصفحة أو اللقطات:** عدّل `index.html` أو استبدل صور `screenshots/` بنفس الأسماء، وبعدين:
   ```
   git add -A; git commit -m "update"; git push
   ```
   Pages هتبني لوحدها خلال دقيقة.

## خطوات التثبيت عند المستخدم

نزّل الـ APK → اسمح بـ«مصادر غير معروفة» لو الجهاز سأل → افتح وابدأ.

## ملاحظات

- اللقطات دي فيها بيانات واسم وصور حقيقية — لو عايز تعتيم قبل نشر أوسع، استبدلها.
- إيموجي: ممنوع في الصفحة — كل الأيقونات SVG (ستايل Lucide/Feather).
