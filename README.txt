PriceMind AI - مشروع أندرويد

الطريقة 1 (Android Studio):
  File > Open > اختر هذا المجلد > انتظر Sync > Build > Build APK(s)
  الناتج: app/build/outputs/apk/debug/app-debug.apk

الطريقة 2 (بدون Android Studio، من المتصفح):
  1) أنشئ مستودعاً جديداً على github.com وارفع محتويات هذا المجلد (بما فيها .github).
  2) تبويب Actions > Build APK > Run workflow.
  3) بعد دقائق نزّل app-debug.apk من Artifacts.

داخل التطبيق: الإعدادات ⚙ > ضع مفتاح Gemini API (aistudio.google.com/apikey).
ملاحظة: app/src/main/assets/index.html يعمل أيضاً وحده في المتصفح.
