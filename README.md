<div align="right">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://kashanu.ac.ir/assets/2425b86d/images/logo.png">
    <source media="(prefers-color-scheme: light)" srcset="https://upload.wikimedia.org/wikipedia/commons/9/9a/University_of_Kashan_Logo.png">
    <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="">
  </picture>

</div>

# قالب لتک پایان نامه دانشگاه کاشان <sub> (غیر رسمی)
</sub>

- فایلی که باید کامپایل کنید، Athesis است. متن هر بخش از پایان نامه جداگانه و در پوشه‌ی Chapters قرار دارد. متن پایان نامه‌ی من به عنوان متن پیش‌فرض در این قالب قرار دارد و می‌توانید دستورات لازم برای نوشتن پایان نامه را از روی پایان نامه کپی کنید. در سایر موارد هم راهنمای لتک به صورت آنلاین وجود دارد.
- این قالب با توجه به نکات و تذکرات موجود در آموزش دانشکده برق و کامپیوتر دانشگاه کاشان تهیه و ویرایش شده است. نسخه‌ی پایه‌ی این قالب بر اساس قالب دانشگاه صنعتی اصفهان است.
- از نصب بودن فونت B ZAR و B Zar Bold بر روی سیستم خود اطمینان حاصل کنید. اگر به مشکل پیدا نکردن فونت برخوردید، از وجود این - فونت ها در پوشه Windows/Fonts از طریق CMD مطمین شوید.
- کامپایلر ادیتور را روی XeLaTeX قرار دهید.
- برای تهیه‌ی واژه نامه، از برنامه ثانویه مثل اکسل استفاده شده است. بدین منظور می‌توانید فایل ارائه شده در این قالب را ویرایش کنید و از آن خروجی PDF بگیرید.
- توصیه می‌شود از شکل‌های برداری با فرمت PDF استفاده شود. این کار علاوه بر افزایش کیفیت رسال/پایان‌نامه/گزارش، باعث کاهش حجم شکل‌ها (و در نتیجه  کاهش حجم فایل نهایی) و همچنین کاهش زمان پردازش می‌شود. می توانید شکل را در پاورپوینت ایجاد کنید و از آن خروجی PDF بگیرید.
- برای آن‌که پردازش فایل و مشاهده خروجی در هنگام نوشتن پایان‌نامه آسان‌تر و سریع‌تر انجام شود، فصل‌ها و بخش‌هایی که در حال نوشتن آن‌ها نیستید را غیر فعال کنید. به‌عنوان مثال، در این قالب، این دستورات را می‌توان در صورت عدم نیاز با اضافه کردن % به طور موقت غیرفعال کرد:
```
% \MakeTitlePage
% \MakeFarsiSignaturePage
% \input{Chapters/nowledgments}
% \MakeCopyRightPage
% \input{Chapters/Dedication}
% \MakeTableOfContents
% \MakeListOfFigures
% \MakeListOfTables
% \MakeFarsiAbstract
% \input{Chapters/Chapter#}
% \MakeAppendices
% \input{Chapters/Appendices}
% \MakeEnglishAbstract
% \MakeEnglishSignaturePage
```
- آخرین نسخه ادیتوری که این قالب با آن تست شده تکس استودیو ۴.۵.۲ بوده است.
- در صورتی که میخواهید به سطر بعد بروید اما نمیخواهید بین دو کلمه‌ای که نوشتید فاصله بیفتد کافی است در انتهای خط اول  (بدون فاصله) کاراکتر % را اضافه کنید. با این عمل، لاتک خط فاصله ایجاد شده در اثر تغییر سطر را به عنوان توضیح اضافه یا کامنت در نظر میگیرد و در خروجی اعمال نمی‌کند.

 تشکر فراوان از آقای فخاری و آقای جان نثاری که نسخه‌ی پایه‌ی این قالب را ایجاد کردند.
 
![Language](https://img.shields.io/badge/Language-LaTeX-blue)
![Version](https://img.shields.io/badge/Version-2.2-fuchsia)
![Compiler](https://img.shields.io/badge/Compiler-XeLaTeX-red)
![IDE](https://img.shields.io/badge/IDE-TexStudio-yellow)
![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)

 
