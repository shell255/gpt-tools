# GPT Text Generator

![interface](https://github.com/user-attachments/assets/7ed07977-0fa2-4735-8d83-36201aeea8b2)

---
این پروژه یک رابط کاربری گرافیکی زیبا و کاربردی برای تولید متن، کد، داستان‌های تعاملی و ارزیابی مدل‌های مختلف مانند GPT-2 و CodeGen ارائه می‌دهد. با استفاده از این ابزار می‌توانید به راحتی مدل‌های زبان طبیعی را مدیریت و از خروجی‌های آن بهره‌برداری کنید

---

## **🚨 Requirements**

این پروژه برای اجرا نیاز به **پایتون نسخه 3.8.6** دارد. لطفاً اطمینان حاصل کنید که نسخه صحیح پایتون روی سیستم شما نصب است.  
برای بررسی نسخه پایتون، دستور زیر را در خط فرمان اجرا کنید:
```bash
python --version
```

---

## **💫 Main features**

- تولید متن: تولید متن‌های خلاقانه با استفاده از مدل‌های مختلف GPT-2.
- تولید کد: تولید کدهای برنامه‌نویسی با مدل CodeGen از طریق ورودی‌های توصیفی.
- داستان‌های تعاملی: ایجاد داستان‌های سفارشی و خلاقانه با همکاری مدل.
- مدیریت مدل‌ها: دانلود و ذخیره مدل‌ها در مسیرهای سفارشی.
- آموزش مدل‌ها: آموزش مجدد مدل‌ها با داده‌های دلخواه و ذخیره‌سازی تغییرات.
---
## **📁 Project Structure**
```bash
.
├── app.py                 # رابط کاربری گرافیکی (Gradio)
├── model.py               # مدیریت و بارگذاری مدل‌ها
├── generate.py            # منطق تولید متن و کد
├── train.py               # آموزش مجدد مدل‌ها
├── database.py            # مدیریت پایگاه داده برای ذخیره ورودی‌ها
├── models/          # مسیر پیش‌فرض برای ذخیره مدل‌ها
└── lib.txt       # لیست کتابخانه‌های موردنیاز
```
---
## **🚀 Installation and setup**

### **نصب پایتون 3.8.6**
اگر پایتون نسخه 3.8.6 روی سیستم شما نصب نیست، از صفحه دانلود  آن را نصب کنید.
در سیستم‌های لینوکسی می‌توانید از دستورات زیر استفاده کنید
```bash
sudo apt update
sudo apt install python3.8
```
---
### **کلون کردن**
ابتدا مخزن پروژه رو کلون کنید
```bash
git clone https://github.com/ali0discord/gpt-text-generator.git
cd gpt-text-generator
```
---
### **نصب کتابخانه ها**
با این دستور کتابخانه ها رو نصب کنید
```bash
pip install -r lib.txt
```
---
### **دانلود مدل ها**
با اجرای این فایل مدل های مورد نیاز به صورت خودکار دانلود و در دایرکتوری مخصوص ذخیره میشوند
```bash
python download.py
```
---
### **اجرای کدها**
با دستور زیر کد ها رو اجرا کنید
```bash
python app.py
```
پس از اجرای کد ها به صورت کامل وارد ادرس
```bash
127.0.0.1:7860
```
---
## **گزارش باگ ها**
از طریق بخش Issues گیت هاب با ما در ارتباط باشید
