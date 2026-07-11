<div align="center">

# 🧠 Ultimate Academic & Computer Science Vocabulary Matrix (6,997 Words)

### ماتریس یکپارچه و بهینه‌سازی‌شده واژگان آکادمیک و علوم کامپیوتر برای آیلتس ۸ و تافل

[![Vocabulary](https://img.shields.io/badge/Vocabulary-6%2C997%20Unique%20Words-blueviolet.svg?style=flat-square)](https://github.com/)
[![Target](https://img.shields.io/badge/Target-IELTS%208%2B%20%7C%20TOEFL%20110%2B-gold.svg?style=flat-square)](https://github.com/)
[![Anki](https://img.shields.io/badge/Format-Anki%20Ready-orange.svg?style=flat-square&logo=anki&logoColor=white)](https://apps.ankiweb.net/)
[![License](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)](https://opensource.org/licenses/MIT)

**Language / زبان**

**[🇬🇧 English Version](#-english-version)** | **[🇮🇷 نسخه فارسی](#-نسخه-فارسی)**

</div>

---

# 🇬🇧 English Version

This repository features a production-grade, highly consolidated English language lexical matrix engineered specifically for **Computer Science researchers, software engineers, and elite academic candidates (IELTS Band 8+ / TOEFL 110+)**. 

By compiling the world’s most authoritative general, academic, and domain-specific corpuses into a unified, single-column data structure, this project eliminates cross-corpus redundancy through rigorous deduplication. The primary objective is to streamline high-tier language acquisition, serving as a comprehensive linguistic framework for writing research theses, reading state-of-the-art literature, and mastering advanced academic tests.

---

## 🚀 Core Lexical Matrix & Excel Schema

The underlying dataset is structured as a comprehensive matrix spreadsheet. The layout below illustrates the exact order of the columns mapped in the master database, showcasing how raw target corpuses flow sequentially into the final clean compilation:

| Column Order | Column Header | Data Scope & Target Utility |
| :---: | :--- | :--- |
| **1** | `NGSL` | 2,801 High-Frequency Base Headwords covering over 90% of general English text. |
| **2** | `CSAVL` | 904 Core Academic Words—the absolute gold standard for computer science discourse. |
| **3** | `CSAVL-S` | 702 Spoken Specialist Words tailored for computer science speech and academic lectures. |
| **4** | `AWL(sublist 1)` | Sublist 1 of Averil Coxhead's Academic Word List (Most frequent academic families). |
| **5** | `AWL(sublist 2)` | Sublist 2 of the Academic Word List. |
| **6** | `AWL(sublist 3)` | Sublist 3 of the Academic Word List. |
| **7** | `AWL(sublist 4)` | Sublist 4 of the Academic Word List. |
| **8** | `AWL(sublist 5)` | Sublist 5 of the Academic Word List. |
| **9** | `AWL(sublist 6)` | Sublist 6 of the Academic Word List. |
| **10** | `AWL(sublist 7 & 8)` | Combined high-tier academic vocabulary from Sublists 7 and 8. |
| **11** | `AWL(sublist9 & 10)` | Combined advanced academic vocabulary from Sublists 9 and 10. |
| **12** | `COCA-5000` | Top 5,000 highest frequency words from contemporary American English. |
| **13** | `all_words` | The raw, unified column containing the sequential stack of all corpuses combined (~11,000+ terms). |
| **14** | `unique_words` | **The Final Production Column.** Programmatically cleaned via a deduplication engine to leave exactly **6,997 non-repeating words**. |

---

## 📊 Empirical Consolidation & Data Metrics

The entire database was combined into a single matrix to guarantee zero-overlap learning efficiency. 

*   **Massive Deduplication Yield:** Stacking all five lists raw would result in over 11,000 overlapping entries. Through systematic data cleaning, the list was compressed into exactly **6,997 unique, high-impact words** in the `unique_words` column.
*   **Optimal Text Coverage:** Familiarity with the NGSL base combined with the Academic Word List (AWL) grants automated recognition of approximately 90% of words in standard academic literature.
*   **Research & Thesis Readiness:** The inclusion of the CSAVL corpus directly bridges the gap between general academic English and the precise semantic nuances required for writing top-tier software engineering or AI publications.

---

## 📂 File Structure & Repository Map

```text
├── Database Pipeline
│   ├── Unified_Lexical_Matrix.xlsx (Complete spreadsheet containing all columns)
│   ├── master_unified_column.csv (Export of raw all_words)
│   └── deduplicated_6997_final.txt (Export of unique_words dataset)
│
├── Raw Corpuses (Historical Source Data)
│   ├── NGSL_Headwords_2801.txt
│   ├── CSAVL_Core_904.txt
│   ├── CSAVL_Spoken_702.txt
│   ├── AWL_Sublists_1_to_10.txt
│   └── BNCOCA_Top5K_Bands.txt
│
└── Anki Ecosystem (Coming Soon)
    ├── Scripts
    └── Releases

```

---

## 🗺️ Future Roadmap

* [ ] Release of the **Premium Persian-Localized Anki Flashcard Deck (`.apkg`)**
* [ ] Implementation of the Ultra-Clean Single-Tab card layout optimized for rapid review
* [ ] Explicit multi-meaning splits (e.g., *Run* as physical movement vs. *Run* as managing/running a business)
* [ ] Collocation mappings to teach words in high-scoring natural combinations
* [ ] Integration of advanced grammatical structures and templates for immediate production (Speaking/Writing)

---

# 🇮🇷 نسخه فارسی

این مخزن شامل یک ماتریس واژگانی پیشرفته، یکپارچه و بهینه‌سازی‌شده برای زبان انگلیسی است که به‌طور اختصاصی برای **دانشجویان و پژوهشگران علوم کامپیوتر، مهندسان نرم‌افزار و متقاضیان نمرات برتر آزمون‌های بین‌المللی (IELTS Band 8+ / TOEFL 110+)** مهندسی شده است.

در این پروژه، معتبرترین پیکره‌های متنی (Corpuses) عمومی، آکادمیک و تخصصی جهان در یک ساختار داده تک‌ستونی ادغام شده و با اعمال الگوریتم‌های حذف هم‌پوشانی (Deduplication)، واژگان تکراری آنها کاملاً پاک‌سازی شده‌اند. هدف نهایی این ماتریس، بهینه‌سازی فرآیند یادگیری، تسهیل نگارش مقالات علمی و پایان‌نامه‌ها و تسلط بر متون پیشرفته است.

---

## 🚀 ماتریس ساختاری و ستون‌های فایل اکسل

پایگاه داده اصلی این پروژه در قالب یک فایل اکسل ساختاریافته طراحی شده است. جدول زیر ترتیب دقیق ستون‌های موجود در این فایل و نحوه جریان داده‌های خام تا رسیدن به نسخه نهایی را نشان می‌دهد:

| ترتیب ستون | نام سرستون (Header) | محدوده داده و هدف آکادمیک |
| --- | --- | --- |
| **۱** | `NGSL` | تعداد ۲,۸۰۱ کلمه کلیدی پرکاربرد پایه؛ پوشش‌دهنده بالای ۹۰٪ از متون عمومی. |
| **۲** | `CSAVL` | تعداد ۹۰۴ واژه آکادمیک هسته؛ استاندارد طلایی متون تخصصی علوم کامپیوتر. |
| **۳** | `CSAVL-S` | تعداد ۷۰۲ واژه تخصصی گفتاری؛ بهینه‌شده برای سخنرانی‌ها و لکچرهای آکادمیک کامپیوتر. |
| **۴** | `AWL(sublist 1)` | ساب‌لیست ۱ از واژگان آکادمیک Averil Coxhead (پرکاربردترین لغات دانشگاهی). |
| **۵** | `AWL(sublist 2)` | ساب‌لیست ۲ از مجموعه واژگان آکادمیک AWL. |
| **۶** | `AWL(sublist 3)` | ساب‌لیست ۳ از مجموعه واژگان آکادمیک AWL. |
| **۷** | `AWL(sublist 4)` | ساب‌لیست ۴ از مجموعه واژگان آکادمیک AWL. |
| **۸** | `AWL(sublist 5)` | ساب‌لیست ۵ از مجموعه واژگان آکادمیک AWL. |
| **۹** | `AWL(sublist 6)` | ساب‌لیست ۶ از مجموعه واژگان آکادمیک AWL. |
| **۱۰** | `AWL(sublist 7 & 8)` | ترکیب واژگان سطح بالای آکادمیک ساب‌لیست‌های ۷ و ۸. |
| **۱۱** | `AWL(sublist9 & 10)` | ترکیب واژگان پیشرفته آکادمیک ساب‌لیست‌های ۹ و ۱۰. |
| **۱۲** | `COCA-5000` | ۵,۰۰۰ واژه اول و پرتکرار کورپوس انگلیسی معاصر آمریکا. |
| **۱۳** | `all_words` | ستون ادغام خام؛ شامل تجمیع متوالی تمام پیکره‌ها روی یکدیگر (بیش از ۱۱,۰۰۰ لغت). |
| **۱۴** | `unique_words` | **ستون نهایی و خروجی پروژه.** شامل دقیقاً **۶,۹۹۷ واژه منحصربه‌فرد** پس از حذف کلمات تکراری. |

---

## 📊 تحلیل تجربی و نتایج یکپارچه‌سازی

به منظور تضمین بالاترین بازدهی زمان مطالعه، تمام پایگاه‌های داده در یک ستون نهایی تلفیق شدند.

* **خروجی خالص پس از فیلتراسیون:** در صورت تجمیع ساده و خام این ۵ لیست، تعداد واژگان به بیش از ۱۱,۰۰۰ کلمه می‌رسید. با اعمال فرآیند پاک‌سازی داده‌ها، این مقدار در ستون `unique_words` به دقیقاً **۶,۹۹۷ واژه منحصربه‌فرد و کلیدی** کاهش یافت.
* **پوشش متنی بهینه:** تسلط هم‌زمان بر پایه لغات NGSL و واژگان آکادمیک (AWL)، به شما شناختی خودکار نسبت به حدود ۹۰٪ از لغات به‌کاررفته در متون استاندارد دانشگاهی می‌دهد.
* **آمادگی برای نگارش مقالات تخصصی:** وجود پیکره تخصصی CSAVL به عنوان فیلتر نهایی، فاصله بین انگلیسی آکادمیک عمومی و کلمات دقیق مورد نیاز برای نگارش مقالات در ژورنال‌های معتبر هوش مصنوعی و نرم‌افزار را کاملاً پوشش می‌دهد.

---

## 📂 ساختار پروژه

```text
├── Database Pipeline (خط لوله داده)
│   ├── Unified_Lexical_Matrix.xlsx (فایل اکسل جامع شامل تمام ستون‌ها)
│   ├── master_unified_column.csv (خروجی خام ستون all_words)
│   └── deduplicated_6997_final.txt (خروجی نهایی ستون unique_words)
│
├── Raw Corpuses (پیکره‌های خام اولیه)
│   ├── NGSL_Headwords_2801.txt
│   ├── CSAVL_Core_904.txt
│   ├── CSAVL_Spoken_702.txt
│   ├── AWL_Sublists_1_to_10.txt
│   └── BNCOCA_Top5K_Bands.txt
│
└── Anki Ecosystem (به‌زودی)
    ├── Scripts
    └── Releases

```

---

## 🗺️ نقشه راه آینده

* [ ] انتشار **دک پرمیوم فلش‌کارت‌های انکی شخصی‌سازی‌شده به زبان فارسی (`.apkg`)**
* [ ] پیاده‌سازی قالب تک‌تب (Single-Tab) فوق‌العاده تمیز و بهینه برای مرور با بالاترین سرعت
* [ ] تفکیک دقیق و مجزای کلمات چندمعنایی (مثال: بررسی کلمه *Run* در نقش دویدن در مقابل *Run* به معنی مدیریت یک کسب‌وکار)
* [ ] نگاشت کالوکیشن‌ها (Collocations) برای آموزش ترکیب‌های طبیعی کلمات جهت کسب نمره Lexical Resource بالا
* [ ] ادغام گرامرها و ساختارهای جمله‌سازی پیشرفته برای استفاده مستقیم در آزمون‌های Speaking و Writing

```

```
