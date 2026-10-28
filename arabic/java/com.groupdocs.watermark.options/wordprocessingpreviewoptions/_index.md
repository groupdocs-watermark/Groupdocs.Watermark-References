---
title: "WordProcessingPreviewOptions"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يوفر خيارات لتعيين المتطلبات ومندوبين التدفق لإنشاء معاينة مستند معالجة النصوص."
type: docs
weight: 69
url: /ar/java/com.groupdocs.watermark.options/wordprocessingpreviewoptions/
---
**Inheritance:**
java.lang.Object، [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class WordProcessingPreviewOptions extends PreviewOptions
```

يوفر خيارات لتعيين المتطلبات ومندوبين التدفق لإنشاء معاينة مستند معالجة النصوص.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [WordProcessingPreviewOptions(ICreatePageStream createPageStream)](#WordProcessingPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | ينشئ مثيلاً جديداً من الفئة `[WordProcessingPreviewOptions](../../com.groupdocs.watermark.options/wordprocessingpreviewoptions)` مما يؤدي إلى إغلاق تدفق الإخراج. |
|
|  | [WordProcessingPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#WordProcessingPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | ينشئ مثيلاً جديداً من الفئة `[WordProcessingPreviewOptions](../../com.groupdocs.watermark.options/wordprocessingpreviewoptions)` مما يؤدي إلى إرجاع تدفق الإخراج إلى العميل للاستخدام الإضافي. |
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
### WordProcessingPreviewOptions(ICreatePageStream createPageStream) {#WordProcessingPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public WordProcessingPreviewOptions(ICreatePageStream createPageStream)
```


ينشئ مثيلاً جديداً من الفئة `[WordProcessingPreviewOptions](../../com.groupdocs.watermark.options/wordprocessingpreviewoptions)` مما يؤدي إلى إغلاق تدفق الإخراج.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | ينشئ تدفقًا لمعاينة صفحة محددة. |
|

### WordProcessingPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#WordProcessingPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public WordProcessingPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


ينشئ مثيلاً جديداً من الفئة `[WordProcessingPreviewOptions](../../com.groupdocs.watermark.options/wordprocessingpreviewoptions)` مما يؤدي إلى إرجاع تدفق الإخراج إلى العميل للاستخدام الإضافي.


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

