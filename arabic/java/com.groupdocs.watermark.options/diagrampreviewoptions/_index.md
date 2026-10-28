---
title: "DiagramPreviewOptions"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يوفر خيارات لتعيين المتطلبات ومندوبين التدفق لتوليد معاينة مستند مخطط."
type: docs
weight: 12
url: /ar/java/com.groupdocs.watermark.options/diagrampreviewoptions/
---
**Inheritance:**
java.lang.Object، [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class DiagramPreviewOptions extends PreviewOptions
```

يوفر خيارات لتعيين المتطلبات ومندوبين التدفق لتوليد معاينة مستند مخطط.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [DiagramPreviewOptions(ICreatePageStream createPageStream)](#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | ينشئ مثيلاً جديدًا للفئة `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` مما يتسبب في إغلاق تدفق الإخراج. |
|
|  | [DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | يُنشئ مثيلاً جديدًا من الفئة `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` مما يجعل تدفق الإخراج يُعاد إلى العميل للاستخدام لاحقًا. |
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
|  | [getHighQualityRendering()](#getHighQualityRendering--) | يحصل على العلامة الخاصة بالتصيير عالي الجودة. |
|
|  | [setHighQualityRendering(boolean value)](#setHighQualityRendering-boolean-) | يضبط العلامة الخاصة بالتصيير عالي الجودة. |
|
### DiagramPreviewOptions(ICreatePageStream createPageStream) {#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public DiagramPreviewOptions(ICreatePageStream createPageStream)
```


ينشئ مثيلاً جديدًا للفئة `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` مما يتسبب في إغلاق تدفق الإخراج.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | ينشئ تدفقًا لمعاينة صفحة محددة. |
|

### DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


يُنشئ مثيلاً جديدًا من الفئة `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` مما يجعل تدفق الإخراج يُعاد إلى العميل للاستخدام لاحقًا.


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

القيمة الافتراضية هي 300.

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

القيمة الافتراضية هي 300.

<br />

|

### getHighQualityRendering() {#getHighQualityRendering--}
```
public final boolean getHighQualityRendering()
```


يحصل على العلامة الخاصة بالتصيير عالي الجودة.


**Returns:**
منطقي - العلامة الخاصة بالتصيير عالي الجودة.

<br />

*** ** * ** ***

التصيير عالي الجودة يستخدم موارد أكثر. القيمة الافتراضية هي false.

<br />


### setHighQualityRendering(boolean value) {#setHighQualityRendering-boolean-}
```
public final void setHighQualityRendering(boolean value)
```


يضبط العلامة الخاصة بالتصيير عالي الجودة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | boolean | العلامة الخاصة بالتصيير عالي الجودة. |

<br />

*** ** * ** ***

التصيير عالي الجودة يستخدم موارد أكثر. القيمة الافتراضية هي false.

<br />

|

