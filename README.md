# X-O-game-android-JAVA online
# using firebase firestore ....

-----

أوامر التعامل مع Git
لرفع مشروع الى ال Git 
cd / d  // 
حدد مكان الملف 
cd   My_Project // 
افتح الملف 
git init  // 
إضافة ملف تعقب من جت الى مشروعك
git add .  // 
إضافة كافة ملفات المشروع , وتهيئتها للرفع
git commit -m "upload the  project"  // 
عمليات الإضافة و الرفع تتطلب هذا الامر , سيتم شرحه لاحقا 
git remote add origin   enter url address (from git site) / / 
تحديد مكان رفع الملف عن طريق إضافة رابط المشروع الموجود ع جت هب
git push u- origin master // امر لرفع المشروع الى الموقع , كلمة ماستر ستوضح لاحقا 
لتحميل مشروع من  ال Git  الى جهازك
cd /c  
لتحديد مكان تحميل المشروع 
git clone    url link  // 
لتحميل المشروع , نضع رابط المشروع هنا 

عمل تحديث للمشروع ( في حال كان المشروع محملا على جهازك )
git pull origin master

 
للتعديل على المشروع و رفع تعديلاتك 
cd  /d

cd   My_project //  
نفتح المشروع 
git add .  //  
نضيف جميع الملفات 
git commit -m  " my first update" //  
نعمل كومميت جديدة , و نسميها ب اسم ما
git push origin master  // 
نرفع الملفات الى السيرفر 


في حالة  مرضيش يعمل إضافة حط هادا الامر و اعمل إضافة تاني

git config core.autocrlf true


