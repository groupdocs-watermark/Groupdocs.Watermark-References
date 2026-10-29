---
title: "SpreadsheetHeaderFooterSection"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar ett sidhuvud/sidfotsavsnitt i ett Excel-dokument."
type: docs
weight: 111
url: /sv/java/com.groupdocs.watermark.contents/spreadsheetheaderfootersection/
---
**Inheritance:**
java.lang.Object
```
public class SpreadsheetHeaderFooterSection
```

Representerar ett sidhuvud/sidfotsavsnitt i ett Excel-dokument.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getSectionType()](#getSectionType--) | Hämtar typen av detta `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`. |
|
|  | [getHeaderFooter()](#getHeaderFooter--) | Hämtar föräldra sidhuvud/sidfoten för detta `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`. |
|
|  | [getScript()](#getScript--) | Hämtar skriptformateringen för detta `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`. |
|
|  | [setScript(String value)](#setScript-java.lang.String-) | Ställer in skriptformateringen för detta `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`. |
|
|  | [getImage()](#getImage--) | Hämtar bilden för detta `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`. |
|
|  | [setImage(SpreadsheetWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | Ställer in bilden för detta `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`. |
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


Hämtar typen av detta `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`.


**Returns:**
int - Typen av detta `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`.

### getHeaderFooter() {#getHeaderFooter--}
```
public final SpreadsheetHeaderFooter getHeaderFooter()
```


Hämtar föräldra sidhuvud/sidfoten för detta `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`.


**Returns:**
[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter) - The parent header/footer of this `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`.

### getScript() {#getScript--}
```
public final String getScript()
```


Hämtar skriptformateringen för detta `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`.


**Returns:**
java.lang.String - Skriptinnehållet för detta `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`.

### setScript(String value) {#setScript-java.lang.String-}
```
public final void setScript(String value)
```


Ställer in skriptformateringen för detta `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.lang.String | Skriptinnehållet för detta `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`. |
|

### getImage() {#getImage--}
```
public final SpreadsheetWatermarkableImage getImage()
```


Hämtar bilden för detta `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`.


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The image of this `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` or `null` if the section has no image.

### setImage(SpreadsheetWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public final void setImage(SpreadsheetWatermarkableImage value)
```


Ställer in bilden för detta `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | Bilden för detta `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` eller `null` om bilden ska tas bort. |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### resetImageReference() {#resetImageReference--}
```
public final void resetImageReference()
```


<br />



