# ساخت APK نصب‌شدنی Elaros

## روش ۱: روی کامپیوتر خودت (Node 18+ ، JDK 17 و Android Studio/SDK)
    npm install
    npx cap add android
    npm run apk
فایل خروجی: android/app/build/outputs/apk/debug/app-debug.apk

## روش ۲: بدون نصب ابزار (GitHub Actions)
۱. یک مخزن خصوصی در GitHub بساز و کل این پوشه را push کن.
۲. به تب Actions برو، workflow به نام «Build APK» اجرا می‌شود.
۳. بعد از چند دقیقه، فایل elaros-apk (شامل app-debug.apk) را از بخش Artifacts دانلود کن.

برای نصب روی گوشی، نصب از «منبع ناشناس» را فعال کن.
