# بناء التطبيق من السحابة

المشروع يحتوي على `codemagic.yaml` لتسهيل البناء على Codemagic.

1. ارفع محتويات المشروع إلى GitHub.
2. افتح Codemagic وأضف مستودع GitHub.
3. اختر Flutter.
4. شغّل workflow `android-debug-apk` للحصول على APK تجريبي.
5. لنسخة iPhone، شغّل `ios-unsigned` أولًا للتأكد من نجاح البناء.
6. للتثبيت والتوزيع على iPhone/TestFlight يلزم إعداد Apple code signing وApp Store Connect داخل Codemagic.

المشروع لا يحتوي على مفاتيح توقيع أو حسابات شخصية.
