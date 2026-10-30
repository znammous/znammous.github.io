# znammous.github.io

ملفّا التوثيق اللذان يفتحان روابطَ قصص «نور الوحي» المُشارَكة في التطبيق لمن ثبّته،
بدل المتصفّح — ويجب أن يكونا في جذر النطاق لا تحت `/quran-kids/`:

- `.well-known/assetlinks.json` — أندرويد (App Links): بصمتا شهادة التوقيع، شهادةُ Google Play
  للتطبيق من المتجر، ومفتاحُ الرفع لملفّ APK المنشور على GitHub.
- `.well-known/apple-app-site-association` — أبل (Universal Links): معرّفُ الفريق والتطبيق.

والمسارات `/quran-kids/stories/p/*` و`/quran-kids/stories/<لغة>/p/*` وحدَها — صفحاتُ المشاركة في
[quran-kids](https://github.com/znammous/quran-kids). و`.nojekyll` لئلّا يُسقط Jekyll مجلّدَ `.well-known`.
