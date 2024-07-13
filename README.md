
![Logo](https://i.postimg.cc/c4FcFPRd/image.png)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/) [![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/) [![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)


# نهضة | منصة تبادل خبرات

## مقدمة  

مرحبًا بكم في نهضة - منصة لتبادل الخبرات بين المبرمجين. توفر منصة نهضة للمستخدمين إمكانية نشر الدورات التدريبية والشروحات للأدوات والتقنيات ولغات البرمجة الجديدة، مما يتيح لهم تبادل الخبرات والتواصل مع مجتمع مفتوح من المبرمجين. بالإضافة إلى ذلك، تحتوي المنصة على مكتبة شاملة للكتب التقنية باللغة العربية.


## مميزات رئيسية

نشر الدورات التدريبية: يمكن للمستخدمين نشر دورات تدريبية وشروحات للأدوات والتقنيات ولغات البرمجة الجديدة.

مجتمع مفتوح: تتيح المنصة التواصل بين المبرمجين وتبادل الأسئلة والخبرات.

مكتبة كتب تقنية: تحتوي المنصة على مكتبة واسعة من الكتب التقنية باللغة العربية.
## كيف تبدأ

**المتطلبات:**

PHP (الإصدار 8.0 أو أحدث)

Composer

Laravel (الإصدار 11)



## التثبيت

**استنساخ المستودع:**

```bash
  git clone https://github.com/izzeldeenn/nahda.git
```

**الدخول إلى دليل المشروع:**

```bash
  cd nahda
```

**تثبيت التبعيات:**

```bash
  composer install
```

**إنشاء ملف إعدادات البيئة:**

```bash
  cp .env.example .env
```

**توليد مفتاح التطبيق:**

```bash
 php artisan key:generate
```
**إعداد قاعدة البيانات:**

قم بتحديث ملف .env بمعلومات قاعدة البيانات الخاصة بك، ثم قم بتشغيل الأوامر التالية لتشغيل الترحيلات والبذور:

```bash
 php artisan migrate --seed
```
**تشغيل الخادم المحلي:**

```bash
 php artisan serve
```
## المساهمة
نرحب بجميع المساهمات من المطورين المهتمين بتحسين وتطوير المنصة. لبدء المساهمة، يرجى اتباع الخطوات التالية

**تفريع (Fork) المستودع:**

**إنشاء فرع جديد للتعديلات:**

```bash
  git checkout -b feature/اسم-الميزة
```
**تنفيذ التعديلات ودفعها إلى الفرع الجديد:**

```bash
git add .
git commit -m "إضافة ميزة جديدة: اسم الميزة"
git push origin feature/اسم-الميزة

```
**فتح طلب سحب (Pull Request) للمراجعة:**


## الدعم

إذا كان لديك أي أسئلة أو تحتاج إلى دعم، يرجى التواصل معي عبر izzeldeennasser9@gmail.com 


## تواصل معي

البريد الإلكتروني: izzeldeennasser9@gmail.com 



## الرخصة
يتم توزيع هذا المشروع تحت رخصة MIT. راجع ملف [licenses](https://choosealicense.com/licenses/mit/) لمزيد من المعلومات.

