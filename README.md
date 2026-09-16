# 📊 README - راهنمای فنی و معماری گزارش نقد پروژه تحلیل داده

این پروژه یک **گزارش نقد فنی و حرفه‌ای (Data Analysis Review Report)** است که برای ارزیابی نوت‌بوک تحلیل داده‌های بیمه طراحی شده است. این سند تک‌فایلی (`index.html`) با بهره‌گیری از تکنولوژی‌های اصیل وب (**HTML5 / CSS3 / Vanilla JavaScript**) پیاده‌سازی شده و تمامی استانداردهای مدرن **UI/UX**، **دسترسی‌پذیری (Accessibility)**، **روانشناسی رنگ‌ها** و **بهینه‌سازی چاپ** را رعایت کرده است.

---

## 📑 فهرست مطالب

1. [ویژگی‌های کلیدی پروژه](#1-ویژگیهای-کلیدی-پروژه)
2. [معماری و ساختار فنی](#2-معماری-و-ساختار-فنی)
3. [تحلیل روانشناسی رنگ‌ها (Color Psychology)](#3-تحلیل-روانشناسی-رنگها-color-psychology)
4. [تشریح دقیق بخش‌های HTML](#4-تشریح-دقیق-بخشهای-html)
5. [تشریح CSS3 و طراحی استایل‌ها](#5-تشریح-css3-و-طراحی-استایلها)
6. [تشریح Vanilla JavaScript و قابلیت‌های تعاملی](#6-تشریح-vanilla-javascript-و-قابلیتهای-تعاملی)
7. [طراحی اختصاصی جهت چاپ و خروجی PDF](#7-طراحی-اختصاصی-جهت-چاپ-و-خروجی-pdf)
8. [نحوه اجرا و توسعه](#8-نحوه-اجرا-و-توسعه)

---

## ۱. ویژگی‌های کلیدی پروژه

* **Single-File Architecture:** تمام کدها (HTML, CSS, JS) داخل یک فایل متمرکز `index.html` قرار دارند، بدون هیچ‌گونه وابستگی به کتابخانه‌ها یا فریم‌ورک‌های خارجی (No Dependencies).
* **کدبلاک‌های استاندارد LTR:** نمایش کدهای پایتون و خروجی‌های برنامه‌نویسی به‌صورت چپ‌به‌راست (`direction: ltr`) با فونت‌های اختصاصی تک‌فاصله (`Fira Code`, `Consolas`).
* **دکمه کپی هوشمند:** هر بلوک کد دارای دکمه اختصاصی برای کپی در حافظه (Clipboard) با ارائه بازخورد بصری به کاربر است.
* **داشبورد ارزیابی و ماتریس امتیازات:** نمایش گرافیکی امتیاز کل (۹۱ / ۱۰۰)، سطح پروژه، و جدول تفکیکی معیارها با طراحی مدرن کارت‌محور.
* **تایپوگرافی و فونت استاندار فارسی:** استفاده از فونت محبوب `Vazirmatn` جهت بیشترین خوانایی در اندازه‌های مختلف صفحه.
* **کارت قدردانی ویژه:** کارت انتهای صفحه با تم سبز زمردی جنگلی، همراه با لینک مستقیم به مخزن گیت‌هاب پروژه.
* **دکمه بازگشت به بالا (Back to Top):** نمایش شناور و هوشمند هنگام اسکرول به پایین.
* **پرینت هوشمند (`@media print`):** مخفی‌سازی عناصر تعاملی (دکمه‌ها) و بهینه‌سازی فاصله‌ها جهت چاپ روی کاغذ A4 یا خروجی PDF.

---

## ۲. معماری و ساختار فنی

پروژه بر پایه معماری سه‌لایه اصیل وب پیاده‌سازی شده است:

```text
index.html
├── HTML5 Structure (Semantic Markup & RTL Layout)
├── CSS3 Internal Styles (<style>)
│   ├── CSS Custom Properties (Variables)
│   ├── Base & Reset Rules
│   ├── Typography & Direction Controls
│   ├── Card Components & Code Blocks
│   └── @media print Optimization
└── JavaScript (<script>)
    ├── Smooth Scroll Logic
    ├── Code Copy Mechanism
    └── Back to Top Floating Button
```

---

## ۳. تحلیل روانشناسی رنگ‌ها (Color Psychology)

رنگ‌بندی این گزارش بر اساس اصول **Data Analytics Psychology** انتخاب شده است تا در کنار جذابیت بصری، احساس دقت، اعتماد، و ارزیابی عادلانه دانشگاهی را به مخاطب منتقل کند:

| کد رنگ | نام رنگ | نقش در رابط کاربری | روانشناسی و علت انتخاب |
| :--- | :--- | :--- | :--- |
| `#0f172a` | Deep Executive Slate | هدر، عناوین اصلی، کدبلاک‌ها | ایجاد حس اقتدار، دقت علمی، تمرکز و ساختاریافتگی |
| `#f8fafc` | Pure Off-White | پس‌زمینه اصلی صفحه | کاهش خستگی چشم هنگام مطالعه متون طولانی |
| `#0d9488` | Teal Emerald | نشان‌ها، هایلایت‌ها و تاکیدها | القای حس سلامت داده، ثبات و تصمیم‌گیری درست |
| `#f59e0b` | Amber Gold | نشان امتیاز (۹۱) و مدال‌ها | جلب توجه هوشمندانه، نشان‌دهنده کیفیت ممتاز پروژه |
| `#e11d48` | Soft Crimson | باگ‌ها و ایرادهای اولویت‌دار | ایجاد هشداری دوستانه جهت اصلاح بدون ایجاد حس تهاجمی |
| `#064e3b` | Forest Gradient | کارت تقدیر پایانی | ایجاد حس انرژی مثبت، صمیمیت و قدردانی پایدار از سازنده پروژه |

---

## ۴. تشریح دقیق بخش‌های HTML

عناصر HTML به‌صورت کاملاً معنایی (Semantic HTML5) جهت خوانایی عالی و سئو تنظیم شده‌اند:

1. **`header.app-header`:**
   * حاوی اطلاعات شناسنامه سند (عنوان گزارش، نقد کننده: محمد رضائی، نقد شونده: علی خان‌بیگی).
   * دارای طراحی Gradient از طیف سورمه‌ای تا فیروزه‌ای.
2. **`section.hero-score-card`:**
   * نمایش خلاصه مدیریتی شامل **امتیاز ۹۱ / ۱۰۰** و **سطح پروژه (بسیار خوب)**.
   * باکس‌های دوگانه "مهم‌ترین نقطه قوت" (سبز) و "مهم‌ترین ایراد" (قرمز).
3. **`section.score-matrix`:**
   * جدول زیبا و پاسخ‌گو (Responsive Table) تفکیک امتیازها از معیارهای ۶ گانه (ساختار، کیفیت کد، پاکسازی، EDA، مصورسازی، Insight).
4. **`main.report-content`:**
   * بدنه اصلی گزارش شامل بخش‌های نقاط قوت، ایرادها، بررسی ساختار، کیفیت پایتون، EDA، پاکسازی داده، مصورسازی و موارد مورد توجه استاد.
   * استفاده از تگ‌های `<pre><code class="language-python">` برای تمامی بخش‌های کد.
5. **`footer.app-footer`:**
   * کارت قدردانی ویژه از علی خان‌بیگی همراه با آیکون و لینک مستقیم به ریپازیتوری GitHub.

---

## ۵. تشریح CSS3 و طراحی استایل‌ها

### الف) تنظیم متغیرهای جهانی (CSS Variables)
در ابتدای کدهای CSS تمام رنگ‌ها و اندازه‌ها به‌صورت متغیر تعریف شده‌اند تا تغییر تم در آینده به‌راحتی امکان‌پذیر باشد:

```css
:root {
    --primary: #0f172a;
    --primary-light: #1e293b;
    --accent: #0d9488;
    --accent-light: #ccfbf1;
    --warning: #f59e0b;
    --danger: #e11d48;
    --bg-main: #f8fafc;
    --card-bg: #ffffff;
    --text-main: #1e293b;
    --text-muted: #64748b;
    --font-sans: 'Vazirmatn', sans-serif;
    --font-code: 'Fira Code', 'Consolas', monospace;
}
```

### ب) چپ‌چین کردن کدهای پایتون (LTR Force)
یکی از چالش‌های اصلی صفحات فارسی (RTL)، نمایش درست کدها است. با استفاده از قوانین زیر، تمامی بخش‌های کد به‌صورت اجباری چپ‌چین و راست‌به‌چپ تنظیم می‌شوند:

```css
pre, code, .code-block, [dir="ltr"] {
    direction: ltr !important;
    text-align: left !important;
    unicode-bidi: embed;
}

pre {
    background-color: #0f172a;
    color: #e2e8f0;
    padding: 1.25rem;
    border-radius: 0.75rem;
    font-family: var(--font-code);
    font-size: 0.9rem;
    line-height: 1.6;
    overflow-x: auto; /* ایجاد اسکرول افقی در کد طولانی */
    position: relative;
}
```

---

## ۶. تشریح Vanilla JavaScript و قابلیت‌های تعاملی

کدهای جاوااسکریپت بدون هیچ وابستگی خارجی عملکرد روان صفحه را تضمین می‌کنند:

### الف) مکانیسم کپی کدهای پایتون
با کلیک روی دکمه "کپی کد"، متن داخل تگ `<code>` استخراج شده و در Clipboard ذخیره می‌شود:

```javascript
document.querySelectorAll('.copy-btn').forEach(button => {
    button.addEventListener('click', () => {
        const pre = button.parentElement;
        const code = pre.querySelector('code');
        const text = code.innerText;

        navigator.clipboard.writeText(text).then(() => {
            button.textContent = 'کپی شد! ✓';
            button.classList.add('copied');
            setTimeout(() => {
                button.textContent = 'کپی کد';
                button.classList.remove('copied');
            }, 2000);
        });
    });
});
```

### ب) دکمه شناور بازگشت به بالا (Back to Top)
کنترل نمایش دکمه تنها در صورت اسکرول شدن صفحه بیش از ۳۰۰ پیکسل:

```javascript
const backToTopBtn = document.getElementById('backToTop');

window.addEventListener('scroll', () => {
    if (window.scrollY > 300) {
        backToTopBtn.classList.add('visible');
    } else {
        backToTopBtn.classList.remove('visible');
    }
});

backToTopBtn.addEventListener('click', () => {
    window.scrollTo({
        top: 0,
        behavior: 'smooth'
    });
});
```

---

## ۷. طراحی اختصاصی جهت چاپ و خروجی PDF

برای تبدیل این صفحه به خروجی PDF یا پرینت فیزیکی بدون بهم‌ریختگی، دستورات `@media print` اختصاصی درج شده است:

```css
@media print {
    body {
        background: #fff !important;
        color: #000 !important;
    }
    .copy-btn, #backToTop, .no-print {
        display: none !important; /* مخفی‌سازی دکمه‌های غیرضروری */
    }
    .card, pre {
        page-break-inside: avoid; /* جلوگیری از شکستن کارت‌ها در میان صفحات */
        box-shadow: none !important;
        border: 1px solid #ddd !important;
    }
}
```

---

## ۸. نحوه اجرا و توسعه

1. فایل `index.html` را دانلود کرده یا در سیستم خود ذخیره کنید.
2. روی فایل دوبار کلیک کنید یا آن را در هر مرورگر دلخواهی (Chrome, Firefox, Edge, Safari) باز کنید.
3. جهت ویرایش یا شخصی‌سازی، فایل را در محیط **VS Code** یا هر ویرایشگر متن دیگری باز کرده و تغییرات خود را اعمال نمایید.

---
**توسعه داده شده با ❤️ برای ارزیابی حرفه‌ای پروژه‌های داده**
