---
title: "SpreadsheetHeaderFooterSection"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Excel belgesindeki bir üstbilgi/altbilgi bölümünü temsil eder."
type: docs
weight: 111
url: /tr/java/com.groupdocs.watermark.contents/spreadsheetheaderfootersection/
---
**Inheritance:**
java.lang.Object
```
public class SpreadsheetHeaderFooterSection
```

Excel belgesindeki bir üstbilgi/altbilgi bölümünü temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getSectionType()](#getSectionType--) | Bu `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` tipini alır. |
|
|  | [getHeaderFooter()](#getHeaderFooter--) | Bu `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` üst başlık/altbilgi öğesini alır. |
|
|  | [getScript()](#getScript--) | Bu `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` betik biçimlendirmesini alır. |
|
|  | [setScript(String value)](#setScript-java.lang.String-) | Bu `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` betik biçimlendirmesini ayarlar. |
|
|  | [getImage()](#getImage--) | Bu `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` görüntüsünü alır. |
|
|  | [setImage(SpreadsheetWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | Bu `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` görüntüsünü ayarlar. |
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


Bu `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` tipini alır.


**Returns:**
int - Bu `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` tipinin.

### getHeaderFooter() {#getHeaderFooter--}
```
public final SpreadsheetHeaderFooter getHeaderFooter()
```


Bu `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` üst başlık/altbilgi öğesini alır.


**Returns:**
[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter) - The parent header/footer of this `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`.

### getScript() {#getScript--}
```
public final String getScript()
```


Bu `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` betik biçimlendirmesini alır.


**Returns:**
java.lang.String - Bu `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` betik içeriği.

### setScript(String value) {#setScript-java.lang.String-}
```
public final void setScript(String value)
```


Bu `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` betik biçimlendirmesini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | java.lang.String | Bu `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` betik içeriği. |
|

### getImage() {#getImage--}
```
public final SpreadsheetWatermarkableImage getImage()
```


Bu `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` görüntüsünü alır.


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The image of this `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` or `null` if the section has no image.

### setImage(SpreadsheetWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public final void setImage(SpreadsheetWatermarkableImage value)
```


Bu `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` görüntüsünü ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | Bu `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` görüntüsü veya görüntünün kaldırılması gerekiyorsa `null`. |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### resetImageReference() {#resetImageReference--}
```
public final void resetImageReference()
```


<br />



