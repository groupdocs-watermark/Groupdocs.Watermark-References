---
title: "SpreadsheetAttachment"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt een bestand dat aan een Excel‑document is gekoppeld voor."
type: docs
weight: 101
url: /nl/java/com.groupdocs.watermark.contents/spreadsheetattachment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.ITwoDObject](../../com.groupdocs.watermark.search/itwodobject)
```
public class SpreadsheetAttachment extends Attachment implements ITwoDObject
```

Stelt een bestand dat aan een Excel‑document is gekoppeld voor.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getContent()](#getContent--) | Haalt de inhoud van het bijgevoegde bestand op. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | Stelt de inhoud van het bijgevoegde bestand in. |
|
|  | [getPreviewImageContent()](#getPreviewImageContent--) | Haalt de voorbeeldafbeelding van het bijgevoegde bestand op als een byte-array. |
|
|  | [setPreviewImageContent(byte[] value)](#setPreviewImageContent-byte---) | Stelt de voorbeeldafbeelding van het bijgevoegde bestand in als een byte-array. |
|
|  | [isLink()](#isLink--) | Haalt een waarde op die aangeeft of de inhoud alleen een koppeling naar het bestand bevat. |
|
|  | [getSourceFullName()](#getSourceFullName--) | Haalt de volledige naam van het bijgevoegde bestand op. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Haalt de beschrijvende (alternatieve) tekst op die aan het bijgevoegde bestand is gekoppeld. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Stelt de beschrijvende (alternatieve) tekst in die aan het bijgevoegde bestand is gekoppeld. |
|
|  | [getAsposeOleObject()](#getAsposeOleObject--) | <br /> |

|
|  | [getX()](#getX--) | Haalt de horizontale offset van het bijlageframe ten opzichte van de linkerrand van het werkblad op in punten. |
|
|  | [setX(double value)](#setX-double-) | Stelt de horizontale offset van het bijlageframe ten opzichte van de linkerrand van het werkblad in punten. |
|
|  | [getY()](#getY--) | Haalt de verticale offset van het bijlageframe ten opzichte van de bovengrens van het werkblad op in punten. |
|
|  | [setY(double value)](#setY-double-) | Stelt de verticale offset van het bijlageframe ten opzichte van de bovengrens van het werkblad in punten. |
|
|  | [getWidth()](#getWidth--) | Haalt de breedte van het bijlageframe op in punten. |
|
|  | [setWidth(double value)](#setWidth-double-) | Stelt de breedte van het bijlageframe in punten. |
|
|  | [getHeight()](#getHeight--) | Haalt de hoogte van het bijlageframe op in punten. |
|
|  | [setHeight(double value)](#setHeight-double-) | Stelt de hoogte van het bijlageframe in punten. |
|
|  | [checkImageType()](#checkImageType--) | <br /> |

|
### getContent() {#getContent--}
```
public byte[] getContent()
```


Haalt de inhoud van het bijgevoegde bestand op.


**Returns:**
byte[] - De inhoud van het bijgevoegde bestand.

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


Stelt de inhoud van het bijgevoegde bestand in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | byte[] | De inhoud van het bijgevoegde bestand. |
|

### getPreviewImageContent() {#getPreviewImageContent--}
```
public final byte[] getPreviewImageContent()
```


Haalt de voorbeeldafbeelding van het bijgevoegde bestand op als een byte-array.


**Returns:**
byte[] - De voorbeeldafbeelding van het bijgevoegde bestand als een byte-array.

### setPreviewImageContent(byte[] value) {#setPreviewImageContent-byte---}
```
public final void setPreviewImageContent(byte[] value)
```


Stelt de voorbeeldafbeelding van het bijgevoegde bestand in als een byte-array.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | byte[] | De voorbeeldafbeelding van het bijgevoegde bestand als een byte-array. |
|

### isLink() {#isLink--}
```
public final boolean isLink()
```


Haalt een waarde op die aangeeft of de inhoud alleen een koppeling naar het bestand bevat.


**Returns:**
boolean - True als het bijgevoegde bestand wordt verwezen via een koppeling (de inhoud bevat geen bijgevoegde bestandsinhoud); anders false.

### getSourceFullName() {#getSourceFullName--}
```
public final String getSourceFullName()
```


Haalt de volledige naam van het bijgevoegde bestand op.


**Returns:**
java.lang.String - De volledige naam van het bijgevoegde bestand.

<br />

*** ** * ** ***

De extensie wordt gebruikt om de juiste toepassing te bepalen om het bestand te openen.

<br />


### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Haalt de beschrijvende (alternatieve) tekst op die aan het bijgevoegde bestand is gekoppeld.


**Returns:**
java.lang.String - De beschrijvende (alternatieve) tekst die aan het bijgevoegde bestand is gekoppeld.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Stelt de beschrijvende (alternatieve) tekst in die aan het bijgevoegde bestand is gekoppeld.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | De beschrijvende (alternatieve) tekst die aan het bijgevoegde bestand is gekoppeld. |
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


Haalt de horizontale offset van het bijlageframe ten opzichte van de linkerrand van het werkblad op in punten.


**Returns:**
double - De x-coördinaat van het bijlageframe.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Stelt de horizontale offset van het bijlageframe ten opzichte van de linkerrand van het werkblad in punten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | double | De x-coördinaat van het bijlageframe. |
|

### getY() {#getY--}
```
public final double getY()
```


Haalt de verticale offset van het bijlageframe ten opzichte van de bovengrens van het werkblad op in punten.


**Returns:**
double - De y-coördinaat van het bijlageframe.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Stelt de verticale offset van het bijlageframe ten opzichte van de bovengrens van het werkblad in punten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | double | De y-coördinaat van het bijlageframe. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Haalt de breedte van het bijlageframe op in punten.


**Returns:**
double - De breedte van het bijlageframe in punten.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Stelt de breedte van het bijlageframe in punten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | double | De breedte van het bijlageframe in punten. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Haalt de hoogte van het bijlageframe op in punten.


**Returns:**
double - De hoogte van het bijlageframe in punten.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Stelt de hoogte van het bijlageframe in punten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | double | De hoogte van het bijlageframe in punten. |
|

### checkImageType() {#checkImageType--}
```
public final void checkImageType()
```


<br />



