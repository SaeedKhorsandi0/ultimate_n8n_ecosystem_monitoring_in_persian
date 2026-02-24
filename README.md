# 🤖 Ultimate n8n Monitoring (Persian Edition)

یک سیستم مانیتورینگ هوشمند و خودکار برای رصد اخبار وبلاگ رسمی n8n، انجمن‌های Reddit و ویدئوهای جدید YouTube که با استفاده از هوش مصنوعی، محتوا را به فارسی ترجمه کرده و به تلگرام می‌فرستد.

![n8n](https://img.shields.io/badge/n8n-Workflow-orange?style=for-the-badge&logo=n8n)
![AI](https://img.shields.io/badge/AI-Translation-blue?style=for-the-badge&logo=openai)
![Telegram](https://img.shields.io/badge/Telegram-Notification-blue?style=for-the-badge&logo=telegram)

## 🌟 قابلیت‌های اصلی

* **رصد وبلاگ n8n:** مانیتورینگ خودکار RSS Feed وبلاگ رسمی برای دریافت مقالات جدید.
* **پایش Reddit:** بررسی ساب‌ردیت‌های `r/n8n` و `r/AI_Agents` برای گفتگوهای تازه.
* **جستجوی YouTube:** جستجوی جدیدترین ویدئوها با کوئری‌های مشخص شده.
* **ترجمه هوشمند AI:** استفاده از مدل‌های زبانی (LLM) برای ترجمه تخصصی عناوین و متن‌ها به فارسی.
* **تبدیل تاریخ به شمسی:** تبدیل خودکار زمان انتشار پست‌ها به فرمت فارسی برای خوانایی بهتر.
* **اطلاع‌رسانی تلگرامی:** ارسال خروجی نهایی به همراه تصویر و لینک مستقیم به بات تلگرام.

<img src="https://github.com/SaeedKhorsandi0/ultimate_n8n_ecosystem_monitoring_in_persian/blob/main/screenshots/Screenshot%202026-02-24%20at%2015-33-10%20%E2%96%B6%EF%B8%8F%20Ultimate%20N8N%20Monitoring%20-%20n8n.png">

## 📸 پیش‌نمایش خروجی

<div align="center">
  <table border="0">
    <tr>
      <td>
        <p align="center"><b>نمونه خروجی ردیت</b></p>
        <img src="https://github.com/SaeedKhorsandi0/ultimate_n8n_ecosystem_monitoring_in_persian/blob/main/screenshots/Screenshot_20260223_221305.jpg" width="350" alt="Reddit Screenshot">
      </td>
      <td>
        <p align="center"><b>نمونه خروجی یوتیوب</b></p>
        <img src="https://github.com/SaeedKhorsandi0/ultimate_n8n_ecosystem_monitoring_in_persian/blob/main/screenshots/Screenshot_20260223_221251.jpg" width="350" alt="YouTube Screenshot">
      </td>
    </tr>
  </table>
</div>

---

## 🚀 نحوه نصب و راه‌اندازی

1.  فایل `Ultimate_N8N_Monitoring.json` را از این ریپازیتوری دانلود کنید.
2.  در محیط n8n خود، یک ورک‌فلو جدید ساخته و فایل را **Import** کنید.
3.  **تنظیمات دسترسی (Credentials):**
    * **Telegram Api:** توکن بات خود را در نود تلگرام وارد کنید.
    * **Groq API:** کلید API خود را برای نودهای AI تنظیم کنید.
    * **YouTube API:** کلید API یوتیوب خود را در نود HTTP Request قرار دهید.
4.  ورک‌فلو را **Activate** کنید تا طبق زمان‌بندی (Schedule) اجرا شود.

## 📁 ساختار ریپازیتوری

* `Ultimate_N8N_Monitoring.json`: فایل اصلی ورک‌فلو برای ایمپورت در n8n.
* `/screenshots`: تصاویر پیش‌نمایش خروجی بات.
* `README.md`: راهنمای پروژه.

## ⚖️ لایسنس
این پروژه تحت لایسنس **MIT** منتشر شده است. استفاده و تغییر در آن برای همگان آزاد است.

---
**توسعه‌دهنده: سعید خورسندی**
[Linkedin](https://www.linkedin.com/in/saeedkhorsandi0) 
