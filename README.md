# social-osint-tool
Python scripts for OSINT and Security Testing"
# Social OSINT Tool | أداة جمع المعلومات (OSINT)

## 📌 Overview | نظرة عامة
A Python-based Open Source Intelligence (OSINT) tool designed to check the availability of a specific username across multiple social media platforms. It uses multithreading for fast results and supports proxy integration to bypass rate limits.

أداة مبنية بلغة بايثون لجمع المعلومات المفتوحة المصدر (OSINT). تقوم بفحص اسم مستخدم (Username) معين عبر أكثر من 12 منصة سوشل ميديا. الأداة تستخدم تعدد المسارات (Multithreading) لسرعة البحث، وتدعم استخدام البروكسي لتجنب الحظر.

## 🚀 Features | الميزات
- **Fast Scanning:** Uses `concurrent.futures` for multithreaded requests.
- **Proxy Support:** Integrates with HTTP/SOCKS proxies.
- **Colorized Output:** Clear terminal output using `colorama`.
- **Wide Coverage:** Checks 12+ platforms (Instagram, TikTok, Twitter, GitHub, etc.).

- **فحص سريع:** استخدام تعدد المسارات (Multithreading) لفحص المنصات في وقت واحد.
- **دعم البروكسي:** يمكن ربط الأداة ببروكسي لتجنب حظر الـ IP.
- **مخرجات ملونة:** عرض النتائج في الطرفية بشكل واضح ومنظم.
- **تغطية واسعة:** فحص أكثر من 12 منصة تواصل اجتماعي.

## ⚙️ Requirements | المتطلبات
- Python 3.8+
- `requests`
- `colorama`

## 🛠️ Installation | التثبيت
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/social-osint-tool.git
   cd social-osint-tool
   
