---
title: "EmailPreviewOptions"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يوفر خيارات لتعيين المتطلبات ومندوبين التدفق لتوليد معاينة مستند بريد إلكتروني."
type: docs
weight: 17
url: /ar/java/com.groupdocs.watermark.options/emailpreviewoptions/
---
**Inheritance:**
java.lang.Object، [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class EmailPreviewOptions extends PreviewOptions
```

يوفر خيارات لتعيين المتطلبات ومندوبين التدفق لتوليد معاينة مستند بريد إلكتروني.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [EmailPreviewOptions(ICreatePageStream createPageStream)](#EmailPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | ينشئ مثيلاً جديداً من الفئة `[EmailPreviewOptions](../../com.groupdocs.watermark.options/emailpreviewoptions)` مما يؤدي إلى إغلاق تدفق الإخراج. |
|
|  | [EmailPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#EmailPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | ينشئ مثيلاً جديداً من الفئة `[EmailPreviewOptions](../../com.groupdocs.watermark.options/emailpreviewoptions)` مما يؤدي إلى إرجاع تدفق الإخراج إلى العميل للاستخدام الإضافي. |
|
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [DefaultResolution](#DefaultResolution) | الدقة الافتراضية بالنقاط في البوصة. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getResolution()](#getResolution--) | يحصل على الدقة للصور المولدة، بالنقاط في البوصة. |
|
|  | [setResolution(float value)](#setResolution-float-) | يضبط الدقة للصور المولدة، بالنقاط في البوصة. |
|
### EmailPreviewOptions(ICreatePageStream createPageStream) {#EmailPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public EmailPreviewOptions(ICreatePageStream createPageStream)
```


ينشئ مثيلاً جديداً من الفئة `[EmailPreviewOptions](../../com.groupdocs.watermark.options/emailpreviewoptions)` مما يؤدي إلى إغلاق تدفق الإخراج.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | ينشئ تدفقًا لمعاينة صفحة محددة. |
|

### EmailPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#EmailPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public EmailPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


ينشئ مثيلاً جديداً من الفئة `[EmailPreviewOptions](../../com.groupdocs.watermark.options/emailpreviewoptions)` مما يؤدي إلى إرجاع تدفق الإخراج إلى العميل للاستخدام الإضافي.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | ينشئ تدفقًا لمعاينة صفحة محددة. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | يُخطر بأن إنشاء معاينة الصفحة انتهى ويحصل على تدفق الإخراج. |
|

### DefaultResolution {#DefaultResolution}
```
public static final float DefaultResolution
```


الدقة الافتراضية بالنقاط في البوصة.


### getResolution() {#getResolution--}
```
public final float getResolution()
```


يحصل على الدقة للصور المولدة، بالنقاط في البوصة.


**Returns:**
float - الدقة للصور المُولَّدة، بوحدة النقاط لكل بوصة.

<br />

*** ** * ** ***

القيمة الافتراضية هي 96.

<br />


### setResolution(float value) {#setResolution-float-}
```
public final void setResolution(float value)
```


يضبط الدقة للصور المولدة، بالنقاط في البوصة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | float | الدقة للصور المولدة، بالنقاط في البوصة. |

<br />

*** ** * ** ***

القيمة الافتراضية هي 96.

<br />

|

