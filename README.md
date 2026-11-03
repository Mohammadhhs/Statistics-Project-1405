<div dir="rtl" lang="fa" align="right">

<h1>فاز اول پروژهٔ آمار</h1>

<p>مسیر ج، بررسی ارتباط اختلاف ضخامت قشر انتورینال چپ و راست با نمرهٔ شناختی MoCA در زیرمجموعهٔ آموزشی NACC.</p>

<h2>فایل‌های تحویل</h2>

<ul>
  <li><a href="PROJECT_CARD.md">کارت پروژه</a></li>
  <li><a href="reports/phase1.pdf">گزارش فاز اول</a></li>
  <li><a href="phase1.ipynb">نوت‌بوک تحلیل و بازتولید خروجی‌ها</a></li>
</ul>

<p>برچسب نسخهٔ تحویل در Git برابر <code dir="ltr">phase-1</code> است.</p>

<h2>داده‌های لازم</h2>

<p>برای بازتولید تحلیل، نسخهٔ تحویلی تیم درس از دو فایل <code dir="ltr">udslong_imputed.csv</code> و <code dir="ltr">mriscanclean.csv</code> را روی رایانهٔ خود کنار <code dir="ltr">phase1.ipynb</code> قرار دهید. تاریخ دریافت این نسخه در مستندات همراه مشخص نشده است. فایل‌های خام را خارج از مخزن و بستهٔ تحویل نگه دارید. <a href="https://www.naccdata.org/the-nacc-researchers-guide/">منبع رسمی داده و راهنمای پژوهشگران NACC</a></p>

<h2>اجرای تحلیل</h2>

<p>در پوشهٔ نوت‌بوک، دستورهای زیر را با پایتون اجرا کنید. کد با پایتون ۳٫۱۲ و نسخه‌های مشخص‌شدهٔ کتابخانه‌ها بررسی شده است.</p>

<div dir="ltr" align="left">
<pre dir="ltr"><code>python -m pip install notebook pandas==2.2.3 matplotlib==3.10.8
python -m notebook</code></pre>
</div>

<p>در جوپیتر، نوت‌بوک را باز کنید، کرنل را بازنشانی کنید و همهٔ سلول‌ها را از ابتدا اجرا کنید. جدول‌ها، چهار نمودار و پیام «کنترل نهایی انجام شد» در خروجی نوت‌بوک نمایش داده می‌شوند.</p>

</div>
