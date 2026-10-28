---
title: "PresentationPreviewOptions"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يوفر خيارات لتعيين المتطلبات ومندوبين التدفق لتوليد معاينة مستند عرض تقديمي."
type: docs
weight: 12
url: /ar/java/com.groupdocs.watermark/presentationpreviewoptions/
---
**Inheritance:**
java.lang.Object، [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class PresentationPreviewOptions extends PreviewOptions
```

يوفر خيارات لتعيين المتطلبات ومندوبين التدفق لتوليد معاينة مستند عرض تقديمي.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [PresentationPreviewOptions(ICreatePageStream createPageStream)](#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | ينشئ مثيلًا جديدًا للفئة `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` مما يؤدي إلى إغلاق تدفق الإخراج. |
|
|  | [PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | ينشئ مثيلًا جديدًا للفئة `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` مما يؤدي إلى إرجاع تدفق الإخراج إلى العميل للاستخدام لاحقًا. |
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
|  | [setResolution(long value)](#setResolution-long-) | يضبط الدقة للصور المولدة، بالنقاط في البوصة. |
|
### PresentationPreviewOptions(ICreatePageStream createPageStream) {#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PresentationPreviewOptions(ICreatePageStream createPageStream)
```


ينشئ مثيلًا جديدًا للفئة `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` مما يؤدي إلى إغلاق تدفق الإخراج.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | ينشئ تدفقًا لمعاينة صفحة محددة. |
|

### PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


ينشئ مثيلًا جديدًا للفئة `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` مما يؤدي إلى إرجاع تدفق الإخراج إلى العميل للاستخدام لاحقًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | ينشئ تدفقًا لمعاينة صفحة محددة. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | يُخطر بأن إنشاء معاينة الصفحة انتهى ويحصل على تدفق الإخراج. |
|

### DefaultResolution {#DefaultResolution}
```
public static final long DefaultResolution
```


الدقة الافتراضية بالنقاط في البوصة.


### getResolution() {#getResolution--}
```
public final long getResolution()
```


يحصل على الدقة للصور المولدة، بالنقاط في البوصة.


**Returns:**
long - الدقة للصور المولدة، بالنقاط في البوصة.

### setResolution(long value) {#setResolution-long-}
```
public final void setResolution(long value)
```


يضبط الدقة للصور المولدة، بالنقاط في البوصة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | long | الدقة للصور المولدة، بالنقاط في البوصة. |
|

