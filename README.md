# First Show - متجر إلكتروني وهمي

هذا المشروع عبارة عن نسخة وهمية (Front-End فقط) تحاكي متجر firstshow1.com من حيث التصميم وسلوك المستخدم، دون الحاجة إلى قاعدة بيانات أو خادم (Back-End).

## 🚀 ميزات المشروع

- تصميم متجاوب يعمل على جميع أحجام الشاشات
- واجهة مستخدم سهلة الاستخدام وجذابة
- سلة تسوق تعمل باستخدام localStorage
- عرض المنتجات من ملفات JSON
- صفحات متعددة: الرئيسية، تفاصيل المنتج، السلة، من نحن، اتصل بنا، سياسة الشحن
- تأثيرات وانتقالات بصرية جذابة

## 🛠️ التقنيات المستخدمة

- HTML5
- Tailwind CSS
- CSS3
- JavaScript (Vanilla)
- Alpine.js
- Swiper.js
- SweetAlert2
- FontAwesome
- localStorage
- JSON

## 📁 هيكل المشروع

```
tifstore/
├── index.html                # الصفحة الرئيسية
├── product.html              # صفحة تفاصيل المنتج
├── cart.html                 # صفحة سلة التسوق
├── about.html                # صفحة من نحن
├── contact.html              # صفحة اتصل بنا
├── shipping-policy.html      # صفحة سياسة الشحن
├── assets/
│   ├── css/
│   │   └── style.css         # ملف CSS مخصص
│   ├── js/
│   │   ├── main.js           # وظائف JavaScript المشتركة
│   │   ├── cart.js           # وظائف سلة التسوق
│   │   ├── product.js        # وظائف صفحة المنتج
│   │   └── index.js          # وظائف الصفحة الرئيسية
│   └── img/                  # صور المنتجات والشعار
└── data/
    ├── products.json         # بيانات المنتجات
    └── categories.json       # بيانات التصنيفات
```

## 🚦 كيفية تشغيل المشروع

1. قم بتثبيت خادم ويب محلي مثل XAMPP أو WAMP أو أي خادم HTTP آخر.
2. انسخ مجلد المشروع إلى مجلد `htdocs` (في حالة XAMPP) أو `www` (في حالة WAMP).
3. قم بتشغيل الخادم المحلي.
4. افتح المتصفح وانتقل إلى `http://localhost/tifstore`.

## 📱 الوظائف الرئيسية

### الصفحة الرئيسية
- عرض السلايدر الرئيسي
- عرض التصنيفات الرئيسية
- عرض المنتجات المميزة
- عرض منتجات العروض والخصومات
- مميزات المتجر (شحن مجاني، استرجاع، دعم 24/7)

### صفحة المنتج
- عرض صور المنتج في معرض صور
- تفاصيل المنتج (الاسم، السعر، التقييم، الوصف)
- اختيار اللون والمقاس والكمية
- إضافة المنتج للسلة
- عرض منتجات مشابهة

### سلة التسوق
- عرض المنتجات المضافة للسلة
- تعديل الكمية وحذف المنتجات
- إدخال كود خصم
- حساب المجموع والشحن والخصم والإجمالي

## 📝 ملاحظات هامة

- هذا المشروع وهمي ولا يحتوي على قاعدة بيانات فعلية.
- جميع العمليات مثل "شراء الآن" أو "إرسال النموذج" ستؤدي لرسائل تنبيه وهمية فقط.
- المشروع مناسب للعرض التفاعلي أو النماذج الأولية (Prototype).
- يتم تخزين بيانات السلة محليًا في متصفح المستخدم باستخدام localStorage.

## 👨‍💻 تطوير المشروع

إذا كنت ترغب في تطوير المشروع، يمكنك:

1. إضافة المزيد من الصفحات والوظائف.
2. تحسين تجربة المستخدم وواجهة المستخدم.
3. إضافة المزيد من التأثيرات والانتقالات.
4. ربط المشروع بقاعدة بيانات حقيقية وإضافة وظائف الخادم (Back-End).

## 📄 الترخيص

هذا المشروع مخصص للأغراض التعليمية والعرض فقط.