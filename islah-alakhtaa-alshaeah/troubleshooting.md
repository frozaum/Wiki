# إصلاح الأخطاء الشائعة

## **في البداية**

تأكد من أن لديك [الملحق](../altthbyt/extension.md) **و**  [التطبيق](../altthbyt/application.md) مثبتين
Yيمكنك أيضًا تجربة خطوات مختلفة. ليس عليك تجربة هذه بالترتيب الذي وضعناه هنا.

##  الديسكورد لن يظهر presence

### تأكد من عدم تشغيل الديسكورد كمسؤول

مهم للغاية. لن يعمل Discord RPC إذا قمت بتشغيل الديسكورد كمسؤول.

### تأكد من تثبيت أحدث إصدار من PreMiD

يمكنك التحقق من ذلك بالنقر بزر الماوس الأيمن فوق ** "Check For Updates" ** أيقونة PreMiD في شريط المهام.
وإلا فإن التطبيق سوف يخبرك عند توفر تحديث جديد.
ولا داعي للقلق بشأن الملحق لأنه يقوم بتحديث نفسه تلقائيًا.

{% hint style="info" %}
لن يتم تحديث إصدارات Dev والإصدارات ذاتية الضخ تلقائيًا
{% endhint %}

![Windows Taskbar](https://github.com/PreMiD/PreMiD/raw/master/wiki/assets/CheckForUpdates.png)

### تأكد من تمكين Discord Rich Presence في الإعدادات

![Discord Game Activity](https://github.com/PreMiD/PreMiD/raw/master/wiki/assets/GameActivity.png)

### أعد تحميل الصفحة

يمكنك الضغط على ** Strg + R ** / ** F5 ** أو ** CMD + R ** على لوحة المفاتيح أيضًا بدلاً من البحث عن زر التحديث.

### أعد تشغيل المتصفح

** Alt + F4 ** يقوم بعمل جيد للغاية. \ (عليك أن تبدأ متصفحك مرة أخرى بوضوح \)

### تعطيل الإضافات الخاصة بك

تعطيل جميع الإضافات الخاصة بك ومعرفة ما إذا كان يعمل مرة أخرى.
إذا كانت الإجابة بنعم ، فحاول تمكين الإضافات الخاصة بك خطوة بخطوة وأخبرنا بالملحق الذي كسر PreMiD.

### إعادة تشغيل PreMiD \ (التطبيق \)

![Windows Taskbar](https://github.com/PreMiD/PreMiD/raw/master/wiki/assets/Quit.png)

يجب عليك إعادة تشغيل PreMiD.

### تحديث / إعادة تشغيل الديسكورد

اضغط ** Strg + R ** أو ** CMD + R ** على لوحة المفاتيح أو أعد تشغيل الديسكورد يدويًا.

### إعادة تشغيل جهاز الكمبيوتر الخاص بك

أتمنى أن تعرف كيفية إعادة تشغيل الكمبيوتر.

### إعادة تثبيت PreMiD

في بعض الأحيان ، يوجد خطأ في الملفات ... يمكن العثور على دروس للتثبيت [هنا](../altthbyt/application.md).

### الإزالة اليدوية

{% tabs %}
{% tab title="Windows" %}
1. Go to `C:\Users\USER\AppData\Local` وحذف المجلد `premid`
2. Go to `C:\Users\USER\AppData\Roaming` وحذف المجلد`PreMiD`
{% endtab %}

{% tab title="Mac OS" %}
Go to `YOURDISK:/users/USER/~Library/Application Support` وحذف المجلد `PreMiD`
{% endtab %}
{% endtabs %}

منشن مشرف في  [سيرفر الديسكورد](https://discord.gg/WvfVZ8T) إذا لم يساعد أي من هذه الخطوات.

## هذا لم يحل مشكلتي

You can either:

* [افتح مشكلة](https://github.com/PreMiD/PreMiD/issues/new/choose) على [GitHub](https://github.com/PreMiD/PreMiD)
* اسأل الدعم في [\#support](https://discord.gg/WvfVZ8T)

  


