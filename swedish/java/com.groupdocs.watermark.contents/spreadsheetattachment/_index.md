---
title: "SpreadsheetAttachment"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar en fil som är bifogad till ett Excel-dokument."
type: docs
weight: 101
url: /sv/java/com.groupdocs.watermark.contents/spreadsheetattachment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.ITwoDObject](../../com.groupdocs.watermark.search/itwodobject)
```
public class SpreadsheetAttachment extends Attachment implements ITwoDObject
```

Representerar en fil som är bifogad till ett Excel-dokument.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getContent()](#getContent--) | Hämtar det bifogade filinnehållet. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | Ställer in det bifogade filinnehållet. |
|
|  | [getPreviewImageContent()](#getPreviewImageContent--) | Hämtar förhandsgranskningsbilden för den bifogade filen som en byte-array. |
|
|  | [setPreviewImageContent(byte[] value)](#setPreviewImageContent-byte---) | Ställer in förhandsgranskningsbilden för den bifogade filen som en byte-array. |
|
|  | [isLink()](#isLink--) | Hämtar ett värde som indikerar om innehållet endast innehåller en länk till filen. |
|
|  | [getSourceFullName()](#getSourceFullName--) | Hämtar det fullständiga namnet på den bifogade filen. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Hämtar den beskrivande (alternativa) texten som är associerad med den bifogade filen. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Ställer in den beskrivande (alternativa) texten som är associerad med den bifogade filen. |
|
|  | [getAsposeOleObject()](#getAsposeOleObject--) | <br /> |

|
|  | [getX()](#getX--) | Hämtar den horisontella förskjutningen för bilagans ram från kalkylbladets vänstra kant i punkter. |
|
|  | [setX(double value)](#setX-double-) | Ställer in den horisontella förskjutningen för bilagans ram från kalkylbladets vänstra kant i punkter. |
|
|  | [getY()](#getY--) | Hämtar den vertikala förskjutningen för bilagans ram från kalkylbladets övre kant i punkter. |
|
|  | [setY(double value)](#setY-double-) | Ställer in den vertikala förskjutningen för bilagans ram från kalkylbladets övre kant i punkter. |
|
|  | [getWidth()](#getWidth--) | Hämtar bredden på bilagans ram i punkter. |
|
|  | [setWidth(double value)](#setWidth-double-) | Ställer in bredden på bilagans ram i punkter. |
|
|  | [getHeight()](#getHeight--) | Hämtar höjden på bilagans ram i punkter. |
|
|  | [setHeight(double value)](#setHeight-double-) | Ställer in höjden på bilagans ram i punkter. |
|
|  | [checkImageType()](#checkImageType--) | <br /> |

|
### getContent() {#getContent--}
```
public byte[] getContent()
```


Hämtar det bifogade filinnehållet.


**Returns:**
byte[] - Det bifogade filinnehållet.

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


Ställer in det bifogade filinnehållet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | byte[] | Det bifogade filinnehållet. |
|

### getPreviewImageContent() {#getPreviewImageContent--}
```
public final byte[] getPreviewImageContent()
```


Hämtar förhandsgranskningsbilden för den bifogade filen som en byte-array.


**Returns:**
byte[] - Förhandsgranskningsbilden för den bifogade filen som en byte-array.

### setPreviewImageContent(byte[] value) {#setPreviewImageContent-byte---}
```
public final void setPreviewImageContent(byte[] value)
```


Ställer in förhandsgranskningsbilden för den bifogade filen som en byte-array.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | byte[] | Den bifogade filens förhandsgranskningsbild som en bytearray. |
|

### isLink() {#isLink--}
```
public final boolean isLink()
```


Hämtar ett värde som indikerar om innehållet endast innehåller en länk till filen.


**Returns:**
boolean - Sant om den bifogade filen refereras av en länk (innehållet innehåller inte den bifogade filens innehåll); annars falskt.

### getSourceFullName() {#getSourceFullName--}
```
public final String getSourceFullName()
```


Hämtar det fullständiga namnet på den bifogade filen.


**Returns:**
java.lang.String - Det fullständiga namnet på den bifogade filen.

<br />

*** ** * ** ***

Filändelsen används för att bestämma lämplig applikation för att öppna filen.

<br />


### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Hämtar den beskrivande (alternativa) texten som är associerad med den bifogade filen.


**Returns:**
java.lang.String - Den beskrivande (alternativa) texten som är associerad med den bifogade filen.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Ställer in den beskrivande (alternativa) texten som är associerad med den bifogade filen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.lang.String | Den beskrivande (alternativa) texten som är associerad med den bifogade filen. |
|

### getAsposeOleObject() {#getAsposeOleObject--}
```
public final OleObject getAsposeOleObject()
```


<br />



**Returns:**
com.aspose.cells.OleObject
### getX() {#getX--}
```
public final double getX()
```


Hämtar den horisontella förskjutningen för bilagans ram från kalkylbladets vänstra kant i punkter.


**Returns:**
double - X-koordinaten för bilagans ram.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Ställer in den horisontella förskjutningen för bilagans ram från kalkylbladets vänstra kant i punkter.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | double | X-koordinaten för bilagans ram. |
|

### getY() {#getY--}
```
public final double getY()
```


Hämtar den vertikala förskjutningen för bilagans ram från kalkylbladets övre kant i punkter.


**Returns:**
double - Y-koordinaten för bilagans ram.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Ställer in den vertikala förskjutningen för bilagans ram från kalkylbladets övre kant i punkter.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | double | Y-koordinaten för bilagans ram. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Hämtar bredden på bilagans ram i punkter.


**Returns:**
double - Bredden på bilagans ram i punkter.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Ställer in bredden på bilagans ram i punkter.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | double | Bredden på bilagans ram i punkter. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Hämtar höjden på bilagans ram i punkter.


**Returns:**
double - Höjden på bilagans ram i punkter.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Ställer in höjden på bilagans ram i punkter.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | double | Höjden på bilagans ram i punkter. |
|

### checkImageType() {#checkImageType--}
```
public final void checkImageType()
```


<br />



