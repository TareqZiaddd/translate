# translate
#
##https://www.npmjs.com/package/countapi-js
#https://countapi.xyz/

Create a counter and restrict its operations    إنشاء عداد وتقييد عملياته
--------------------------------------------------------------------
Restrict   تقييد
-------------------------------------------------------------------
All counters are accesible    جميع العدادات يمكن الوصول إليها
-----------------------------------------------------------------
accesible   يمكن الوصول اليه 
------------------------------------------------------------------
Want to track the number of hits a page had? Sure.     هل تريد تتبع عدد الزيارات التي حصلت عليها الصفحة؟ بالتأكيد.
-----------------------------------------------------------------------
track  تتبع او رصد
-------------------------------------------------------------------------
Want to know the number of users that clicked on the button "Feed Cow"? There you go.   تريد معرفة عدد المستخدمين الذين نقروا على زر "إطعام البقرة"؟ تفضل
--------------------------------------------------------------------------
There you go.   تفضل
-----------------------------------------------------------------------------
So far, ... keys have been created حتى الان تم انشاء المفاتيح
-------------------------------------------------------------------------
So far, ... keys have been created and there have been ... requests served being ... key updates.
This page has been visited ... times.
--------------------------------------------------------------------------
identified inside a namespace  المحددة داخل مساحة الإسم
-----------------------------------------------------------------------------
Each counter is identified inside a namespace with a key. يتم تعريف كل عداد داخل مساحة الاسم باستخدام مفتاح.
-------------------------------------------------------------------------
Inside each namespace you can generate all the counters you may need. داخل كل مساحة اسم، يمكنك إنشاء جميع العدادات التي قد تحتاجها.
--------------------------------------------------------------------------
you may need قد تحتاج.
---------------------------------------------------------------------------
is identified  يتم تعريفه
-------------------------------------------------------------------------
generate  يولد او ينشىء 
--------------------------------------------------------------------------
The hit endpoint provides increment by one counters directly  عند الاتصال بنقطة النهاية يتم تحديث العدادات بقيمة 1 مباشرة
-----------------------------------------------------------------------------
The hit endpoint 

ما هو "نقطة النهاية عند استدعائها" (hit endpoint)؟
نقطة النهاية عند استدعائها (hit endpoint) هي نقطة اتصال محددة في نظام برمجي أو تطبيق تُستخدم لتلقي طلبات معينة وإرسال استجابات. تُعرف أيضًا باسم "نقطة الوصول" أو "API endpoint".
-----------------------------------------------------------------------------
 Each time its requested   في كل مرة طلبت او في كل مرة تم الطلب
--------------------------------------------------------------------------
The hit endpoint provides increment by one counters directly. Each time its requested the counter will increase by one:
توفر نقطة نهاية النتيجة زيادة بمقدار عداد واحد مباشرة. في كل مرة يتم طلبها، سيزيد العداد بمقدار واحد
-----------------------------------------------------------------------------
If you want to have a counter for each individual page  إذا كنت تريد أن يكون لديك عداد لكل صفحة على حدة
-----------------------------------------------------------------------------
individual page صفحة مستقلة 
--------------------------------------------------------------------------
you can replace visits with a unique identifier for each page  يمكنك استبدال الزيارات بمعرف فريد لكل صفحة
-----------------------------------------------------------------------------
Alternatively  بدلاً من ذلك
-----------------------------------------------------------------------------
reserved words الكلمات المحجوزة
--------------------------------------------------------------------------
Alternatively, you can use some reserved words that are replaced server-side.
For example, if a request is made from https://mysite.com/example/page:   وبدلاً من ذلك، يمكنك استخدام بعض الكلمات المحجوزة التي يتم استبدالها من جانب الخادم.
على سبيل المثال، إذا تم تقديم طلب من https://mysite.com/example/page:

-----------------------------------------------------------------------------

ترجمة "that are replaced server-side" إلى العربية:
عبارة "that are replaced server-side" تشير إلى أن بعض الكلمات أو الرموز الموجودة في عنوان موقع الويب (URL) لا تُعرض للمستخدم بشكل مباشر، بل يتم استبدالها بشيء آخر بواسطة الخادم قبل عرض المحتوى.

شرح مفصل:

Server-side (جانب الخادم): يشير هذا إلى الجزء من موقع الويب الذي يعمل على جهاز كمبيوتر (خادم) ولا يكون مرئيًا للمستخدم بشكل مباشر. حيث يقوم الموقع بمعالجة المعلومات وإنشاء المحتوى الذي تراه في متصفحك.
Replaced (استبدال): تعني أنّ شيئًا ما يتم تبديله بشيء آخر.
لذا، في هذا السياق، تعني "الكلمات التي يتم استبدالها على جانب الخادم" وجود رموز أو كلمات رئيسية خاصة مخفية داخل عنوان URL يفهمها الخادم.

مثال:

تخيل موقعًا يقدم محتوى مخصصًا بناءً على موقعك. قد يبدو عنوان URL مثل:

https://mysite.com/news/local
قد يبدو الأمر وكأن الموقع يعرض فقط مقالات إخبارية عامة. ولكن من وراء الكواليس، قد يتعرف الخادم على كلمة "local" كرمز ويستبدلها بأخبار خاصة بمنطقتك. وبالتالي، قد ترى عناوين رئيسية ذات صلة بمدينتك أو منطقتك.

ملاحظة:

