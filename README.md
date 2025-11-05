# Git

کلون گرفتن 
```commandline
git clone ./link/
```

### اتصال به اکانت گیت هاب
وارد کردن نام کاربری
```commandline
git config --global user.name "Your Name"
```
وارد کردن ایمیل
```commandline
git config --global user.email "your.email@example.com"
```
 دیدن وضعیت فایل ها
```bash
git status
```

اد کردن همه  فایل ها 
```bash
git add .
```

اد کردن یک فایل خاص 
```bash
git add .\fileKhas
```

کامیت کردن فایل
```bash
git commit -m "commit_message"
```

پوش کردن فایل 
```commandline
git push origin main
```

پول کردن  
```commandline
git pull origin main
```

کلون گرفتن:

```bash
git clone git@github.com:bahadorifatemeh1384-eng/project name.git
```
دیدن راهنمای استفاده از کامند های گیت
```commandline
git help
```

# Linux


ساخت پوشه جدید
```bash
mkdir name
```

دیدن فایل های موجود در پوشه
```commandline
ls
```

خارج شدن از پوشه
```commandline
cd ..
```

ورود به پوشه خاص
```commandline
cd .\folder's name\
```

نمایش تنظیمات و آدرس‌های IP سیستم در ویندوز
```commandline
 ipconfig  
 ```

# python

برای اجرای یک فایل پایتون از دستور زیر استفاده میشود

```bash
python file_name.p
```
برای ساخت venv از دستور :
```bash
python -m venv venv
```

برای فعال کردن venv:
(همه پکیج ها به venv اضافه میشن )
```bash
.\venv\Scripts\activate
```
غیر فعال کردن:

```bash 
deactivate
```

 نصب پکیج جدید مثلا fast api :

```bash
 pip install "fastapi[standard]"
 ```

 وقتی استفاده میشه که بخوای یه اسکریپت PowerShell (مثل نصب FastAPI، یا 
 اجرای یه فایل .ps1) رو اجرا کنی ولی خطا بگیری با پیام
running scripts is disabled on this system.
با این دستور، اون محدودیت رو موقتاً برمی‌داری.

```bash
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass 
```

یک محیط مجازی پایتون در پوشه‌ای به نام venv ایجاد می‌کنه.
داخلش نسخه‌ی جداگانه‌ای از پایتون و pip نصب میشه تا بتونی پکیج‌ها رو فقط برای همین پروژه نصب کنی، نه برای کل سیستم.

```bash
python -m venv venv                                  
```
 فعال کردن venv:
```bash
cd \venv\script\activate
```

غیر فعال کردن venv:

```bash 
deactivate
```

نصب یک پکیج پایتون با pip:

مثلا  پکیج fast API به همراه پکیج های جانبی
```bash
pip install "fastapi[standard]"     
```
اجرای برنامه‌ی FastAPI در حالت توسعه (development) از فایل main1.py

```bash
fastapi dev main1.py            
```

ذخیره‌ی فهرست پکیج‌های نصب‌شده در فایل req.txt
```bash
pip freeze > req.txt   
```

این دستور سرور FastAPI رو از فایل main.py بالا میاره و روی پورت ۸۰ در دسترس همه‌ی دستگاه‌ها قرار می‌ده
```bash
uvicorn main:app --host 0.0.0.0 --port 80      
```
