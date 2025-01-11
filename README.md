# RakoAI
مشروع قيادة سيارات بالذكاء الاصطناعي بايثون

الذكاء الاصطناعي - التعلم العميق
مشروع تعليم السيارات على القيادة الآلية باستخدام الشبكات العصبية

كيف يعمل البرنامج ؟
تهيئة البيئة: يتم إعداد البيئة (مثل الطريق والسيارة) باستخدام فئة World وRoad.
تكوين الشبكة العصبية: يتم استخدام ملف config.txt لتحديد إعدادات NEAT، مثل عدد الأفراد في السكان، معايير اللياقة، وغيرها.
إنشاء الأفراد: يتم إنشاء مجموعة من الشبكات العصبية (الأفراد) باستخدام خوارزمية NEAT.
تقييم الأداء: يتم تشغيل كل فرد في البيئة، حيث يتم استخدام الشبكة العصبية للتحكم في السيارة. يتم تقييم أداء كل سيارة بناءً على مدى نجاحها في اجتياز الطريق.
تحديد اللياقة: يتم حساب اللياقة لكل فرد بناءً على أدائه، مثل المسافة المقطوعة أو السرعة.
التكاثر: يتم اختيار الأفراد الأفضل للتكاثر، حيث يتم دمج خصائصهم لإنشاء جيل جديد من الشبكات العصبية.
تكرار العملية: تتكرر هذه العملية لعدة أجيال، مما يسمح للخوارزمية بتحسين الشبكات العصبية بمرور الوقت.
عرض النتائج: يتم عرض أفضل الشبكات العصبية على الشاشة، مما يسمح للمستخدم بمشاهدة كيفية تطور أداء السيارات.
