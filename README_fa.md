# قالب معرفی نرم‌افزار

![CodeFactor](https://www.codefactor.io/repository/github/mjavadh/Software.introduction-template/badge)

![Static Badge](https://img.shields.io/badge/HTML5-blue)
![Static Badge](https://img.shields.io/badge/CSS3-orange)
![Static Badge](https://img.shields.io/badge/Bootstrap-8A2BE2)
![Static Badge](https://img.shields.io/badge/jQuery-darkblue)
![Static Badge](https://img.shields.io/badge/aos-lightyellow)

قالب تک صفحه‌ای معرفی نرم‌افزار، دارای دو حالت تیره و روشن و همچنین چپ چین و راست چین بسته به سلیقه شما، استفاده شده از bootstrap و jQuery، انیمیشن های جذاب برای دکمه های تغییر تم،‌ پخش ویدیو و منوی موبایل؛ استفاده شده از کتابخانه AOS برای ایجاد انیمیشن هایی هنگام اسکرول، قابل شخصی سازی،طراحی مدرن و ریسپانسیو

[پیشنمایش][Preview]

[![Preview][Banner]][Banner]

## فهرست
* [ویژگی ها](#ویژگی-ها)
* [فایل ها](#فایل-ها)
* [شخصی سازی](#شخصی-سازی)

## ویژگی ها
*  دارای دو حالت تیره و روشن
*  نحوه نمایش قالب به صورت چپ به راست(ltr) و راست به چپ(rtl)
*  Bootstrap
*  jQuery
*  انیمیشن های اختصاصی
*  AOS
*  امکان شخصی سازی
*  طراحی مدرن و نئومورفیسم
*  کاملا ریسپانسیو

## فایل ها

در این قالب از کتابخانه های Bootstrap، jQuery، AOS و همچنین از فونت وزیر برای ایجاد صفحه استفاده شده است؛ که درون پوشه assets قرار داده شده‌اند، همچنین میتوانید فایل هایی با نام های style و script مشاهده کنید که اصلی ترین بخش برای شخصی سازی این قالب مربوط به این دو فایل است.

## شخصی سازی
#### تغییر مطالب قالب: 
در بالای تگ های اصلی متن های راهنما نوشته شده که به شکل <-- متن --!> هستند مانند خط 135 فایل index که نشان دهنده این است که خطوط پایین زیر این راهنما مربوط به سکشن باکس ها میباشد و به همین صورت دیگر تگ های اصلی همچنین راهنمایی هایی در بالای خود دارند این راهنمایی ها به شما کمک میکنند به راحتی مطالب قالب را شخصی سازی کنید.
#### تغییر قالب بندی صفحه(چپ چین و راست چین کردن): 
اگر وبسایتی که میخواهید بسازید انگلیسی و بین المللی هست نیاز دارید که حروف انگلسی به درستی نمایش داده شوند و برای این کار نیاز به قالبی دارید که چپ چین باشد، شما با در این قالب براحتی میتوانید فقط با چند حرکت صفحه خود را بین راست چین و چپ چین سوییچ کنید تنها کاری که لازمه در فایل index به تگ  html کلاس page_ltr بدهید با این کار صفحه به حالت چپ چین در می آید و نمایش بهتری از محتوای انگلیسی به شما میدهد اگر میخواهید صفحه شما راست چین شود فقط کافیست کلاس page_ltr از تگ html پاک کنید. توجه داشته باشید در صورتی که از حروف فارسی در صفحه خود استفاده میکنید قالب را در حالت راست چین بگذارید.
#### تغییر عناوین دکمه های منو: 
در داخل تگ header دو تگ nav و ul قرار دارد که داخل آنها دکمه های منو و عناوین شون قرار دارد برای تغییر هر دکمه باید توجه داشته باشید در هر دو تگ nav و ul تغییر مورد نظر خود را اعمال کنید تگ nav برای منو هست که در کامپیوتر های شخصی،لپتاپ و آیپد ها نمایش داده میشود و تگ ul منوی هست که در موبایل به نمایش در می آیند؛ دلیل اینکه دو تگ منو جدا قرار دارد برای این است که شما بتوانید در دستگاه های مختلف شخصی سازی های خاصی در نظر بگیرید. توجه داشته باشید که درون تگ nav تگی دیگر به نام ul قرار دارد که لیست دکمه در آن تگ است.
#### تغییر تصویر لوگو در منو: 
لوگو همان تصویری است که در نوار منو قرار دارد برای تغییر آن وارد تگ header شوید و بعد وارد تگ nav در آخر درون تگ a تگ img قرار دارد(خط 76) که شما آدرس عکس درون مشخصه src میگذارید. اگر این روش برای شما سخت هست فقط کافیست است نام فایل لوگو خود را به Logo تغییر داده و داخل پوشه image جایگزین فایل قبلی کنید توجه داشته باشید پسوند فایل لوگو شما در این روش باید .png باشد.
سایز پیشنهادی لوگو 100*50 پیکسل میباشد اگر طول تصویر بیشتر و یا کمتر از 100 باشد اشکالی ندارد اما سعی شود ارتفاع تصویر حتما 50 پیکسل باشد.
#### حذف بخش هایی که لازم ندارید:
احتمالا بعد دیدن صفحه وب متوجه شدین بعضی بخش های صفحه مورد نیاز شما نیست و میخواهید حذف شوند برای این کار 2 راه وجود دارد اول اینکه کد های بخش مربوطه که لازم ندارید حذف کنید و یا اینکه از کلاس d-none استفاده کنید مثلا اگر بخش تعرفه هارو نیاز ندارید فقط کافیه به تگی که مربوط به تعرفه ها میشود کلاس d-none اضافه کنید.
#### دو ستونه کردن بخش ویژگی ها:
بخش ویژگی ها دارای 3 ستون هست که 2 ستون سمت چپ و راست مربوط به توضیحات و ستون وسطی تصویر قرار میگیرد اگر میخواید یکی از ستون توضیحات حذف کنید پیشنهاد میشه تگ div با کلاس left_attrs حذف کرده و یا کلاس d-none به آن اضافه کنید.
#### شخصی سازی استایل های صفحه:
وارد فایل style شوید در بعضی از خطوطی روبروی استایل وارد شده راهنما هایی مانند /\*متن\*/ قرار دارد که توضیحات کوتاهی درباره استایل میدهد تا اگر میخواستید تغییراتی ایجاد کنید سردرگم نشید و سریع متوجه کارایی استایل نوشته شده شوید.

## تصویر کامل از صفحه
![Full-RTL]

[Preview]: https://mjavadh.github.io/Software.introduction-template/
[Banner]: https://github.com/MjavadH/Software.introduction-template/blob/master/docx/preview/Banner-RTL.png "Banner"
[Full-RTL]: https://github.com/MjavadH/Software.introduction-template/blob/master/docx/preview/Full-RTL.png "Full-RTL"
