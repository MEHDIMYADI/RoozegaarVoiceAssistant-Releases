# Roozegaar Voice Assistant

<details open>
<summary>🇮🇷 فارسی</summary>

<div dir="rtl">

## 🎙️ دستیار صوتی روزگار

**روزگار** یک برنامه‌ی دستیار صوتی مدرن برای ویندوز است که با استفاده از فناوری **Vosk** برای تشخیص گفتار و رابط کاربری قدرتمند **WinUI 3** توسعه داده شده. این برنامه توانایی درک گفتار به زبان‌های **فارسی** و **انگلیسی** را دارد و می‌تواند متن تشخیص داده‌شده را تایپ کند، فرمان‌های صوتی را اجرا نماید و نشانه‌گذاری را بر اساس گفتار انجام دهد.

---

## ⭐ ویژگی‌های کلیدی

- 🎤 **تشخیص گفتار در لحظه** با پشتیبانی از زبان فارسی و انگلیسی  
- ✍️ **تایپ هوشمند خودکار** متن‌های شنیده‌شده در هر نرم‌افزاری  
- 🧠 **فرمان‌های صوتی سفارشی‌پذیر** (مثلاً: اجرای برنامه، باز کردن لینک، تایپ متن خاص)  
- 🔤 **تشخیص و اجرای نشانه‌گذاری صوتی** (مثل «نقطه»، «ویرگول»، «علامت سوال»)  
- 🎚️ تنظیمات کامل برای انتخاب زبان، تم گرافیکی، حالت صوت، فرمت ساعت و...  
- 📋 قابلیت کپی و پاک‌کردن سریع متن‌های تشخیص‌داده‌شده  
- 🪟 طراحی مدرن و روان با WinUI 3 در محیط ویندوز ۱۰ و ۱۱  

---

## ⚙️ پیش‌نیازها

- Windows 10/11  
- [.NET 6 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/6.0) یا بالاتر  
- میکروفون فعال و مجاز برای برنامه  
- فایل‌های مدل Vosk برای زبان‌های:
  - فارسی: `VoskFA`
  - انگلیسی: `VoskEN`

---

## 🧭 نحوه استفاده

1. برنامه را اجرا کنید.
2. در اولین اجرا، دسترسی به میکروفون را فعال نمایید.
3. با زدن دکمه میکروفون، فرایند شنود آغاز می‌شود.
4. می‌توانید فرمان‌های صوتی تعریف‌شده یا نشانه‌گذاری را امتحان کنید.
5. به کمک صفحه تنظیمات، زبان و تم دلخواه خود را انتخاب نمایید.
6. با مراجعه به لیست فرمان‌ها و نشانه‌گذاری‌ها، دستورات جدید اضافه یا ویرایش کنید.

---

## 🧠 فرمان‌های صوتی قابل تنظیم

کاربر می‌تواند برای هر زبان (فارسی یا انگلیسی) فرمان‌هایی سفارشی تعریف کند. هر فرمان شامل:

- متن ماشه (Trigger)
- نوع عملکرد (مثل تایپ متن، اجرای فایل، باز کردن لینک)
- مقدار عملکرد (متن مورد تایپ، مسیر فایل یا آدرس اینترنتی)

---

## ✍️ نشانه‌گذاری صوتی

مثلاً اگر بگویید «ویرگول» یا «نقطه»، برنامه به‌طور خودکار `،` یا `.` را درج می‌کند. این فرمان‌ها نیز قابل ویرایش و تعریف توسط کاربر هستند.

---

## 🖼️ اسکرین‌شات‌ها (رابط فارسی)


---

## 📂 محل قرارگیری مدل‌های گفتاری

ساختار موردنیاز برای مدل‌های Vosk به این شکل است:

RoozegaarVoiceAssistant/
└── Assets/
└── Models/
├── VoskFA/
└── VoskEN/


---

## 📝 مجوز


</div>
</details>

<details>
<summary>🇬🇧 English</summary>

## 🎙️ Roozegaar Voice Assistant

**Roozegaar** is a modern voice assistant for Windows built with **WinUI 3** and powered by the **Vosk speech recognition engine**. It supports **real-time speech-to-text**, **custom voice commands**, and **spoken punctuation**, all within a clean, responsive user interface.

---

## ⭐ Key Features

- 🗣️ **Live speech recognition** in Persian (`fa-IR`) and English (`en-US`)
- 📝 **Smart auto-typing** of recognized text in any app
- 💡 **Custom voice commands** (e.g., open file, type text, launch app)
- ❗ **Speech-based punctuation** (say “comma”, “dot”, etc.)
- 🎨 User preferences for theme, language, audio feedback, and time format
- 📋 Easy copy or clear functionality for recognized text
- 🖥️ Seamless native Windows integration with WinUI 3

---

## ⚙️ Requirements

- Windows 10/11  
- [.NET 6 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/6.0)  
- Microphone access enabled  
- Downloaded Vosk models:
  - `VoskFA` for Persian
  - `VoskEN` for English

---

## 🚀 How to Use

1. Launch the app.
2. Grant microphone permission if prompted.
3. Press the mic button to start recognition.
4. Use smart text mode or command mode as needed.
5. Customize settings in the “Settings” page.
6. Add/edit commands or punctuation rules as needed.

---

## 🧠 Custom Voice Commands

Users can define voice triggers that perform specific actions such as:

- Typing predefined text
- Opening files or folders
- Launching applications
- Opening URLs

Each command can be language-specific.

---

## ✍️ Spoken Punctuation

Saying words like “comma”, “period”, or “question mark” will insert the appropriate symbol in the text output. You can add or edit these as well.

---

## 🖼️ Screenshots (English UI)


---

## 📁 Model Folder Structure

Make sure the Vosk model directories are placed as follows:

RoozegaarVoiceAssistant/
└── Assets/
└── Models/
├── VoskFA/
└── VoskEN/


---

## 📄 License


</details>
