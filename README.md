# ShortsCounter - عداد الفيديوهات القصيرة الذكي

تطبيق أندرويد متكامل بلغة Kotlin و Jetpack Compose يعمل كعداد شخصي لمتابعة الفيديوهات والريلز عبر تيك توك، إنستجرام، يوتيوب، سناب شات، وفيسبوك.

## المميزات الأساسية:
- أيقونة عائمة (Floating VR Widget) عبر WindowManager مع SYSTEM_ALERT_WINDOW.
- خدمة إمكانية وصول (Accessibility Service) مع فلترة ذكية لـ Scroll لمنع الحساب المزدوج.
- لوحة إحصائيات بـ Jetpack Compose و Material 3.
- قاعدة بيانات Room محلية مع حفظ الإحصائيات والتصفير اليومي.
- دعم كامل للعربية (RTL) والإنجليزية.

## خطوات البناء:
1. افتح المجلد في Android Studio.
2. انتظر Gradle Sync.
3. شغل الأمر `./gradlew assembleDebug` لإنشاء ملف الـ APK.
4. ثبت الـ APK عبر `adb install -r app/build/outputs/apk/debug/app-debug.apk`.
