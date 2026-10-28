---
title: "SpreadsheetHeaderFooterSection"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt einen Kopf-/Fußzeilenabschnitt in einem Excel-Dokument dar."
type: docs
weight: 111
url: /de/java/com.groupdocs.watermark.contents/spreadsheetheaderfootersection/
---
**Inheritance:**
java.lang.Object
```
public class SpreadsheetHeaderFooterSection
```

Stellt einen Kopf-/Fußzeilenabschnitt in einem Excel-Dokument dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getSectionType()](#getSectionType--) | Gibt den Typ dieses `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` zurück. |
|
|  | [getHeaderFooter()](#getHeaderFooter--) | Gibt die übergeordnete Kopf-/Fußzeile dieses `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` zurück. |
|
|  | [getScript()](#getScript--) | Gibt die Skriptformatierung dieses `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` zurück. |
|
|  | [setScript(String value)](#setScript-java.lang.String-) | Setzt die Skriptformatierung dieses `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`. |
|
|  | [getImage()](#getImage--) | Gibt das Bild dieses `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` zurück. |
|
|  | [setImage(SpreadsheetWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | Setzt das Bild dieses `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`. |
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


Gibt den Typ dieses `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` zurück.


**Returns:**
int - Der Typ dieses `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`.

### getHeaderFooter() {#getHeaderFooter--}
```
public final SpreadsheetHeaderFooter getHeaderFooter()
```


Gibt die übergeordnete Kopf-/Fußzeile dieses `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` zurück.


**Returns:**
[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter) - The parent header/footer of this `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`.

### getScript() {#getScript--}
```
public final String getScript()
```


Gibt die Skriptformatierung dieses `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` zurück.


**Returns:**
java.lang.String - Der Skriptinhalt dieses `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`.

### setScript(String value) {#setScript-java.lang.String-}
```
public final void setScript(String value)
```


Setzt die Skriptformatierung dieses `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | java.lang.String | Der Skriptinhalt dieses `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`. |
|

### getImage() {#getImage--}
```
public final SpreadsheetWatermarkableImage getImage()
```


Gibt das Bild dieses `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` zurück.


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The image of this `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` or `null` if the section has no image.

### setImage(SpreadsheetWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public final void setImage(SpreadsheetWatermarkableImage value)
```


Setzt das Bild dieses `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | Das Bild dieses `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` oder `null`, wenn das Bild entfernt werden soll. |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] |  |

### resetImageReference() {#resetImageReference--}
```
public final void resetImageReference()
```


<br />