تُستخدم هذه التقنية غالبًا في مواقع الويب الديناميكية التي تقدم محتوى مخصصًا للمستخدمين بناءً على سلوكهم أو بياناتهم.
قد لا تكون على دراية بهذه العملية لأنها تحدث خلف الكواليس دون تدخل منك.
-----------------------------------------------------------------------------
:HOST: will be replaced with mysite.com
:PATHNAME: will be replaced with examplepage :HOST: سيتم استبداله بـ mysite.com
:PATHNAME: سيتم استبداله بصفحة المثال
-----------------------------------------------------------------------------
Note: Reserved words are padded with dots if their length is less than three.  ملاحظة: يتم تعبئة الكلمات المحجوزة بالنقاط (.) إذا كان طولها أقل من ثلاثة أحرف.
-----------------------------------------------------------------------------
padded  حشو,تعبئة,تبطين
-----------------------------------------------------------------------------
Important: if you want to know the actual key used you can check the X-Path header.
هام: إذا كنت تريد معرفة المفتاح الفعلي المستخدم، فيمكنك التحقق من رأس X-Path
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Multiple pages
If you want to have a counter for each individual page you can replace visits with a unique identifier for each page, i.e. index, contact, item-1234. Check the right format a key must have.

Alternatively, you can use some reserved words that are replaced server-side.
For example, if a request is made from https://mysite.com/example/page:

:HOST: will be replaced with mysite.com
:PATHNAME: will be replaced with examplepage

Note: Reserved words are padded with dots if their length is less than three.
So you could use something like:

https://api.countapi.xyz/hit/mysite.com/:PATHNAME:
Or even more generic (though not recommended):

https://api.countapi.xyz/hit/:HOST:/:PATHNAME:
Important: if you want to know the actual key used you can check the X-Path header.


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
هات مثال اخر لنفترض أن لديك موقعين:
موقعك الرئيسي: https://mysite.com
موقع فرعي: https://blog.mysite.com
إذا كنت تريد تتبع عدد الزيارات على الصفحة الرئيسية لكلا الموقعين:
https://api.countapi.xyz/hit/mysite.com/:PATHNAME::
يمكنك استخدام هذا الرابط دون أي تغيير، حيث تفترض CountAPI اسم المجال "mysite.com".
https://api.countapi.xyz/hit/:HOST:/:PATHNAME::
يمكنك استخدام هذا الرابط، لكن ستحتاج إلى استبدال :HOST: بـ "mysite.com" أو "[تمت إزالة عنوان URL غير صالح]" اعتمادًا على الصفحة التي تتبعها.
في النهاية، يعتمد اختيار الرابط المناسب على احتياجاتك ومتطلبات موقع الويب الخاص بك.
-----------------------------------------------------------------------------
First, include the package    اولاً قم بتضمين الحزمة
-----------------------------------------------------------------------------
This is the official promise-based wrapper for CountAPI. CountAPI is a free counting service, you can use it to track page hits, and custom events.
هذا هو الغلاف الرسمي المستند إلى الوعود لـ CountAPI. CountAPI هي خدمة عد مجانية، يمكنك استخدامها لتتبع مرات تحميل الصفحات والأحداث المخصصة.



معنى "wrapper" في النص:
في النص الذي قدمته، تُستخدم كلمة "wrapper" للإشارة إلى غلاف برمجي. الغلاف البرمجي هو أداة برمجية تُستخدم لتسهيل استخدام مكتبة أو خدمة ما.

في هذا السياق، يُشير "wrapper" إلى مكتبة برمجية تسمح لك بالتفاعل مع خدمة CountAPI بسهولة.

مميزات استخدام wrapper:

سهولة الاستخدام: يوفر wrapper واجهة برمجة بسيطة تسمح لك بالتفاعل مع CountAPI دون الحاجة إلى تعلم كيفية استخدام واجهة برمجة التطبيقات الخاصة بها مباشرة.
إخفاء التعقيد: يقوم wrapper بإخفاء تفاصيل التنفيذ الداخلية لـ CountAPI، مما يجعل من السهل عليك استخدامها دون الحاجة إلى فهم كيفية عملها.
توفير الوظائف الإضافية: قد يوفر wrapper وظائف إضافية لا تتوفر في واجهة برمجة التطبيقات الأصلية لـ CountAPI.
-----------------------------------------------------------------------------
parsing error   خطأ تحليل 
-----------------------------------------------------------------------------

-----------------------------------------------------------------------------
adjacent jsx  elements must be wrapped in an enclosing tag    
-----------------------------------------------------------------------------
adjacent متجاور
s يعني ان العناصر يتم وضعها جنباً الى جنب بدون كونتينر يحتويها
-----------------------------------------------------------------------------
wrapped تغليف العناصر المتجاورة بعنصر رئيسي واحد.
-----------------------------------------------------------------------------
discussion مناقشة
thread موضوع
block او اليمينت كتلة
existing موجود
-----------------------------------------------------------------------------
discussion thread on a block.  موضوع المناقشة على كتلة
-----------------------------------------------------------------------------
Add a comment to an existing discussion thread on a block. إضافة تعليق إلى موضوع نقاش موجود على كتلة
-----------------------------------------------------------------------------
Notion هو تطبيق لإدارة المشاريع وتنظيم المعلومات يتميز بتعدد وظائفه وسهولة استخدامه.
-----------------------------------------------------------------------------

-----------------------------------------------------------------------------

-----------------------------------------------------------------------------

-----------------------------------------------------------------------------

-----------------------------------------------------------------------------

-----------------------------------------------------------------------------

-----------------------------------------------------------------------------







