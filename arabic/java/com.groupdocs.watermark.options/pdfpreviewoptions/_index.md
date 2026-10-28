---
title: "PdfPreviewOptions"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يوفر خيارات لتعيين المتطلبات ومندوبات الدفق لإنشاء معاينة لمستند PDF."
type: docs
weight: 31
url: /ar/java/com.groupdocs.watermark.options/pdfpreviewoptions/
---
**Inheritance:**
java.lang.Object، [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class PdfPreviewOptions extends PreviewOptions
```

يوفر خيارات لتعيين المتطلبات ومندوبات الدفق لإنشاء معاينة لمستند PDF.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [PdfPreviewOptions(ICreatePageStream createPageStream)](#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | ينشئ مثيلاً جديدًا للفئة `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` مما يؤدي إلى إغلاق تدفق الإخراج. |
|
|  | [PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | ينشئ مثيلاً جديدًا للفئة `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` مما يجعل تدفق الإخراج يُعاد إلى العميل للاستخدام لاحقًا. |
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
|  | [setResolution(int value)](#setResolution-int-) | يضبط الدقة للصور المولدة، بالنقاط في البوصة. |
|
### PdfPreviewOptions(ICreatePageStream createPageStream) {#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PdfPreviewOptions(ICreatePageStream createPageStream)
```


ينشئ مثيلاً جديدًا للفئة `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` مما يؤدي إلى إغلاق تدفق الإخراج.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | ينشئ تدفقًا لمعاينة صفحة محددة. |
|

### PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


ينشئ مثيلاً جديدًا للفئة `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` مما يجعل تدفق الإخراج يُعاد إلى العميل للاستخدام لاحقًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | ينشئ تدفقًا لمعاينة صفحة محددة. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | يُخطر بأن إنشاء معاينة الصفحة انتهى ويحصل على تدفق الإخراج. |
|

### DefaultResolution {#DefaultResolution}
```
public static final int DefaultResolution
```


الدقة الافتراضية بالنقاط في البوصة.


### getResolution() {#getResolution--}
```
public final int getResolution()
```


يحصل على الدقة للصور المولدة، بالنقاط في البوصة.


**Returns:**
int - الدقة للصور المولدة، بوحدة النقاط في البوصة.

<br />

*** ** * ** ***

القيمة الافتراضية هي 150.

<br />


### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


يضبط الدقة للصور المولدة، بالنقاط في البوصة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | int | الدقة للصور المولدة، بالنقاط في البوصة. |

<br />

*** ** * ** ***

القيمة الافتراضية هي 150.

<br />

|

