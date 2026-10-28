---
title: "PdfPermissions"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل أذونات المستخدمين لمستند PDF."
type: docs
weight: 68
url: /ar/java/com.groupdocs.watermark.contents/pdfpermissions/
---
**Inheritance:**
java.lang.Object
```
public final class PdfPermissions
```

يمثل أذونات المستخدم لمستند PDF.

## الحقول

| حقل | الوصف |
| --- | --- |
|  | [PrintDocument](#PrintDocument) | اطبع المحتوى. |
|
|  | [ModifyContent](#ModifyContent) | عدّل المحتوى. |
|
|  | [ExtractContent](#ExtractContent) | انسخ أو استخرج النص والرسومات من المستند بأي طريقة أخرى. |
|
|  | [ModifyTextAnnotations](#ModifyTextAnnotations) | أضف أو عدّل التعليقات النصية. |
|
|  | [FillForm](#FillForm) | املأ حقول النماذج التفاعلية الموجودة. |
|
|  | [ExtractContentWithDisabilities](#ExtractContentWithDisabilities) | استخرج النص والرسومات. |
|
|  | [AssembleDocument](#AssembleDocument) | جمّع المحتوى. |
|
|  | [PrintingQuality](#PrintingQuality) | اطبع المحتوى إلى تمثيل يمكن من خلاله إنشاء نسخة رقمية دقيقة من مستند PDF. |
|
### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```


اطبع المحتوى.

معالجات الأمان للإصدار 2: اطبع المحتوى.

معالجات الأمان للإصدار 3 أو أعلى: اطبع المحتوى
(ربما ليس بأعلى مستوى جودة، اعتمادًا على ما إذا كان
`#PrintingQuality.PrintingQuality` تم تعيينه أيضًا).


### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```


عدّل المحتوى.

عدّل محتويات المستند بعمليات أخرى
عن تلك التي يتحكم فيها `#ModifyTextAnnotations.ModifyTextAnnotations`، `#FillForm.FillForm`.


### ExtractContent {#ExtractContent}
```
public static final int ExtractContent
```


انسخ أو استخرج النص والرسومات من المستند بأي طريقة أخرى.

معالجات الأمان للإصدار 2: انسخ أو استخرج النص والرسومات من المحتوى،
بما في ذلك استخراج النص والرسومات (دعمًا لإمكانية الوصول للمستخدمين الذين لديهم
إعاقات أو لأغراض أخرى).

معالجات الأمان للإصدار 3 أو أعلى: نسخ أو استخراج النص والرسومات من
المحتوى عبر عمليات غير تلك التي يتحكم بها
`#ExtractContentWithDisabilities.ExtractContentWithDisabilities`.


### ModifyTextAnnotations {#ModifyTextAnnotations}
```
public static final int ModifyTextAnnotations
```


أضف أو عدّل التعليقات النصية.

إضافة أو تعديل تعليقات النص، ملء حقول النماذج التفاعلية،
و، إذا كان `#ModifyContent.ModifyContent` مُعيّنًا أيضًا،
إنشاء أو تعديل حقول النماذج التفاعلية (بما في ذلك حقول التوقيع).


### FillForm {#FillForm}
```
public static final int FillForm
```


املأ حقول النماذج التفاعلية الموجودة.

معالجات الأمان للإصدار 3 أو أعلى: ملء حقول النماذج التفاعلية الموجودة
(بما في ذلك حقول التوقيع)، حتى إذا كان `#ModifyTextAnnotations.ModifyTextAnnotations` غير مفعَّل.


### ExtractContentWithDisabilities {#ExtractContentWithDisabilities}
```
public static final int ExtractContentWithDisabilities
```


استخرج النص والرسومات.

معالجات الأمان للإصدار 3 أو أعلى: استخراج النص والرسومات
(دعمًا لإمكانية الوصول للمستخدمين ذوي الإعاقة أو لأغراض أخرى).


### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```


جمّع المحتوى.

معالجات الأمان للإصدار 3 أو أعلى: تجميع المحتوى (إدراج، تدوير، أو حذف الصفحات
وإنشاء إشارات مرجعية أو صور مصغرة)، حتى إذا كان `#ModifyContent.ModifyContent` غير مفعَّل.


### PrintingQuality {#PrintingQuality}
```
public static final int PrintingQuality
```


اطبع المحتوى إلى تمثيل يمكن من خلاله إنشاء نسخة رقمية دقيقة من مستند PDF.

معالجات الأمان للإصدار 3 أو أعلى: طباعة المحتوى إلى تمثيل يمكن من خلاله الحصول على نسخة دقيقة
نسخة رقمية من مستند PDF يمكن إنشاؤها. عندما تكون هذه الخاصية غير مفعَّلة (و `#PrintDocument.PrintDocument`
مُعيَّنة)، يكون الطباعة محدودة إلى تمثيل منخفض المستوى للمظهر، وربما بجودة منخفضة.


