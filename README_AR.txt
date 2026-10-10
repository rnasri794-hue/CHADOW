SHADOW — مشروع Android تجريبي
================================

شنوّة فيه؟
- تطبيق أندرويد بسيط يفتح واجهة SHADOW داخل WebView.
- 4 تحدّيات يومية، XP ومستويات.
- يحفظ التقدّم على نفس الجهاز باستعمال localStorage.
- يدعم Android 7.0 فما فوق (minSdk 24).

كيفاش تفتحو على PC؟
1) نزّل Android Studio من الموقع الرسمي: https://developer.android.com/studio
2) فكّ الضغط على SHADOW_Android_Starter.zip.
3) من Android Studio اختار Open وافتح مجلّد SHADOW_Android_Starter.
4) استنّى Gradle Sync. يلزم إنترنت أوّل مرّة باش يحمّل الأدوات.
5) اختار Run لتشغيله على Emulator أو تليفون مربوط بالـ USB مع تفعيل USB debugging.

كيفاش تجرّبو بسرعة من غير Android Studio؟
1) افتح app/src/main/assets/index.html بمتصفّح Chrome على الـ PC.
2) على الهاتف تنجم تنسخ index.html وتفتحو بمتصفّح يدعم الملفات المحلية، أما أحسن تجربة تكون عبر Android Studio.

كيفاش تخرّج APK؟
1) في Android Studio: Build > Build Bundle(s) / APK(s) > Build APK(s)
2) بعد ما يكمل، اضغط locate من الإشعار باش تلقى ملف APK.
3) انقل APK للتليفون وثبّتو. يمكن يلزم تسمح بتثبيت التطبيقات من هذا المصدر.

ملاحظات مهمّة:
- هذا نموذج أولي، موش تطبيق منشور في Google Play.
- ما فيهش تسجيل حسابات، مزامنة بين الأجهزة، ولا قاعدة بيانات سحابية.
- اسم SHADOW اسم عمل مؤقّت؛ قبل النشر تثبّت من توفر الاسم والعلامة التجارية.
- المشروع يستخدم Android Gradle Plugin 8.6.1 ويحتاج JDK 17 ونسخة حديثة من Android Studio.
- ما نجّمتش نعمل build فعلي للـ APK داخل هذه الحزمة؛ يلزم Android Studio على جهازك.
