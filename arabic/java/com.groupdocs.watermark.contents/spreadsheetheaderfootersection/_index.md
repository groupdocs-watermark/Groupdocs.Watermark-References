---
title: "SpreadsheetHeaderFooterSection"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل قسم الترويسة/التذييل في مستند Excel."
type: docs
weight: 111
url: /ar/java/com.groupdocs.watermark.contents/spreadsheetheaderfootersection/
---
**Inheritance:**
java.lang.Object
```
public class SpreadsheetHeaderFooterSection
```

يمثل قسم الترويسة/التذييل في مستند Excel.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getSectionType()](#getSectionType--) | يحصل على نوع هذا `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`. |
|
|  | [getHeaderFooter()](#getHeaderFooter--) | يحصل على رأس/تذييل الأصل لهذا `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`. |
|
|  | [getScript()](#getScript--) | يحصل على تنسيق النص البرمجي لهذا `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`. |
|
|  | [setScript(String value)](#setScript-java.lang.String-) | يضبط تنسيق النص البرمجي لهذا `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`. |
|
|  | [getImage()](#getImage--) | يحصل على صورة هذا `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`. |
|
|  | [setImage(SpreadsheetWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | يضبط صورة هذا `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`. |
|
|  | [getImageData()](#getImageData--) | <br /> |

|
|  | [setImageData(byte[] value)](#setImageData-byte---) | <br /> |

|
|  | [resetImageReference()](#resetImageReference--) | <br /> |

|
### getSectionType() {#getSectionType--}
```
public final int getSectionType()
```


يحصل على نوع هذا `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`.


**Returns:**
int - نوع هذا `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`.

### getHeaderFooter() {#getHeaderFooter--}
```
public final SpreadsheetHeaderFooter getHeaderFooter()
```


يحصل على رأس/تذييل الأصل لهذا `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`.


**Returns:**
[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter) - The parent header/footer of this `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`.

### getScript() {#getScript--}
```
public final String getScript()
```


يحصل على تنسيق النص البرمجي لهذا `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`.


**Returns:**
java.lang.String - محتوى النص البرمجي لهذا `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`.

### setScript(String value) {#setScript-java.lang.String-}
```
public final void setScript(String value)
```


يضبط تنسيق النص البرمجي لهذا `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | java.lang.String | محتوى النص البرمجي لهذا `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`. |
|

### getImage() {#getImage--}
```
public final SpreadsheetWatermarkableImage getImage()
```


يحصل على صورة هذا `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`.


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The image of this `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` or `null` if the section has no image.

### setImage(SpreadsheetWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public final void setImage(SpreadsheetWatermarkableImage value)
```


يضبط صورة هذا `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | صورة هذا `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` أو `null` إذا كان يجب إزالة الصورة. |
|

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


<br />



**Returns:**
byte[]
### setImageData(byte[] value) {#setImageData-byte---}
```
public final void setImageData(byte[] value)
```


<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte[] |  |

### resetImageReference() {#resetImageReference--}
```
public final void resetImageReference()
```


<br />



