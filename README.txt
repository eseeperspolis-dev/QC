QC App - راهنمای انتشار روی GitHub Pages
1) در github.com یک مخزن (Repository) عمومی بسازید، مثلاً qc-app
2) همه فایل‌های این پوشه (index.html, sw.js, manifest.webmanifest و پوشه icons) را در ریشه مخزن آپلود کنید
3) Settings > Pages > Source: Deploy from a branch > Branch: main و پوشه / (root) > Save
4) بعد از چند دقیقه آدرس https://USERNAME.github.io/qc-app/ فعال می‌شود
5) یک بار با اینترنت باز کنید؛ از آن به بعد بدون اینترنت هم کار می‌کند
6) روی موبایل: Add to Home Screen (اندروید: Install app)
نکته: با هر تغییر در فایل‌ها، عدد qc-v1 در sw.js را افزایش دهید (qc-v2 ...) تا نسخه جدید روی گوشی‌ها به‌روز شود.
