# 🎓 دوره جامع علم داده با پایتون (Data Science with Python)

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Persian](https://img.shields.io/badge/Language-Persian-red.svg)]()

## 📖 درباره دوره

این مخزن شامل تمام مطالب، کدها، تمرین‌ها و پروژه‌های **دوره جامع علم داده با پایتون** است. دوره بر اساس کتاب مرجع **"Data Science Essentials in Python"** نوشته **Dmitry Zinoviev** طراحی شده و در ۱۲ جلسه آنلاین برگزار می‌شود.

### 🎯 هدف دوره
یادگیری عملی و پروژه‌محور علم داده از مفاهیم اولیه برنامه‌نویسی پایتون تا اجرای یک پروژه واقعی علم داده.

### 👨‍🏫 مدرس
**آراز شاه کرمی** - مدرس علم داده و پایتون

---

## 📚 سرفصل دوره

### جلسه 1: مقدمه و مفاهیم پایه علم داده
- آشنایی با علم داده و جایگاه آن
- چرخه کامل پروژه علم داده
- انواع داده‌ها و Data Acquisition Pipeline
- معرفی محیط کاری (Python، Jupyter، Google Colab)
- اولین تحلیل داده عملی

### جلسه 2: پایتون برای علم داده (Core Python)
- کار با رشته‌ها و ساختمان داده‌ها
- خواندن و نوشتن فایل‌ها
- دریافت داده از وب (`urllib`, `requests`)
- Regular Expressions
- Pickling & Unpickling

### جلسه 3: کار با داده متنی (Text Data)
- پردازش HTML با BeautifulSoup
- کار با CSV و JSON
- مقدمه‌ای بر پردازش زبان طبیعی (NLTK)
- پروژه: جمع‌آوری و تحلیل اخبار

### جلسه 4: کار با پایگاه داده‌ها (Databases)
- MySQL و اجرای کوئری‌ها
- MongoDB و داده‌های NoSQL
- اتصال Python به پایگاه‌داده

### جلسه 5: داده عددی و NumPy
- ایجاد و دستکاری آرایه‌ها
- Broadcasting و ufuncs
- Aggregation و Set operations

### جلسه 6: Pandas: Data Series & DataFrames
- کار با DataFrame و Series
- Reshaping, Pivot, Melt
- مدیریت داده‌های گمشده
- Merge/Join ترکیب داده‌ها

### جلسه 7: تحلیل شبکه (Network Analysis)
- مفاهیم گراف و NetworkX
- سنجش‌های مرکزیت و خوشه‌بندی
- پروژه: تحلیل شبکه اجتماعی

### جلسه 8: مصورسازی داده
- Matplotlib و انواع نمودار
- زیبا‌سازی و سفارشی‌سازی
- ترسیم مستقیم از Pandas

### جلسه 9: آمار و احتمال با پایتون
- توزیع‌های آماری و شاخص‌ها
- آزمون‌های آماری
- تحلیل همبستگی

### جلسه 10: یادگیری ماشین (Machine Learning)
- رگرسیون خطی (Linear Regression)
- K-Means Clustering
- Random Forest
- ارزیابی مدل

### جلسه 11-12: پروژه نهایی
- انتخاب و تعریف پروژه
- پیاده‌سازی کامل
- ارائه نتایج

---

## 🛠️ ابزارها و تکنولوژی‌ها

### زبان برنامه‌نویسی
- **Python 3.8+**

### کتابخانه‌های اصلی
- **NumPy** - محاسبات عددی
- **Pandas** - تحلیل داده‌های جدولی  
- **Matplotlib** - مصورسازی
- **Scikit-learn** - یادگیری ماشین
- **BeautifulSoup** - وب اسکرپینگ
- **NetworkX** - تحلیل شبکه
- **Requests** - HTTP requests

### پایگاه داده
- **MySQL** - پایگاه داده رابطه‌ای
- **MongoDB** - پایگاه داده NoSQL

### محیط‌های اجرایی
- **Jupyter Notebook**
- **Google Colab**

---

## 📁 ساختار مخزن

```
data-science-python-course/
│
├── sessions/                    # مطالب هر جلسه
│   ├── session-01/             # جلسه اول
│   │   ├── slides/             # اسلایدها
│   │   ├── notebooks/          # Jupyter Notebooks
│   │   ├── data/              # داده‌های نمونه
│   │   └── exercises/         # تمرین‌ها
│   ├── session-02/
│   └── ...
│
├── projects/                   # پروژه‌های دوره
│   ├── mini-projects/         # پروژه‌های کوچک
│   └── final-project/         # پروژه نهایی
│
├── datasets/                  # مجموعه داده‌های دوره
│   ├── raw/                   # داده‌های خام
│   ├── processed/             # داده‌های پردازش شده
│   └── external/              # داده‌های خارجی
│
├── resources/                 # منابع و مراجع
│   ├── books/                 # کتاب‌ها و مقالات
│   ├── cheatsheets/          # برگه‌های کمک سریع
│   └── links.md              # لینک‌های مفید
│
├── setup/                     # راه‌اندازی محیط
│   ├── installation.md       # راهنمای نصب
│   └── environment.yml       # محیط conda
│
├── requirements.txt           # کتابخانه‌های Python
├── LICENSE                    # مجوز استفاده
└── README.md                 # این فایل
```

---

## 🚀 نصب و راه‌اندازی

### پیش‌نیازها
- Python 3.8 یا بالاتر
- Git (برای کلون کردن مخزن)

### روش 1: استفاده از Conda (پیشنهادی)
```bash
# کلون کردن مخزن
git clone https://github.com/arazshah/Data-science-with-python.git
cd Data-science-with-python

# ایجاد محیط conda
conda env create -f setup/environment.yml
conda activate data-science-course

# راه‌اندازی Jupyter
jupyter notebook
```

### روش 2: استفاده از pip
```bash
# کلون کردن مخزن
git clone https://github.com/arazshah/Data-science-with-python.git
cd Data-science-with-python

# ایجاد محیط مجازی
python -m venv venv
source venv/bin/activate  # در Windows: venv\Scripts\activate

# نصب کتابخانه‌ها
pip install -r requirements.txt

# راه‌اندازی Jupyter
jupyter notebook
```

### روش 3: Google Colab
برای استفاده بدون نصب:
1. بروید به [Google Colab](https://colab.research.google.com/)
2. فایل‌های `.ipynb` را از مخزن آپلود کنید
3. کتابخانه‌های موردنیاز از قبل نصب شده‌اند

---

## 💻 نحوه استفاده

### برای دانشجویان دوره:
1. هر جلسه، پوشه مربوطه را بررسی کنید
2. ابتدا اسلایدها را مطالعه کنید
3. Notebook های آموزشی را اجرا کنید
4. تمرین‌ها را انجام دهید
5. در صورت سوال، Issue ایجاد کنید

### برای یادگیری خودآموز:
1. از جلسه اول شروع کنید
2. مطالب را به ترتیب دنبال کنید
3. تمرین‌ها را حتماً انجام دهید
4. پروژه‌های کوچک را پیاده‌سازی کنید

---

## 📊 پروژه‌های نمونه

### پروژه‌های کوچک:
- **تحلیل داده‌های فروش**: آنالیز ترندهای فروش ماهانه
- **اسکرپینگ اخبار**: جمع‌آوری و دسته‌بندی اخبار
- **تحلیل شبکه اجتماعی**: بررسی روابط در شبکه‌های اجتماعی

### پروژه نهایی:
**"تحلیل الگوهای تردد شهری"**
- جمع‌آوری داده‌های تردد
- پاک‌سازی و آماده‌سازی
- تحلیل الگوهای زمانی و مکانی
- مصورسازی تعاملی
- مدل پیش‌بینی تراکم

---

## 🤝 مشارکت

### نحوه مشارکت:
1. مخزن را Fork کنید
2. شاخه جدید ایجاد کنید (`git checkout -b feature/AmazingFeature`)
3. تغییرات را Commit کنید (`git commit -m 'Add some AmazingFeature'`)
4. به شاخه Push کنید (`git push origin feature/AmazingFeature`)
5. Pull Request ایجاد کنید

### انواع مشارکت:
- گزارش باگ‌ها
- پیشنهاد بهبودها
- اضافه کردن مثال‌های جدید
- ترجمه مطالب
- بهبود مستندات

---

## 📞 ارتباط و پشتیبانی

### راه‌های ارتباط:
- **ایمیل**: [araz.shah@gmail.com]
- **تلگرام**: [@arazshah]
- **LinkedIn**: [https://www.linkedin.com/in/araz-shahkarami/]

### گزارش مشکلات:
برای گزارش مشکلات فنی یا پیشنهادات، لطفاً [Issue جدید](../../issues) ایجاد کنید.

### سوالات متداول:
قبل از سوال، لطفاً [FAQ](resources/faq.md) را بررسی کنید.

---

## 🙏 تشکر و قدردانی

### منابع الهام:
- کتاب "Data Science Essentials in Python" - Dmitry Zinoviev
- دوره‌های Coursera و edX
- جامعه Python و کتابخانه‌های متن‌باز

### تشکر ویژه از:
- تمام دانشجویان دوره برای بازخوردهای ارزشمند
- توسعه‌دهندگان کتابخانه‌های NumPy، Pandas، Matplotlib
- تیم Jupyter برای ایجاد محیط عالی تحلیل داده

---

## 📈 آمار مخزن

![GitHub stars](https://img.shields.io/github/stars/[username]/data-science-python-course?style=social)
![GitHub forks](https://img.shields.io/github/forks/[username]/data-science-python-course?style=social)
![GitHub issues](https://img.shields.io/github/issues/[username]/data-science-python-course)
![GitHub last commit](https://img.shields.io/github/last-commit/[username]/data-science-python-course)

---

## 🔄 به‌روزرسانی‌ها

برای اطلاع از آخرین به‌روزرسانی‌ها:
- ⭐ مخزن را Star کنید
- 👀 Watch کنید تا از تغییرات مطلع شوید
- 📧 در لیست ایمیل دوره عضو شوید

---

**موفق باشید در مسیر یادگیری علم داده! 🚀**

---

*آخرین به‌روزرسانی: [26/5/1404] | نسخه: 1.0.0*

---

## نکات تکمیلی برای README:

### 1. فایل‌های همراه که نیاز دارید:
- `requirements.txt`
- `environment.yml` 
- `LICENSE`
- `resources/faq.md`

### 2. برای تکمیل README:
- آدرس GitHub repository خود را جایگزین `[arazshah]` کنید
- اطلاعات تماس واقعی خود را وارد کنید
- تاریخ‌ها و نسخه‌ها را به‌روزرسانی کنید

### 3. بخش‌های اختیاری که می‌توانید اضافه کنید:
- بخش Changelog
- نمونه‌هایی از خروجی کدها
- ویدئوهای آموزشی
- لینک به وبسایت یا بلاگ شخصی

این README به‌صورت کامل و حرفه‌ای طراحی شده و آماده استفاده در GitHub است.