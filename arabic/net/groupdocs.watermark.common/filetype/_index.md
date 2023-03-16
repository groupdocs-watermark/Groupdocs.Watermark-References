---
title: FileType
second_title: GroupDocs.Watermark لـ .NET API Reference
description: يمثل نوع الملف.
type: docs
weight: 40
url: /ar/net/groupdocs.watermark.common/filetype/
---
## FileType class

يمثل نوع الملف.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Extension](../../groupdocs.watermark.common/filetype/extension) { get; } | يحصل على لاحقة اسم الملف (بما في ذلك النقطة ".") على سبيل المثال ، ".doc" . |
| [FileFormatName](../../groupdocs.watermark.common/filetype/fileformatname) { get; } | الحصول على اسم نوع الملف ، على سبيل المثال ، "مستند Microsoft Word" . |
| [FormatFamily](../../groupdocs.watermark.common/filetype/formatfamily) { get; } | يحصل على عائلة التنسيق . |

## طُرق

| اسم | وصف |
| --- | --- |
| static [FromExtension](../../groupdocs.watermark.common/filetype/fromextension)(string) | تعيين امتداد الملف لنوع الملف. |
| [Equals](../../groupdocs.watermark.common/filetype/equals#equals)(FileType) | يحدد ما إذا كان التيار[`FileType`](../filetype) هو نفس المحدد[`FileType`](../filetype) الكائن . |
| override [Equals](../../groupdocs.watermark.common/filetype/equals#equals_1)(object) | يحدد ما إذا كان التيار[`FileType`](../filetype) هو نفس الكائن المحدد. |
| override [GetHashCode](../../groupdocs.watermark.common/filetype/gethashcode)() | إرجاع رمز تجزئة للتيار[`FileType`](../filetype) الكائن . |
| override [ToString](../../groupdocs.watermark.common/filetype/tostring)() | إرجاع سلسلة تمثل الكائن الحالي. |
| static [GetSupportedFileTypes](../../groupdocs.watermark.common/filetype/getsupportedfiletypes)() | استرداد أنواع الملفات المدعومة. |
| [operator ==](../../groupdocs.watermark.common/filetype/op_equality) | تحديد ما إذا كان اثنان[`FileType`](../filetype) الكائنات هي نفسها. |
| [operator !=](../../groupdocs.watermark.common/filetype/op_inequality) | تحديد ما إذا كان اثنان[`FileType`](../filetype) الكائنات ليست هي نفسها. |

## مجالات

| اسم | وصف |
| --- | --- |
| static readonly [BMP](../../groupdocs.watermark.common/filetype/bmp) | الملفات ذات الامتداد .BMP تمثل ملفات الصور النقطية المستخدمة لتخزين الصور الرقمية. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/bmp/) . |
| static readonly [DOC](../../groupdocs.watermark.common/filetype/doc) | تمثل الملفات ذات الامتداد .doc المستندات التي تم إنشاؤها بواسطة Microsoft Word أو مستندات معالجة النصوص الأخرى بتنسيق ملف ثنائي. تعرف على المزيد حول هذا الملف format [هنا](https://wiki.fileformat.com/word-processing/doc/) . |
| static readonly [DOCM](../../groupdocs.watermark.common/filetype/docm) | ملفات DOCM هي Microsoft Word 2007 أو مستندات تم إنشاؤها بأعلى مع إمكانية تشغيل وحدات الماكرو. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/docm/) . |
| static readonly [DOCX](../../groupdocs.watermark.common/filetype/docx) | DOCX هو تنسيق معروف لمستندات Microsoft Word. تم تقديمه من عام 2007 مع الإصدار من Microsoft Office 2007 ، تم تغيير هيكل تنسيق المستند الجديد هذا من عادي binary إلى مجموعة من ملفات XML والملفات الثنائية. تعرف على المزيد حول هذا الملف format [هنا](https://wiki.fileformat.com/word-processing/docx/) . |
| static readonly [DOT](../../groupdocs.watermark.common/filetype/dot) | الملفات ذات الامتداد .DOT هي ملفات قوالب تم إنشاؤها بواسطة Microsoft Word للحصول على إعدادات مهيأة مسبقًا لتوليد المزيد من ملفات DOC أو DOCX. تعرف على المزيد حول هذا الملف format [هنا](https://wiki.fileformat.com/word-processing/dot/) . |
| static readonly [DOTM](../../groupdocs.watermark.common/filetype/dotm) | يمثل ملف بامتداد DOTM ملف قالب تم إنشاؤه باستخدام Microsoft Word 2007 أو أعلى . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/dotm/) . |
| static readonly [DOTX](../../groupdocs.watermark.common/filetype/dotx) | الملفات ذات امتداد DOTX هي ملفات قوالب تم إنشاؤها بواسطة Microsoft Word للحصول على إعدادات مهيأة مسبقًا لتوليد المزيد من ملفات DOCX. تعرف على المزيد حول هذا الملف format [هنا](https://wiki.fileformat.com/word-processing/dotx/) . |
| static readonly [EML](../../groupdocs.watermark.common/filetype/eml) | يمثل تنسيق ملف EML رسائل البريد الإلكتروني المحفوظة باستخدام Outlook والتطبيقات الأخرى ذات الصلة. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/email/eml/) . |
| static readonly [EMLX](../../groupdocs.watermark.common/filetype/emlx) | تم تنفيذ وتطوير تنسيق ملف EMLX بواسطة Apple. يستخدم تطبيق Apple Mail تنسيق ملف EMLX لتصدير رسائل البريد الإلكتروني. تعرف على المزيد حول هذا الملف format [هنا](https://wiki.fileformat.com/email/emlx/) . |
| static readonly [FlatOpc](../../groupdocs.watermark.common/filetype/flatopc) | Office Open XML WordprocessingML مخزّن في ملف XML ثابت بدلاً من حزمة ZIP (.xml) . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [FlatOpcMacroEnabled](../../groupdocs.watermark.common/filetype/flatopcmacroenabled) | Office Open XML WordprocessingML مستند ممكّن بماكرو مخزن في ملف XML مسطح بدلاً من حزمة ZIP (.xml) . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [FlatOpcTemplate](../../groupdocs.watermark.common/filetype/flatopctemplate) | Office Open XML WordprocessingML Template (خالٍ من الماكرو) المخزن في ملف XML مسطح بدلاً من حزمة ZIP (.xml) . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [FlatOpcTemplateMacroEnabled](../../groupdocs.watermark.common/filetype/flatopctemplatemacroenabled) | Office Open XML WordprocessingML قالب ممكّن بماكرو مخزن في ملف XML مسطح بدلاً من حزمة ZIP (.xml) . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [GIF](../../groupdocs.watermark.common/filetype/gif) | تنسيق GIF أو Graphical Interchange Format هو نوع من الصور المضغوطة بشدة. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/gif/) . |
| static readonly [JPEG](../../groupdocs.watermark.common/filetype/jpeg) | JPEG هو نوع من تنسيق الصورة يتم حفظه باستخدام طريقة الضغط مع فقد البيانات . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/jpeg/) . |
| static readonly [JPF](../../groupdocs.watermark.common/filetype/jpf) | JPEG 2000 (JPF) هو نظام ترميز للصور وأحدث معايير ضغط الصور. تم تصميمه ، باستخدام تقنية المويجات ، يمكن لـ JPEG 2000 ترميز المحتوى غير المفقود بأي جودة في وقت واحد. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/jp2/) . |
| static readonly [JPG](../../groupdocs.watermark.common/filetype/jpg) | JPEG هو نوع من تنسيق الصورة يتم حفظه باستخدام طريقة الضغط مع فقد البيانات . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/jpeg/) . |
| static readonly [JPM](../../groupdocs.watermark.common/filetype/jpm) | JPEG 2000 (JPM) هو نظام ترميز للصور وأحدث معايير ضغط الصور. تم تصميمه ، باستخدام تقنية المويجات ، يمكن لـ JPEG 2000 ترميز المحتوى غير المفقود بأي جودة في وقت واحد. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/jp2/) . |
| static readonly [JPX](../../groupdocs.watermark.common/filetype/jpx) | JPEG 2000 (JPX) هو نظام ترميز للصور وأحدث معايير ضغط الصور. تم تصميمه ، باستخدام تقنية المويجات ، يمكن لـ JPEG 2000 ترميز المحتوى غير المفقود بأي جودة في وقت واحد. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/jp2/) . |
| static readonly [MSG](../../groupdocs.watermark.common/filetype/msg) | MSG هو تنسيق ملف يستخدمه Microsoft Outlook و Exchange لتخزين رسائل البريد الإلكتروني أو جهات الاتصال أو موعد أو مهام أخرى. تعرف على المزيد حول هذا الملف format [هنا](https://wiki.fileformat.com/email/msg/) . |
| static readonly [ODT](../../groupdocs.watermark.common/filetype/odt) | ملفات ODT هي نوع من المستندات التي تم إنشاؤها باستخدام تطبيقات معالجة الكلمات التي تعتمد على تنسيق OpenDocument Text File. يتم إنشاؤها باستخدام تطبيقات معالج الكلمات مثل OpenOffice Writer و يمكنه الاحتفاظ بمحتوى مثل النص والصور والكائنات والأنماط. تعرف على المزيد حول هذا الملف format [هنا](https://wiki.fileformat.com/word-processing/odt/) . |
| static readonly [OFT](../../groupdocs.watermark.common/filetype/oft) | تمثل الملفات ذات الامتداد .OFT ملفات قوالب الرسائل التي تم إنشاؤها باستخدام Microsoft Outlook . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/email/oft/) . |
| static readonly [OOXML](../../groupdocs.watermark.common/filetype/ooxml) | Office فتح ملف xml (.ooxml) . |
| static readonly [PDF](../../groupdocs.watermark.common/filetype/pdf) | تنسيق المستند المحمول (PDF) هو نوع من المستندات التي أنشأتها Adobe في التسعينيات. كان الغرض من تنسيق الملف هذا هو تقديم معيار لتمثيل المستندات والمواد المرجعية الأخرى في تنسيق مستقل عن برامج التطبيقات والأجهزة وكذلك نظام التشغيل. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/view/pdf/) . |
| static readonly [PNG](../../groupdocs.watermark.common/filetype/png) | PNG ، رسومات الشبكة المحمولة ، يشير إلى نوع من تنسيق ملف الصورة النقطية الذي يستخدم ضغط بدون فقدان . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/png/) . |
| static readonly [POTM](../../groupdocs.watermark.common/filetype/potm) | الملفات ذات الامتداد POTM هي ملفات قوالب Microsoft PowerPoint مع دعم لوحدات الماكرو. يتم إنشاء ملفات POTM باستخدام PowerPoint 2007 أو أعلى وتحتوي على الإعدادات الافتراضية التي يمكن استخدامها لإنشاء ملفات عرض تقديمية أخرى. تعرف على المزيد حول هذا الملف format [هنا](https://wiki.fileformat.com/presentation/potm/) . |
| static readonly [POTX](../../groupdocs.watermark.common/filetype/potx) | تمثل الملفات ذات الامتداد .POTX عروض تقديمية لقوالب Microsoft PowerPoint التي تم إنشاؤها باستخدام Microsoft PowerPoint 2007 والإصدارات الأحدث. تعرف على المزيد حول هذا الملف format [هنا](https://wiki.fileformat.com/presentation/potx/) . |
| static readonly [PPS](../../groupdocs.watermark.common/filetype/pps) | PPS ، عرض شرائح PowerPoint ، يتم إنشاء الملفات باستخدام Microsoft PowerPoint لغرض عرض الشرائح. يدعم Microsoft PowerPoint 97-2003 قراءة وإنشاء ملف PPS. تعرف على المزيد حول هذا الملف format [هنا](https://wiki.fileformat.com/presentation/pps/) . |
| static readonly [PPSM](../../groupdocs.watermark.common/filetype/ppsm) | تمثل الملفات ذات الامتداد PPSM تنسيق ملف عرض الشرائح ممكّن بماكرو تم إنشاؤه باستخدام Microsoft PowerPoint 2007 أو إصدار أحدث. تعرف على المزيد حول هذا الملف format [هنا](https://wiki.fileformat.com/presentation/ppsm/) . |
| static readonly [PPSX](../../groupdocs.watermark.common/filetype/ppsx) | PPSX ، عرض شرائح Power Point ، يتم إنشاء الملف باستخدام Microsoft PowerPoint 2007 والإصدارات الأحدث لـ غرض عرض الشرائح. تعرف على المزيد حول هذا الملف format [هنا](https://wiki.fileformat.com/presentation/ppsx/) . |
| static readonly [PPT](../../groupdocs.watermark.common/filetype/ppt) | يمثل ملف بامتداد PPT ملف PowerPoint يتكون من مجموعة من الشرائح لعرضها على هيئة عرض شرائح. تحدد تنسيق الملف الثنائي المستخدم بواسطة Microsoft PowerPoint 97-2003. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/presentation/ppt/) . |
| static readonly [PPTM](../../groupdocs.watermark.common/filetype/pptm) | الملفات ذات الامتداد PPTM هي ملفات عرض تقديمية تم تمكين الماكرو تم إنشاؤها باستخدام Microsoft PowerPoint 2007 أو الإصدارات الأحدث. تعرف على المزيد حول هذا الملف format [هنا](https://wiki.fileformat.com/presentation/pptm/) . |
| static readonly [PPTX](../../groupdocs.watermark.common/filetype/pptx) | الملفات ذات امتداد PPTX هي ملفات عرض تقديمي تم إنشاؤها باستخدام تطبيق Microsoft PowerPoint الشهير . على عكس الإصدار السابق من تنسيق ملف العرض التقديمي PPT الذي كان ثنائيًا ، فإن تنسيق PPTX يعتمد على على تنسيق ملف العرض التقديمي XML المفتوح لبرنامج Microsoft PowerPoint. تعرف على المزيد حول هذا الملف format [هنا](https://wiki.fileformat.com/presentation/pptx/) . |
| static readonly [RTF](../../groupdocs.watermark.common/filetype/rtf) | تم تقديمه وتوثيقه بواسطة Microsoft ، يمثل Rich Text Format (RTF) طريقة لتشفير النص والرسومات المنسقة لاستخدامها في التطبيقات. يسهل التنسيق تبادل document عبر الأنظمة الأساسية مع منتجات Microsoft الأخرى ، وبالتالي يخدم الغرض من قابلية التشغيل البيني. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/word-processing/rtf/) . |
| static readonly [TIF](../../groupdocs.watermark.common/filetype/tif) | TIFF أو TIF ، تنسيق ملف الصورة ذي العلامات ، يمثل الصور النقطية المخصصة للاستخدام على مجموعة متنوعة من الأجهزة التي تتوافق مع معيار تنسيق الملف هذا. تعرف على المزيد حول هذا الملف format [هنا](https://wiki.fileformat.com/image/tiff/) . |
| static readonly [TIFF](../../groupdocs.watermark.common/filetype/tiff) | TIFF أو TIF ، تنسيق ملف الصورة ذي العلامات ، يمثل الصور النقطية المخصصة للاستخدام على مجموعة متنوعة من الأجهزة التي تتوافق مع معيار تنسيق الملف هذا. تعرف على المزيد حول هذا الملف format [هنا](https://wiki.fileformat.com/image/tiff/) . |
| static readonly [Unknown](../../groupdocs.watermark.common/filetype/unknown) | يمثل نوع ملف غير معروف. |
| static readonly [VDW](../../groupdocs.watermark.common/filetype/vdw) | VDW هو تنسيق ملف Visio Graphics Service الذي يحدد التدفقات والمخازن المطلوبة لعرض رسم ويب. تعرف على المزيد حول هذا الملف format [هنا](https://wiki.fileformat.com/web/vdw/) . |
| static readonly [VDX](../../groupdocs.watermark.common/filetype/vdx) | أي رسم أو مخطط تم إنشاؤه في Microsoft Visio ، ولكن تم حفظه بتنسيق XML له ملحق .VDX . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/vdx/) . |
| static readonly [VSD](../../groupdocs.watermark.common/filetype/vsd) | ملفات VSD هي رسومات تم إنشاؤها باستخدام تطبيق Microsoft Visio لتمثيل مجموعة متنوعة من الكائنات الرسومية والترابط بينها. تعرف على المزيد حول هذا الملف format [هنا](https://wiki.fileformat.com/image/vsd/) . |
| static readonly [VSDM](../../groupdocs.watermark.common/filetype/vsdm) | الملفات ذات الامتداد VSDM هي ملفات رسم تم إنشاؤها باستخدام تطبيق Microsoft Visio الذي يدعم وحدات الماكرو . تعرف على المزيد حول تنسيق الملف هذا [هنا](https://wiki.fileformat.com/image/vsdm/) . |
| static readonly [VSDX](../../groupdocs.watermark.common/filetype/vsdx) | تمثل الملفات ذات الامتداد .VSDX تنسيق ملف Microsoft Visio المقدم من Microsoft Office 2013 فصاعدًا. تعرف على المزيد حول هذا الملف format [هنا](https://wiki.fileformat.com/image/vsdx/) . |
| static readonly [VSS](../../groupdocs.watermark.common/filetype/vss) | VSS هي ملفات استنسل تم إنشاؤها باستخدام Microsoft Visio 2007 والإصدارات الأقدم. توفر ملفات الاستنسل draw كائنات يمكن تضمينها في رسم Visio .VSD. تعرف على المزيد حول هذا الملف format [هنا](https://wiki.fileformat.com/image/vss/) . |
| static readonly [VSSM](../../groupdocs.watermark.common/filetype/vssm) | الملفات ذات الامتداد .VSSM هي ملفات Microsoft Visio Stencil التي تدعم توفير الدعم لوحدات الماكرو . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/vssm/) . |
| static readonly [VSSX](../../groupdocs.watermark.common/filetype/vssx) | تقوم الملفات ذات الامتداد .VSSX برسم قوالب استنسل تم إنشاؤها باستخدام Microsoft Visio 2013 وما فوق. تعرف على المزيد حول تنسيق الملف هذا [هنا](https://wiki.fileformat.com/image/vssx/) . |
| static readonly [VST](../../groupdocs.watermark.common/filetype/vst) | الملفات ذات الامتداد VST هي ملفات صور متجهة تم إنشاؤها باستخدام Microsoft Visio وتعمل كقالب لـ إنشاء ملفات أخرى. تعرف على المزيد حول هذا الملف format [هنا](https://wiki.fileformat.com/image/vst/) . |
| static readonly [VSTM](../../groupdocs.watermark.common/filetype/vstm) | الملفات ذات الامتداد VSTM هي ملفات قوالب تم إنشاؤها باستخدام Microsoft Visio التي تدعم وحدات الماكرو . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/vstm/) . |
| static readonly [VSTX](../../groupdocs.watermark.common/filetype/vstx) | الملفات ذات الامتدادات VSTX هي ملفات قوالب رسم تم إنشاؤها باستخدام Microsoft Visio 2013 وما فوق. تعرف على المزيد حول تنسيق الملف هذا [هنا](https://wiki.fileformat.com/image/vstx/) . |
| static readonly [VSX](../../groupdocs.watermark.common/filetype/vsx) | تشير الملفات ذات الامتداد .VSX إلى قوالب الإستنسل التي تتكون من الرسومات والأشكال المستخدمة في إنشاء الرسوم التخطيطية في Microsoft Visio. تعرف على المزيد حول هذا الملف format [هنا](https://wiki.fileformat.com/image/vsx/) . |
| static readonly [VTX](../../groupdocs.watermark.common/filetype/vtx) | الملف بملحق VTX هو قالب رسم Microsoft Visio يتم حفظه على قرص بتنسيق ملف XML . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/vtx/) . |
| static readonly [WEBP](../../groupdocs.watermark.common/filetype/webp) | WebP ، الذي قدمته Google ، هو تنسيق ملف صورة ويب نقطية حديث يعتمد على ضغط بدون فقدان و . إنه يوفر نفس جودة الصورة مع تقليل حجم الصورة بشكل كبير . تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/image/webp/) . |
| static readonly [XLS](../../groupdocs.watermark.common/filetype/xls) | تمثل الملفات ذات الامتداد XLS تنسيق ملف Excel الثنائي. يمكن إنشاء مثل هذه الملفات بواسطة Microsoft Excel بالإضافة إلى برامج جداول البيانات المماثلة الأخرى مثل OpenOffice Calc أو Apple Numbers. تعرف على المزيد حول تنسيق الملف هذا[هنا](https://wiki.fileformat.com/specification/spreadsheet/xls/) . |
| static readonly [XLSB](../../groupdocs.watermark.common/filetype/xlsb) | يحدد تنسيق ملف XLSB تنسيق ملف Excel الثنائي ، وهو عبارة عن مجموعة من السجلات والبنى التي تحدد محتوى مصنف Excel. تعرف على المزيد حول هذا الملف format [هنا](https://wiki.fileformat.com/specification/spreadsheet/xlsb/) . |
| static readonly [XLSM](../../groupdocs.watermark.common/filetype/xlsm) | الملفات ذات الامتداد XLSM هي نوع من ملفات Spreasheet التي تدعم وحدات الماكرو. تعرف على المزيد حول هذا الملف format [هنا](https://wiki.fileformat.com/specification/spreadsheet/xlsm/) . |
| static readonly [XLSX](../../groupdocs.watermark.common/filetype/xlsx) | XLSX هو تنسيق معروف لمستندات Microsoft Excel تم تقديمه بواسطة Microsoft مع الإصدار من Microsoft Office 2007. تعرف على المزيد حول تنسيق الملف هذا [هنا](https://wiki.fileformat.com/specification/spreadsheet/xlsx/) . |
| static readonly [XLT](../../groupdocs.watermark.common/filetype/xlt) | الملفات ذات الامتداد .XLT هي ملفات قوالب تم إنشاؤها باستخدام Microsoft Excel وهو تطبيق spreadsheet الذي يأتي كجزء من مجموعة Microsoft Office. تعرف على المزيد حول هذا الملف format [هنا](https://wiki.fileformat.com/specification/spreadsheet/xlt/) . |
| static readonly [XLTM](../../groupdocs.watermark.common/filetype/xltm) | يمثل امتداد الملف XLTM الملفات التي تم إنشاؤها بواسطة Microsoft Excel كملفات قالب تم تمكينها بماكرو . تعرف على المزيد حول هذا الملف format [هنا](https://wiki.fileformat.com/specification/spreadsheet/xltm/) . |
| static readonly [XLTX](../../groupdocs.watermark.common/filetype/xltx) | تمثل الملفات ذات الملحق XLTX ملفات قالب Microsoft Excel التي تستند إلى مواصفات تنسيق ملف Office OpenXML . تعرف على المزيد حول هذا الملف format [هنا](https://wiki.fileformat.com/specification/spreadsheet/xltx/) . |

### ملاحظات

توفر هذه الفئة طرقًا للحصول على قائمة بجميع أنواع الملفات التي يدعمها**GroupDocs.Watermark**.**يتعلم أكثر**

* [تنسيقات المستندات المدعومة](https://docs.groupdocs.com/display/watermarknet/Supported+Document+Formats)
* [احصل على تنسيقات الملفات المدعومة](https://docs.groupdocs.com/display/watermarknet/Get+supported+file+formats)
* [الحصول على معلومات الوثيقة](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### أنظر أيضا

* مساحة الاسم [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* المجسم [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
