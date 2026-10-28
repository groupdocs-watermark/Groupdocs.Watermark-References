---
title: "SpreadsheetPreviewOptions"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يوفر خيارات لتعيين المتطلبات ومندوبين التدفق لإنشاء معاينة مستند جدول البيانات."
type: docs
weight: 52
url: /ar/java/com.groupdocs.watermark.options/spreadsheetpreviewoptions/
---
**Inheritance:**
java.lang.Object، [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class SpreadsheetPreviewOptions extends PreviewOptions
```

يوفر خيارات لتعيين المتطلبات ومندوبين التدفق لإنشاء معاينة مستند جدول البيانات.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [SpreadsheetPreviewOptions(ICreatePageStream createPageStream)](#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | ينشئ مثيلاً جديدًا للفئة `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` مما يؤدي إلى إغلاق تدفق الإخراج. |
|
|  | [SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | ينشئ مثيلاً جديدًا للفئة `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` مما يؤدي إلى إرجاع تدفق الإخراج إلى العميل للاستخدام لاحقًا. |
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
|  | [getOnlyDataArea()](#getOnlyDataArea--) | يحصل على العلامة لتصوير منطقة البيانات فقط دون رؤوس، تذييلات، وهوامش. |
|
|  | [setOnlyDataArea(boolean value)](#setOnlyDataArea-boolean-) | يضبط العلامة لتصوير منطقة البيانات فقط دون رؤوس، تذييلات، وهوامش. |
|
### SpreadsheetPreviewOptions(ICreatePageStream createPageStream) {#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public SpreadsheetPreviewOptions(ICreatePageStream createPageStream)
```


ينشئ مثيلاً جديدًا للفئة `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` مما يؤدي إلى إغلاق تدفق الإخراج.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | ينشئ تدفقًا لمعاينة صفحة محددة. |
|

### SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


ينشئ مثيلاً جديدًا للفئة `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` مما يؤدي إلى إرجاع تدفق الإخراج إلى العميل للاستخدام لاحقًا.


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

القيمة الافتراضية هي 96.

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

القيمة الافتراضية هي 96.

<br />

|

### getOnlyDataArea() {#getOnlyDataArea--}
```
public final boolean getOnlyDataArea()
```


يحصل على العلامة لتصوير منطقة البيانات فقط دون رؤوس، تذييلات، وهوامش.


**Returns:**
boolean - العلامة لتصوير منطقة البيانات فقط دون رؤوس، تذييلات، وهوامش.

<br />

*** ** * ** ***

هذه العلامة تؤدي إلى تصوير كامل ورقة العمل على صفحة واحدة. القيمة الافتراضية هي false.

<br />


### setOnlyDataArea(boolean value) {#setOnlyDataArea-boolean-}
```
public final void setOnlyDataArea(boolean value)
```


يضبط العلامة لتصوير منطقة البيانات فقط دون رؤوس، تذييلات، وهوامش.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | boolean | العلامة لتصوير منطقة البيانات فقط دون رؤوس، تذييلات، وهوامش. |

<br />

*** ** * ** ***

هذه العلامة تؤدي إلى تصوير كامل ورقة العمل على صفحة واحدة. القيمة الافتراضية هي false.

<br />

|

