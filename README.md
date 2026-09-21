# 📍 نقشه زنده من (PWA)

اپ PWA برای نمایش موقعیت لحظه‌ای روی نقشه. بدون نیاز به اینترنت، بدون VPN، بدون نصب اپ.

## 🚀 راه‌اندازی روی GitHub Pages

### مرحله ۱: مخزن بساز
1. برو به [github.com/new](https://github.com/new)
2. اسمش رو بذار مثلاً `live-map`
3. تیک **Add a README file** رو بزن
4. **Create repository**

### مرحله ۲: فایل‌ها رو آپلود کن
1. توی مخزن جدید، دکمه **Add file > Upload files** رو بزن
2. این ۴ فایل رو از ZIP بکش بیار توش:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon.svg`
3. دکمه **Commit changes** رو بزن

### مرحله ۳: GitHub Pages فعال کن
1. برو **Settings > Pages**
2. Source رو بذار روی **Deploy from a branch**
3. Branch: **main** و folder: **/(root)**
4. **Save** بزن
5. چند دقیقه صبر کن، یه URL بهت میده مثل:
   `https://username.github.io/live-map/`

### مرحله ۴: روی آیفون نصب کن
1. URL بالا رو توی Safari باز کن
2. دکمه **Share** (مربع با فلش) پایین رو بزن
3. **Add to Home Screen** رو بزن
4. اسمش رو بذار، **Add** کن

🎉 حالا یه آیکون روی صفحه داری مثل بقیه اپ‌ها!

## ✨ ویژگی‌ها
- 📍 GPS زنده با دقت بالا
- 🗺️ نقشه OpenStreetMap (رایگان، اوپن‌سورس)
- 📋 کپی مختصات با یک لمس
- 🔗 اشتراک‌گذاری لینک
- 🎯 نمایش دقت و ارتفاع
- 💫 UI شیشه‌ای iOS-style
- 📱 PWA - قابل نصب روی صفحه اصلی
- 🔌 آفلاین با Service Worker
- 🚫 بدون VPN، بدون اپ، بدون سرور

## 🛠️ تکنولوژی
- HTML5 + CSS3 + Vanilla JS
- Leaflet.js برای نقشه
- OpenStreetMap برای تایل‌ها
- Service Worker برای آفلاین
- Geolocation API برای GPS

## 📝 مجوز
MIT - استفاده آزاد
