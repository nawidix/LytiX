# Lytix - v1.8 - EN

🔻 **Smart 3D Model Optimization Without Quality Loss** 🔻  
---

## 📌 Overview

**Lytix** is a standalone Windows application (`.exe`) that allows you to reduce the polygon count of high-poly 3D models without affecting visual quality or structure. Designed for game developers and 3D artists, it enables clean Low-Poly exports for real-time engines like **Unity** and **Unreal Engine** — with just a few clicks.

---

## 🎯 Key Features

- ✅ Supports `.fbx`, `.obj`, `.dae`, `.glb` 3D model formats  
- 🎚️ Polygon reduction control via simple slider (up to 90%)  
- 🧠 Non-destructive optimization with Blender running in background  
- 💾 Output saved automatically with `_lowpoly` suffix  
- 🔍 View detailed logs and conversion history  
- 📁 No Python required — fully compiled `.exe`  
- 🛠️ Blender executable path can be configured  
- 🌐 Fully localized in Persian (Farsi) with RTL support  

---

## 🖥️ How to Use

1. Run the `Lytix.exe` file.
2. Click **"انتخاب فایل مدل"** to select your model file.
3. Adjust the **"میزان کاهش"** slider to control polygon reduction.
4. Click **"تبدیل به Low-Poly"** to begin the process.
5. The optimized file will be saved in the same folder with a `_lowpoly` suffix.
6. View the conversion summary in the **history panel** below.

---

## ⚙️ Requirements

- **Windows 10 / 11**  
- **Blender v3.0+** installed on your system  
- Configure Blender path manually from inside the app

> Example path:  
> `C:\Program Files\Blender Foundation\Blender 3.6\blender.exe`

---

## 📦 Technologies Used

- Python + PyQt5 (compiled to `.exe`)
- Blender CLI (headless mode)
- Unicode & RTL Persian interface

---

## 📁 Example Output

| Original File          | Output File              | Polygon Reduction |
|------------------------|--------------------------|-------------------|
| `Character.fbx`        | `Character_lowpoly.fbx`  | 30%               |
| `Scene.obj`            | `Scene_lowpoly.obj`      | 50%               |
| `Tree.glb`             | `Tree_lowpoly.glb`       | 40%               |

All exports are optimized and ready for real-time engines like Unity and Unreal.

---

## 👨‍💻 Developer

