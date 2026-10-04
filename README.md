# پلنر من (Planner Man)

اپلیکیشن اندروید شخصی برنامه‌ریزی روزانه/هفتگی برای آمادگی کنکور.

- **Package ID:** `com.roya.planner`
- **نام اپ:** پلنر من
- ساخته‌شده با Capacitor 6 + همان HTML/CSS/JS اصلی (بدون تغییر طراحی)

## ساخت APK با GitHub Actions

۱. این مخزن را روی GitHub بسازید و فایل‌ها را آپلود کنید.
۲. به تب **Actions** بروید و workflow **Build Android APK** را اجرا کنید.
۳. پس از اتمام، از بخش Artifacts فایل `planner-man-apk` را دانلود کنید.

راهنمای کامل قدم‌به‌قدم برای مبتدیان در فایل `INSTRUCTIONS-FA.md` آمده است.

## ساختار

```
planner-app/
├── www/                 # محتوای وب (index.html + فونت‌ها + آیکون‌ها)
├── capacitor.config.json
├── package.json
├── .github/workflows/build-apk.yml
└── README.md
```

پس از `npx cap add android` پوشه `android/` ساخته می‌شود (در Actions خودکار انجام می‌شود).
