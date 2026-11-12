# 🛢️ Awesome Petroleum Engineering Python Libraries
### مجموعه جامع کتابخانه‌های کاربردی پایتون در مهندسی نفت

![Python Version](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)
![Domain](https://img.shields.io/badge/Domain-Petroleum%20Engineering-orange)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-success)

به مخزن مرجع ابزارها و کتابخانه‌های متن‌باز پایتون در **مهندسی نفت (پتروفیزیک، مخزن، حفاری، بهره‌برداری و زمین‌شناسی)** خوش آمدید. این مخزن جهت دسترسی سریع دانشجویان و پژوهشگران به ابزارهای استاندارد صنعتی و دانشگاهی گردآوری شده است.

---

## 🚀 نصب سریع (Quick Start)

شما می‌توانید هر کتابخانه را به‌صورت جداگانه از طریق جدول‌های زیر نصب کنید، و یا تمامی کتابخانه‌های این مجموعه را به‌صورت یکجا با دانلود این مخزن و اجرای دستور زیر نصب نمایید:

```bash
git clone https://github.com/YOUR-USERNAME/petroleum-python-libraries.git
cd petroleum-python-libraries
pip install -r requirements.txt
```

---

## 📚 فهرست دسته‌بندی‌شده کتابخانه‌ها

### ۱. پتروفیزیک و تحلیل لاگ‌های چاه (Petrophysics & Well Logging)

| نام کتابخانه | کاربرد اصلی | دستور نصب | لینک دانلود و مستندات (PyPI) |
| :--- | :--- | :--- | :--- |
| **lasio** | خواندن، ویرایش و نوشتن فایل‌های لاگ استاندارد با فرمت `.LAS` | `pip install lasio` | [PyPI - lasio](https://pypi.org/project/lasio/) |
| **welly** | بارگذاری، پردازش، کنترل کیفیت (QC) و رسم نمودارهای چاه و لاگ‌ها | `pip install welly` | [PyPI - welly](https://pypi.org/project/welly/) |
| **dlisio** | استخراج و خواندن سریع داده‌های لاگ سنگین و پیچیده با فرمت `.DLIS` | `pip install dlisio` | [PyPI - dlisio](https://pypi.org/project/dlisio/) |
| **petropy** | محاسبات پتروفیزیکی (حجم شیل، تخلخل، اشباع آب) و ارزیابی سازند | `pip install petropy` | [PyPI - petropy](https://pypi.org/project/petropy/) |
| **striplog** | ایجاد، مدیریت و نمایش داده‌های چينه‌شناسی و لیتولوژی چاه | `pip install striplog` | [PyPI - striplog](https://pypi.org/project/striplog/) |

---

### ۲. مهندسی مخزن و خواص سیالات (Reservoir Engineering & PVT)

| نام کتابخانه | کاربرد اصلی | دستور نصب | لینک دانلود و مستندات (PyPI) |
| :--- | :--- | :--- | :--- |
| **pyrestoolbox** | محاسبات جامع مهندسی مخزن (خواص PVT نفت و گاز، نفوذپذیری نسبی و جریان چاه) | `pip install pyrestoolbox` | [PyPI - pyrestoolbox](https://pypi.org/project/pyrestoolbox/) |
| **resdata** | خواندن و تحلیل فایل‌های خروجی شبیه‌سازهای مخزن (مانند Eclipse و OPM) | `pip install resdata` | [PyPI - resdata](https://pypi.org/project/resdata/) |
| **fluids** | محاسبات مکانیک سیالات، افت فشار در لوله‌ها، شیرآلات و تجهیزات درون‌چاهی | `pip install fluids` | [PyPI - fluids](https://pypi.org/project/fluids/) |
| **thermo** | محاسبات ترمودینامیکی، تعادل فازی (VLE) و خواص سیالات هیدروکربنی | `pip install thermo` | [PyPI - thermo](https://pypi.org/project/thermo/) |

---

### ۳. مهندسی حفاری و بهره‌برداری (Drilling & Production Engineering)

| نام کتابخانه | کاربرد اصلی | دستور نصب | لینک دانلود و مستندات (PyPI) |
| :--- | :--- | :--- | :--- |
| **wellpathpy** | محاسبات مسیر چاه (Well Trajectory) و داده‌های انحراف‌سنجی (Directional Survey) | `pip install wellpathpy` | [PyPI - wellpathpy](https://pypi.org/project/wellpathpy/) |
| **well-profile** | طراحی، شبیه‌سازی و ترسیم سه‌بعدی پروفایل چاه‌های جهت‌دار و افقی | `pip install well-profile` | [PyPI - well-profile](https://pypi.org/project/well-profile/) |
| **petbox-dca** | تحلیل منحنی‌های افت تولید (Decline Curve Analysis - DCA) و پیش‌بینی تولید | `pip install petbox-dca` | [PyPI - petbox-dca](https://pypi.org/project/petbox-dca/) |

---

### ۴. زمین‌آمار، زمین‌شناسی و لرزه‌نگاری (Geostatistics, Geology & Seismic)

| نام کتابخانه | کاربرد اصلی | دستور نصب | لینک دانلود و مستندات (PyPI) |
| :--- | :--- | :--- | :--- |
| **GeostatsPy** | زمین‌آمار و مدل‌سازی استوکاستیک مخزن (توسعه‌یافته در دانشگاه تگزاس در آستین) | `pip install geostatspy` | [PyPI - geostatspy](https://pypi.org/project/geostatspy/) |
| **segyio** | خواندن، نوشتن و پردازش سریع داده‌های لرزه‌نگاری دوبعدی و سه‌بعدی (`SEG-Y`) | `pip install segyio` | [PyPI - segyio](https://pypi.org/project/segyio/) |
| **gempy** | مدل‌سازی زمین‌شناسی ساختاری سه‌بعدی (گسل‌ها، چین‌خوردگی‌ها و لایه‌ها) | `pip install gempy` | [PyPI - gempy](https://pypi.org/project/gempy/) |

---

### ۵. کتابخانه‌های پایه علوم داده و هوش مصنوعی (Core Data Science & AI)

| نام کتابخانه | کاربرد در پروژه‌های مهندسی نفت | دستور نصب | لینک دانلود و مستندات (PyPI) |
| :--- | :--- | :--- | :--- |
| **Pandas** | مدیریت داده‌های سری زمانی تولید، گزارش‌های روزانه حفاری (DDR) و داده‌های آزمایشگاهی | `pip install pandas` | [PyPI - pandas](https://pypi.org/project/pandas/) |
| **NumPy / SciPy** | محاسبات ماتریسی، بهینه‌سازی و حل معادلات دیفرانسیل جریان در محیط متخلخل | `pip install numpy scipy` | [PyPI - scipy](https://pypi.org/project/scipy/) |
| **Scikit-Learn** | یادگیری ماشین (تخمین نفوذپذیری، تشخیص رخساره‌های سنگی و پیش‌بینی تولید) | `pip install scikit-learn` | [PyPI - scikit-learn](https://pypi.org/project/scikit-learn/) |
| **Plotly** | رسم نمودارهای تعاملی لاگ چاه، داشبوردهای تولید و نمایش سه‌بعدی مسیر چاه | `pip install plotly` | [PyPI - plotly](https://pypi.org/project/plotly/) |

---

## 👨‍🎓 درباره ارائه‌دهنده (Presenter Info)

* **نام و نام خانوادگی:** [علی معصومی]
* **دانشگاه / دانشکده:** دانشکده مهندسی نفت - [دانشگاه تبریز]
* **ارتباط با من:** [لینکدین](#) | [ali.masoomi.ali.1385@gmail.com](mailto:your.email@example.com)

> ⭐ اگر این مخزن برای پروژه‌ها و پژوهش‌های شما مفید بود، لطفاً با دادن یک **Star** در بالای صفحه از آن حمایت کنید!
