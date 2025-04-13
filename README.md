📄 README.md
markdown
Copy
Edit
# 📱 Login System - PHP & MySQL

نظام تسجيل دخول متكامل باستخدام **PHP** و **MySQL**.

## 📌 وصف المشروع  
هذا المشروع عبارة عن نظام بسيط وآمن لإدارة:
- ✅ تسجيل الدخول
- ✅ تسجيل حساب جديد
- ✅ استعادة كلمة المرور
- ✅ تسجيل الخروج
- ✅ لوحة تحكم للمستخدم

## 🗂️ مكونات المشروع  

### 📁 صفحات HTML
- `index.html` : صفحة تسجيل الدخول  
- `register.html` : صفحة إنشاء حساب جديد  
- `reset_password.html` : صفحة استعادة كلمة المرور  

### 📁 ملفات PHP
- `db.php` : ملف الاتصال بقاعدة البيانات  
- `login.php` : التحقق من بيانات المستخدم  
- `register.php` : تسجيل مستخدم جديد  
- `reset_password.php` : إرسال تعليمات استعادة كلمة المرور  
- `logout.php` : تسجيل الخروج  
- `dashboard.php` : الصفحة المحمية بعد تسجيل الدخول  

## 🛠️ المتطلبات  
- **PHP 7+**
- **MySQL Server (مثلاً XAMPP أو MAMP)**
- متصفح حديث (Chrome / Edge)

## ⚙️ طريقة التشغيل

1. شغّل سيرفر محلي (XAMPP أو MAMP)
2. انسخ ملفات المشروع داخل مجلد `htdocs`
3. قم بإنشاء قاعدة بيانات باسم `login_system` (أو أي اسم آخر مع تعديله في `db.php`)
4. أنشئ جدول المستخدمين بداخلها مثل:
   ```sql
   CREATE TABLE users (
       id INT AUTO_INCREMENT PRIMARY KEY,
       username VARCHAR(100) NOT NULL,
       email VARCHAR(100) NOT NULL UNIQUE,
       password VARCHAR(255) NOT NULL
   );
افتح الرابط:

arduino
Copy
Edit
http://localhost/index.html
🎨 المميزات
تصميم عصري متجاوب يدعم الوضع الداكن والفاتح

تحقق من الحقول وظهور رسائل تنبيه بشكل فوري

إمكانية إظهار/إخفاء كلمة المرور

نظام استعادة كلمة مرور متكامل

👨‍💻 المطور
اسم: يوسف النحاس

البريد: DEV.ALNAHAS@GMAIL.COM

GitHub:https://github.com/Alna7as/