Developed with ❤️ by **[Nawidx](https://github.com/Nawidx)**  
Feel free to submit feedback, issues, or feature requests via GitHub.

---

## 🔮 Planned Features

- 🧰 Batch conversion (multi-file support)  
- 👁️ Live 3D model preview  
- 🎮 Unity/Unreal export compatibility  
- 🧵 Texture/material preservation

---

## 📜 License

Released under the **MIT License**  
You are free to use, modify, and distribute this software.

---

## 🔗 Download

> ✅ Download the latest version from the [Releases](https://github.com/your-repo-link/releases) section.  
> Simply unzip and run `Lytix.exe`. No installation required.

---

<div dir="rtl">

# Lytix - نسخه ۱.۸

🔻 **بهینه‌سازی هوشمند مدل‌های سه‌بعدی بدون افت کیفیت** 🔻  
*مناسب برای طراحان سه‌بعدی، بازی‌سازان و پروژه‌های ریل‌تایم*

---

## 📌 معرفی

**Lytix** یک نرم‌افزار مستقل ویندوزی (فایل اجرایی `.exe`) است که امکان کاهش هوشمند حجم مدل‌های سه‌بعدی (Low-Poly) را فراهم می‌کند بدون آن‌که به ظاهر، ساختار، یا کیفیت مدل آسیب وارد شود. این ابزار برای توسعه‌دهندگان بازی، طراحان صحنه‌های سه‌بعدی و پروژه‌هایی که به بهینه‌سازی مدل برای اجرا در موتورهایی مثل **Unity** یا **Unreal Engine** نیاز دارند طراحی شده است.

---

## 🎯 قابلیت‌ها

- ✅ پشتیبانی از فرمت‌های رایج مدل سه‌بعدی: `.fbx`, `.obj`, `.dae`, `.glb`  
- 🎚️ امکان تعیین درصد کاهش پلی‌گان از طریق اسلایدر (تا ۹۰٪)  
- 🧠 کاهش حجم غیرمخرب با استفاده از Blender در حالت پس‌زمینه  
- 💾 ذخیره خودکار خروجی با پسوند `_lowpoly` در کنار فایل اصلی  
- 🔍 نمایش گزارش دقیق عملیات و تاریخچه تبدیل‌ها  
- 📁 بدون نیاز به نصب پایتون – نرم‌افزار به صورت `.exe` مستقل ارائه شده  
- 🛠️ قابلیت انتخاب مسیر اجرایی Blender توسط کاربر  
- 🌐 رابط کاربری فارسی، با پشتیبانی کامل از نمایش راست به چپ (RTL)

---

## 🖥️ روش استفاده

۱. فایل `Lytix.exe` را اجرا کنید.  
۲. روی دکمه **«انتخاب فایل مدل»** کلیک کرده و فایل سه‌بعدی موردنظر را وارد کنید.  
۳. با اسلایدر **«میزان کاهش»**، درصد دلخواه کاهش پلی‌گان را تنظیم نمایید.  
۴. روی دکمه **«تبدیل به Low-Poly»** کلیک کنید و منتظر پایان عملیات بمانید.  
۵. فایل خروجی در کنار فایل اصلی و با پسوند `_lowpoly` ذخیره خواهد شد.  
۶. تاریخچه تبدیل‌ها در پایین صفحه قابل مشاهده است.

---

## ⚙️ پیش‌نیازها

- سیستم‌عامل: **ویندوز ۱۰ یا ۱۱**  
- نصب نرم‌افزار **Blender نسخه ۳.۰ یا بالاتر**  
- تعیین مسیر Blender از داخل برنامه

> مثال مسیر Blender:  
> `C:\Program Files\Blender Foundation\Blender 3.6\blender.exe`

---

## 📦 تکنولوژی‌های استفاده‌شده

- توسعه با Python + PyQt5 (کامپایل‌شده به `.exe`)  
- اجرای Blender به صورت Headless (بدون رابط گرافیکی)  
- رابط کاربری فارسی، پشتیبانی کامل از زبان راست‌چین  
- بدون نیاز به نصب دستی پایتون یا کتابخانه‌ها

---

## 📁 مثال خروجی

| فایل ورودی            | فایل خروجی                 | درصد کاهش پلی‌گان |
|------------------------|-----------------------------|--------------------|
| `character.fbx`        | `character_lowpoly.fbx`     | ۳۰٪                |
| `environment.obj`      | `environment_lowpoly.obj`   | ۵۰٪                |
| `tree.glb`             | `tree_lowpoly.glb`          | ۴۰٪                |

خروجی‌ها برای استفاده مستقیم در موتورهایی مانند Unity و Unreal مناسب هستند.

---

## 👨‍💻 توسعه‌دهنده

این نرم‌افزار با ❤️ توسط **[Nawidx](https://github.com/Nawidx)** توسعه داده شده است.  
پیشنهادات و گزارش خطاهای شما باعث بهبود نسخه‌های بعدی خواهد شد.

---

## 🔮 ویژگی‌های آینده

- 🧰 تبدیل گروهی چند فایل به‌صورت هم‌زمان  
- 👁️ پیش‌نمایش زنده مدل قبل و بعد از کاهش  
- 🎮 خروجی مستقیم برای Unity و Unreal با نگه‌داری متریال‌ها  
- 🧵 پشتیبانی از بافت و مواد (Texture / Material Preservation)

---

## 📜 مجوز استفاده

این پروژه تحت مجوز **MIT License** منتشر شده است.  
استفاده، ویرایش و بازنشر آن کاملاً آزاد است.

---

## 🔗 دانلود

> ✅ آخرین نسخه را از بخش [Releases](https://github.com/your-repo-link/releases) دریافت کنید.  
> فقط کافیست فایل را از حالت فشرده خارج کرده و `Lytix.exe` را اجرا نمایید.

</div>

