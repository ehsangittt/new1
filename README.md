# new1 
لود بالانسر چیست؟
یک نوع فناوری که فشار رو بین سرور ها توزیع میکنه 
چه موقه های از اون استفاده میکنیم؟ برای بهبود عملکرد . قابلیت اطمینان و بالابردن ظرفیت سیستم 
لود بالانسر بعنوان یک پروکسی برای کاربران وب ترافیک رو بطور خودکار بین سرور ها پخش میکنه.
لود بالانسینک نوع های مختلفی داره که عبارتند از :
1-network traffic load balancing 
در این نوع ترافیک شبکه بین چندین سرور توزیع میشه تا بهبود عملکرد و کارایی سیستم رو فراهم کنه.
2- service layer load balancing 
در این نوع لابه سرویس با کاربری بین چندین لایه سرویس مثل دیتا بیس و وب سرویس توزیع میشود تا عملکرد سیستم رو بهبود بببخشن.
3-hardware load bancing 
برای این نوع از برخی تچهیزات سخت افزاری مانند سوییچ ها و فایروال ها برای توزیع بار کاری در شبکه استفاده میشه
4- dns load balancing 
در این نوع هربار که سیستم dns به درخواست کلاینت پاسخ میده . نسخه ای متفاوت از لیست ip ها ارسال میکنه درخواست های dns بطور یکنواخت بین سرور های متخلف توزیع میشود تا بار کلی هدایت رو مدیریت کنه .
5-software load balancing 
برای توزیع بار کاری بین چندین سرور در این روش از نرم افزار ها استفاده میشود در واقع نرم افزار میتونه بر اساس عوامل مختلف مثل بار کنونی پاسخ سرور و محل جفراقیایی بار رو بطور هوشمند توزیع کند. 



این بود از انواع لود بالانسینگ 
حالا باید به مزیت های اون بپردازیم 
۱-افزایش قابلیت اطمینان :‌با استفاده از لود بالانسر بار کاری بین سرور ها به طور منظم توزیع میشه و در پی این احتمال از کار افتادن سرور مبنی بر بار بالا کاهش پیدا میکنه .
۲- بهبود کارایی :‌با توزیع بار بین چندین سرور امکان بهره برداری از توان پردازش بیشتر وو افازیش ظزقیت وجود دارد . پس با استفاده از لود بالانسر کاربر از سرعت و کارایی بهتر بهره میبرد
۳- مقاومت در برابر حملات ؛ لود بالانسر میتواند به عنوان یک لایه دفاعی در برابر حملات مخرب عمل کند و در پی این کار باعث کمتر شدن اختلالات بشود. 
۴- سهولت در مدیریت :‌با استفاده از لود بالانسر مدیران شبکه میتونن به راحتی سرور ها رو حذف و اضافه کنند .
این بود لود بالانسینگ
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
فایروال یا دیوار آتشین
برای محافظت کردن از سیستم یا شبکه ما استفاده میشود . 
بصورت نرم افزاری و سخت افزاری میشه تهیه کرد . 
فایروال سر راه شبکه قرار میگیره برای ارتباط با دنیای بیرون در واقع هر کسی از بیرون خواد با شبکه ما ارتباط داشته باشه و بلعکس ترافیکش توسط فایروال کنترل میشه . 
فایروال علاوه بر اینک برای شبکه باشه برای سیستم عامل هم هست که از هاهست محافظت میکنه .
بریم سراغ پورت ها ۱۰۲۴ پورت اول که البته میشن ۰ تا ۱۰۲۳ که بهشون میگن wellknown port ینی پورت های مشهور . پورت هایی که برای کارهای اصلی و شناخته شده استفاده میشن مثلا برای پروتکل وب از پورت ۸۰ استفاده میشه (http) و پورت ۴۳۳ هم برای https.
پورت های زیر ۱۰۲۳ به پایین برای کارهای و امور ترافیک ها و استفاده پروتکل های پر کاربرد و معروف استفاده میشن و از ۱۰۲۴ به بالا unknown port هستن که به برنامه نویسا توصیه میشه که از این پورت های استفاده کنن تا تداخلی ایجاد نکند.
فایروال در ساده ترین کارش داره این پورت هارو مدیریت میکنه 
حالا فایروال انواعی دارن که مهم ترینشون عبارتند از 
1- packet filtering
2- stateful inspection
3-application filtering 
4-next-generation firewall (ngfw)
5-unified threat management(utm)
بریم سراغ تعریف هاشون
خب تو قدم اول packet filtering میگه که من میتونم تا 4 لایه رو شناسایی کنم ینی از لایه 1 تا 4 رو میشناسه و بر اساس دانشی که از این 4 لایه داره میتونه امنیت برقرار کنه .
ی نکته اینجا هست که لایه چیه اینجا؟
میریم سراغ تعریف  OSI 
یک معماری 7 لایه که هر کدوم در رابطه با انتقال داده ها در شبکه کامپیوتری وظیفه خاصی رو انجام میده. 
ابن 7 لایه چین؟
1- فیزیکی که پایین ترین لایه مدل OSI 
2- داده(لینک)
3- شبکه
4- انتقال 
5- نشس
6- نمایش
7- اپلیکیشن که بالاترین لایه مدل OSI هست.
در این مدل هر لایه دارای پروتکل ها استاندارها و فرآیندهای مختلفی میباشد و هر یک سرویسی را به لایه بالاتر از خود اراِئه داده و خود نیز سرویسی از لایه پایینی دریافت و در نتیجه لایه اپلیکیشن اخرین لایه ای است که سرویس دریافت میکند.
هر کدام از این لایه ها یک عملکرد اصلی و یک شکل اطلاعتی ( راه ارتباطی دارن ).
در لایه اول ( فیزیکی ) عملکرد اصلی ایجاد اتصالی فیزیکی میان دستگاه با شکل اطلاعات بیت هستش.
در لایه داده-لینک، عملکرد اصلی، ایجاد ارتباطی بدون خطا میان دستگاه های یک شبکه با شکل اطلاعات فریم هستش.
در لایه سوم که شبکه هستش ، مسیریابی و پیدا کردن بهتر مسیر برای انتقال داده ها عملکرد اصلی و شکل ارتباطی بسته است . 
در لایه چهارم ( انتقال ) کنترل جریان داده برطرف کردن خطا ها و تحویل بدون مشکل داده ها عملکرد اصلی و سگمنت شکل ارتباطیه.
در لاله 5 ام که لایه نشست هستش ایجاد،مدیریت و پایان داده به سشن ها عملکرد اصلیه و شکل اطلاعاتیش هم پیام میباشد.
در لایه 6 ام که لایه نمایشه عملکرد اصلی، رمز نگاری ، رمزگشایی، تغییر فرمت و فشرده سازی داده ها هستش و شکل اطلاعاتی اون هم مانند لایه نشست پیامه.
لایه 7 ام و اخرین و بالاترین لایه که اپلیکیشن هستش برقراری ارتباط مستقیمبا اپلیکیشن ها و اراِئه خدمات شبکه به کاربران نهایی علمکردشه و شکل اطلاعاتی اون هم مانند دو لایه اخر پیام هست.


