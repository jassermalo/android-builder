# Android Builder

مشروع Android مع GitHub Actions لبناء APK تلقائياً وبسرعة.

## كيفية الاستخدام

### بناء APK
- ادفع أي commit إلى `main` branch → يبدأ البناء تلقائياً
- أو: **Actions** > **Android Build** > **Run workflow** (يدوي)

### تحميل APK
1. اذهب إلى **Actions**
2. اختر آخر run ناجح (علامة خضراء)
3. في أسفل الصفحة: **Artifacts** → حمّل `app-debug-N`

## سرعة البناء
- أول مرة: ~5 دقائق
- بعدها (cache): ~2-3 دقائق

## تعديل التطبيق
- الكود: `app/src/main/java/com/example/androidbuilder/MainActivity.kt`
- الواجهة: `app/src/main/res/layout/activity_main.xml`
