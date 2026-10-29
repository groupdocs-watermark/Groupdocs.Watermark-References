---
title: "FileType"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يمثل نوع الملف."
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

| الاسم | الوصف |
| --- | --- |
| [Extension](../../groupdocs.watermark.common/filetype/extension) { get; } | يسترجع لاحقة اسم الملف (بما في ذلك النقطة ".") مثال: ".doc". |
| [FileFormatName](../../groupdocs.watermark.common/filetype/fileformatname) { get; } | يسترجع اسم نوع الملف مثال: "Microsoft Word Document". |
| [FormatFamily](../../groupdocs.watermark.common/filetype/formatfamily) { get; } | يسترجع عائلة الصيغة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromExtension](../../groupdocs.watermark.common/filetype/fromextension)(string) | يقوم بربط امتداد الملف بنوع الملف. |
| [Equals](../../groupdocs.watermark.common/filetype/equals#equals)(FileType) | يحدد ما إذا كان الـ [`FileType`](../filetype) الحالي هو نفسه ككائن الـ [`FileType`](../filetype) المحدد. |
| override [Equals](../../groupdocs.watermark.common/filetype/equals#equals_1)(object) | يحدد ما إذا كان [`FileType`](../filetype) الحالي هو نفسه الكائن المحدد. |
| override [GetHashCode](../../groupdocs.watermark.common/filetype/gethashcode)() | يعيد رمز تجزئة (hash code) لكائن [`FileType`](../filetype) الحالي. |
| override [ToString](../../groupdocs.watermark.common/filetype/tostring)() | يعيد سلسلة نصية تمثل الكائن الحالي. |
| static [GetSupportedFileTypes](../../groupdocs.watermark.common/filetype/getsupportedfiletypes)() | يسترجع أنواع الملفات المدعومة. |
| [operator ==](../../groupdocs.watermark.common/filetype/op_equality) | يحدد ما إذا كان كائنان من نوع [`FileType`](../filetype) متطابقين. |
| [operator !=](../../groupdocs.watermark.common/filetype/op_inequality) | يحدد ما إذا كان كائنان من نوع [`FileType`](../filetype) غير متطابقين. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| static readonly [BMP](../../groupdocs.watermark.common/filetype/bmp) | الملفات ذات الامتداد .BMP تمثل ملفات صورة نقطية (Bitmap Image) تُستخدم لتخزين الصور الرقمية النقطية. هذه الصور مستقلة عن محول الرسومات وتُعرف أيضًا بملف الصورة النقطية المستقلة عن الجهاز (DIB). تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/bmp/). |
| static readonly [DOC](../../groupdocs.watermark.common/filetype/doc) | الملفات ذات الامتداد .doc تمثل مستندات تم إنشاؤها بواسطة Microsoft Word أو برامج معالجة النصوص الأخرى بصيغة ملف ثنائي. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/doc/). |
| static readonly [DOCM](../../groupdocs.watermark.common/filetype/docm) | ملفات DOCM هي مستندات تم إنشاؤها بواسطة Microsoft Word 2007 أو إصدارات أعلى مع إمكانية تشغيل الماكرو. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/docm/). |
| static readonly [DOCX](../../groupdocs.watermark.common/filetype/docx) | DOCX هو تنسيق معروف لمستندات Microsoft Word. تم تقديمه منذ عام 2007 مع إصدار Microsoft Office 2007، حيث تم تغيير بنية هذا التنسيق الجديد من ثنائي بسيط إلى مزيج من ملفات XML والملفات الثنائية. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/docx/). |
| static readonly [DOT](../../groupdocs.watermark.common/filetype/dot) | الملفات ذات الامتداد .DOT هي ملفات قالب تم إنشاؤها بواسطة Microsoft Word لتحتوي على إعدادات مسبقة لتوليد ملفات DOC أو DOCX إضافية. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/dot/). |
| static readonly [DOTM](../../groupdocs.watermark.common/filetype/dotm) | الملف ذو الامتداد DOTM يمثل ملف قالب تم إنشاؤه باستخدام Microsoft Word 2007 أو إصدارات أعلى. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/dotm/). |
| static readonly [DOTX](../../groupdocs.watermark.common/filetype/dotx) | الملفات ذات الامتداد DOTX هي ملفات قالب تم إنشاؤها بواسطة Microsoft Word لتحتوي على إعدادات مسبقة لتوليد ملفات DOCX إضافية. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/dotx/). |
| static readonly [EML](../../groupdocs.watermark.common/filetype/eml) | تنسيق ملف EML يمثل رسائل البريد الإلكتروني المحفوظة باستخدام Outlook وتطبيقات أخرى ذات صلة. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/email/eml/). |
| static readonly [EMLX](../../groupdocs.watermark.common/filetype/emlx) | تنسيق ملف EMLX تم تنفيذه وتطويره من قبل Apple. يستخدم تطبيق Apple Mail تنسيق EMLX لتصدير رسائل البريد الإلكتروني. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/email/emlx/). |
| static readonly [FlatOpc](../../groupdocs.watermark.common/filetype/flatopc) | Office Open XML WordprocessingML مخزن في ملف XML مسطح بدلاً من حزمة ZIP (.xml). تعرف على المزيد حول هذا التنسيق [هنا](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [FlatOpcMacroEnabled](../../groupdocs.watermark.common/filetype/flatopcmacroenabled) | Office Open XML WordprocessingML مستند مُمكّن بالماكرو مخزن في ملف XML مسطح بدلاً من حزمة ZIP (.xml). تعرف على المزيد حول هذا التنسيق [هنا](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [FlatOpcTemplate](../../groupdocs.watermark.common/filetype/flatopctemplate) | Office Open XML WordprocessingML قالب (خالٍ من الماكرو) مخزن في ملف XML مسطح بدلاً من حزمة ZIP (.xml). تعرف على المزيد حول هذا التنسيق [هنا](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [FlatOpcTemplateMacroEnabled](../../groupdocs.watermark.common/filetype/flatopctemplatemacroenabled) | Office Open XML WordprocessingML قالب مُمكّن بالماكرو مخزن في ملف XML مسطح بدلاً من حزمة ZIP (.xml). تعرف على المزيد حول هذا التنسيق [هنا](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [GIF](../../groupdocs.watermark.common/filetype/gif) | GIF أو تنسيق التبادل الرسومي هو نوع من الصور المضغوطة بشكل كبير. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/gif/). |
| static readonly [JPEG](../../groupdocs.watermark.common/filetype/jpeg) | JPEG هو نوع من تنسيقات الصور يتم حفظه باستخدام طريقة الضغط الفاقد. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/jpeg/). |
| static readonly [JPF](../../groupdocs.watermark.common/filetype/jpf) | JPEG 2000 (JPF) هو نظام ترميز للصور ومعيار ضغط صور متقدم. صُمم باستخدام تقنية الموجة، ويمكن لـ JPEG 2000 ترميز المحتوى غير الفاقد بأي جودة دفعة واحدة. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/jp2/). |
| static readonly [JPG](../../groupdocs.watermark.common/filetype/jpg) | JPEG هو نوع من تنسيقات الصور يتم حفظه باستخدام طريقة الضغط الفاقد. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/jpeg/). |
| static readonly [JPM](../../groupdocs.watermark.common/filetype/jpm) | JPEG 2000 (JPM) هو نظام ترميز صور ومعيار ضغط صور متقدم. صُمم، باستخدام تقنية الموجات، يمكن لـ JPEG 2000 ترميز محتوى غير فقداني بأي جودة في آن واحد. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/jp2/). |
| static readonly [JPX](../../groupdocs.watermark.common/filetype/jpx) | JPEG 2000 (JPX) هو نظام ترميز صور ومعيار ضغط صور متقدم. صُمم، باستخدام تقنية الموجات، يمكن لـ JPEG 2000 ترميز محتوى غير فقداني بأي جودة في آن واحد. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/jp2/). |
| static readonly [MSG](../../groupdocs.watermark.common/filetype/msg) | MSG هو تنسيق ملف يستخدمه Microsoft Outlook و Exchange لتخزين رسائل البريد الإلكتروني، جهات الاتصال، المواعيد، أو مهام أخرى. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/email/msg/). |
| static readonly [ODT](../../groupdocs.watermark.common/filetype/odt) | ملفات ODT هي نوع من المستندات التي تُنشأ باستخدام تطبيقات معالجة النصوص المستندة إلى تنسيق ملف نص OpenDocument. تُنشأ هذه باستخدام تطبيقات معالجة النصوص مثل OpenOffice Writer المجاني ويمكنها احتواء محتوى مثل النصوص، الصور، الكائنات والأنماط. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/odt/). |
| static readonly [OFT](../../groupdocs.watermark.common/filetype/oft) | الملفات ذات الامتداد .OFT تمثل قوالب رسائل تُنشأ باستخدام Microsoft Outlook. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/email/oft/). |
| static readonly [OOXML](../../groupdocs.watermark.common/filetype/ooxml) | ملف Office Open XML (.ooxml). |
| static readonly [PDF](../../groupdocs.watermark.common/filetype/pdf) | Portable Document Format (PDF) هو نوع من المستندات تم إنشاؤه بواسطة Adobe في التسعينيات. كان هدف هذا التنسيق تقديم معيار لتمثيل المستندات والمواد المرجعية الأخرى في صيغة مستقلة عن برامج التطبيقات، الأجهزة، وكذلك نظام التشغيل. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/view/pdf/). |
| static readonly [PNG](../../groupdocs.watermark.common/filetype/png) | PNG، Portable Network Graphics، يشير إلى نوع من تنسيقات ملفات الصور النقطية التي تستخدم ضغط غير فقدان. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/png/). |
| static readonly [POTM](../../groupdocs.watermark.common/filetype/potm) | الملفات ذات الامتداد POTM هي قوالب Microsoft PowerPoint مع دعم للماكرو. تُنشأ ملفات POTM باستخدام PowerPoint 2007 أو أحدث وتحتوي على إعدادات افتراضية يمكن استخدامها لإنشاء ملفات عروض تقديمية أخرى. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/potm/). |
| static readonly [POTX](../../groupdocs.watermark.common/filetype/potx) | الملفات ذات الامتداد .POTX تمثل قوالب عروض Microsoft PowerPoint التي تُنشأ باستخدام Microsoft PowerPoint 2007 وما فوق. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/potx/). |
| static readonly [PPS](../../groupdocs.watermark.common/filetype/pps) | PPS، PowerPoint Slide Show، تُنشأ الملفات باستخدام Microsoft PowerPoint لأغراض عرض الشرائح. قراءة وإنشاء ملفات PPS مدعومة بواسطة Microsoft PowerPoint 97-2003. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/pps/). |
| static readonly [PPSM](../../groupdocs.watermark.common/filetype/ppsm) | الملفات ذات الامتداد PPSM تمثل تنسيق عرض شرائح مدعوم بالماكرو تم إنشاؤه باستخدام Microsoft PowerPoint 2007 أو أعلى. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/ppsm/). |
| static readonly [PPSX](../../groupdocs.watermark.common/filetype/ppsx) | PPSX، Power Point Slide Show، تُنشأ الملفات باستخدام Microsoft PowerPoint 2007 وما فوق لأغراض عرض الشرائح. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/ppsx/). |
| static readonly [PPT](../../groupdocs.watermark.common/filetype/ppt) | الملف ذو الامتداد PPT يمثل ملف PowerPoint يتألف من مجموعة من الشرائح للعرض كعرض شرائح. يحدد تنسيق الملف الثنائي المستخدم بواسطة Microsoft PowerPoint 97-2003. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/ppt/). |
| static readonly [PPTM](../../groupdocs.watermark.common/filetype/pptm) | الملفات ذات الامتداد PPTM هي ملفات عرض تقديمي مدعومة بالماكرو تم إنشاؤها باستخدام Microsoft PowerPoint 2007 أو الإصدارات الأحدث. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/pptm/). |
| static readonly [PPTX](../../groupdocs.watermark.common/filetype/pptx) | الملفات ذات الامتداد PPTX هي ملفات عرض تم إنشاؤها باستخدام تطبيق Microsoft PowerPoint الشائع. على عكس النسخة السابقة من تنسيق ملف العرض PPT الذي كان ثنائيًا، يعتمد تنسيق PPTX على تنسيق عرض Microsoft PowerPoint Open XML. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/presentation/pptx/). |
| static readonly [RTF](../../groupdocs.watermark.common/filetype/rtf) | تم تقديمه وتوثيقه من قبل مايكروسوفت، يمثل تنسيق النص الغني (RTF) طريقة لتشفير النص المنسق والرسومات للاستخدام داخل التطبيقات. يسهل التنسيق تبادل المستندات عبر الأنظمة مع منتجات مايكروسوفت الأخرى، وبالتالي يخدم هدف التوافقية. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/word-processing/rtf/). |
| static readonly [TIF](../../groupdocs.watermark.common/filetype/tif) | TIFF أو TIF، تنسيق ملف الصورة الموسومة، يمثل صورًا نقطية مخصصة للاستخدام على مجموعة متنوعة من الأجهزة التي تتوافق مع معيار هذا التنسيق. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/tiff/). |
| static readonly [TIFF](../../groupdocs.watermark.common/filetype/tiff) | TIFF أو TIF، تنسيق ملف الصورة الموسومة، يمثل صورًا نقطية مخصصة للاستخدام على مجموعة متنوعة من الأجهزة التي تتوافق مع معيار هذا التنسيق. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/tiff/). |
| static readonly [Unknown](../../groupdocs.watermark.common/filetype/unknown) | يمثل نوع ملف غير معروف. |
| static readonly [VDW](../../groupdocs.watermark.common/filetype/vdw) | VDW هو تنسيق ملف خدمة رسومات Visio الذي يحدد التدفقات والتخزينات المطلوبة لتصيير رسم ويب. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/web/vdw/). |
| static readonly [VDX](../../groupdocs.watermark.common/filetype/vdx) | أي رسم أو مخطط تم إنشاؤه في Microsoft Visio، ولكن تم حفظه بتنسيق XML يحمل امتداد .VDX. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/vdx/). |
| static readonly [VSD](../../groupdocs.watermark.common/filetype/vsd) | ملفات VSD هي رسومات تم إنشاؤها باستخدام تطبيق Microsoft Visio لتمثيل مجموعة متنوعة من الكائنات الرسومية والاتصالات بينها. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/vsd/). |
| static readonly [VSDM](../../groupdocs.watermark.common/filetype/vsdm) | الملفات ذات الامتداد VSDM هي ملفات رسومات تم إنشاؤها باستخدام تطبيق Microsoft Visio وتدعم الماكرو. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/vsdm/). |
| static readonly [VSDX](../../groupdocs.watermark.common/filetype/vsdx) | الملفات ذات الامتداد .VSDX تمثل تنسيق ملف Microsoft Visio الذي تم تقديمه بدءًا من Microsoft Office 2013 فصاعدًا. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/vsdx/). |
| static readonly [VSS](../../groupdocs.watermark.common/filetype/vss) | VSS هي ملفات قوالب تم إنشاؤها باستخدام Microsoft Visio 2007 وما قبله. توفر ملفات القوالب كائنات رسومية يمكن تضمينها في رسم Visio بامتداد .VSD. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/vss/). |
| static readonly [VSSM](../../groupdocs.watermark.common/filetype/vssm) | الملفات ذات الامتداد .VSSM هي ملفات قوالب Microsoft Visio التي تدعم الماكرو. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/vssm/). |
| static readonly [VSSX](../../groupdocs.watermark.common/filetype/vssx) | الملفات ذات الامتداد .VSSX هي قوالب رسومات تم إنشاؤها باستخدام Microsoft Visio 2013 وما بعده. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/vssx/). |
| static readonly [VST](../../groupdocs.watermark.common/filetype/vst) | الملفات ذات الامتداد VST هي ملفات صور متجهة تم إنشاؤها باستخدام Microsoft Visio وتعمل كقالب لإنشاء ملفات أخرى. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/vst/). |
| static readonly [VSTM](../../groupdocs.watermark.common/filetype/vstm) | الملفات ذات الامتداد VSTM هي ملفات قوالب تم إنشاؤها باستخدام Microsoft Visio وتدعم الماكرو. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/vstm/). |
| static readonly [VSTX](../../groupdocs.watermark.common/filetype/vstx) | الملفات ذات الامتداد VSTX هي ملفات قوالب رسومات تم إنشاؤها باستخدام Microsoft Visio 2013 وما بعده. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/vstx/). |
| static readonly [VSX](../../groupdocs.watermark.common/filetype/vsx) | الملفات ذات الامتداد .VSX تشير إلى قوالب تتكون من رسومات وأشكال تُستخدم لإنشاء مخططات في Microsoft Visio. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/vsx/). |
| static readonly [VTX](../../groupdocs.watermark.common/filetype/vtx) | الملف ذو الامتداد VTX هو قالب رسم Microsoft Visio يتم حفظه على القرص بتنسيق ملف XML. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/vtx/). |
| static readonly [WEBP](../../groupdocs.watermark.common/filetype/webp) | WebP، الذي قدمته Google، هو تنسيق ملف صورة ويب نقطية حديث يعتمد على الضغط غير الفاقد والفقدان. يوفر نفس جودة الصورة مع تقليل حجم الصورة بشكل كبير. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/image/webp/). |
| static readonly [XLS](../../groupdocs.watermark.common/filetype/xls) | الملفات ذات الامتداد XLS تمثل تنسيق ملف Excel الثنائي. يمكن إنشاء مثل هذه الملفات بواسطة Microsoft Excel وكذلك برامج جداول البيانات المشابهة مثل OpenOffice Calc أو Apple Numbers. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/specification/spreadsheet/xls/). |
| static readonly [XLSB](../../groupdocs.watermark.common/filetype/xlsb) | تنسيق ملف XLSB يحدد تنسيق ملف Excel الثنائي، وهو مجموعة من السجلات والهياكل التي تحدد محتوى دفتر عمل Excel. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/specification/spreadsheet/xlsb/). |
| static readonly [XLSM](../../groupdocs.watermark.common/filetype/xlsm) | الملفات ذات امتداد XLSM هي نوع من ملفات الجداول الإلكترونية التي تدعم الماكرو. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/specification/spreadsheet/xlsm/). |
| static readonly [XLSX](../../groupdocs.watermark.common/filetype/xlsx) | XLSX هو تنسيق معروف لمستندات Microsoft Excel تم تقديمه من قبل Microsoft مع إصدار Microsoft Office 2007. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/specification/spreadsheet/xlsx/). |
| static readonly [XLT](../../groupdocs.watermark.common/filetype/xlt) | الملفات ذات امتداد .XLT هي ملفات قالب تم إنشاؤها باستخدام Microsoft Excel وهو تطبيق جداول إلكترونية يأتي كجزء من مجموعة Microsoft Office. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/specification/spreadsheet/xlt/). |
| static readonly [XLTM](../../groupdocs.watermark.common/filetype/xltm) | امتداد ملف XLTM يمثل الملفات التي يتم إنشاؤها بواسطة Microsoft Excel كملفات قالب مفعلة بالماكرو. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/specification/spreadsheet/xltm/). |
| static readonly [XLTX](../../groupdocs.watermark.common/filetype/xltx) | الملفات ذات امتداد XLTX تمثل ملفات قالب Microsoft Excel المستندة إلى مواصفات تنسيق ملف Office OpenXML. تعرف على المزيد حول هذا التنسيق [هنا](https://wiki.fileformat.com/specification/spreadsheet/xltx/). |

### ملاحظات

هذه الفئة توفر طرقًا للحصول على قائمة بجميع أنواع الملفات المدعومة من قبل **GroupDocs.Watermark**.**المزيد**

* [Supported Document Formats](https://docs.groupdocs.com/display/watermarknet/Supported+Document+Formats)
* [Get supported file formats](https://docs.groupdocs.com/display/watermarknet/Get+supported+file+formats)
* [Get document info](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### انظر أيضاً

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
