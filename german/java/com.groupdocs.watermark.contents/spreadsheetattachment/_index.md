---
title: "SpreadsheetAttachment"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt eine an ein Excel-Dokument angehängte Datei dar."
type: docs
weight: 101
url: /de/java/com.groupdocs.watermark.contents/spreadsheetattachment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.ITwoDObject](../../com.groupdocs.watermark.search/itwodobject)
```
public class SpreadsheetAttachment extends Attachment implements ITwoDObject
```

Stellt eine an ein Excel-Dokument angehängte Datei dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getContent()](#getContent--) | Liest den Inhalt der angehängten Datei. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | Setzt den Inhalt der angehängten Datei. |
|
|  | [getPreviewImageContent()](#getPreviewImageContent--) | Liefert das Vorschaubild der angehängten Datei als Byte-Array. |
|
|  | [setPreviewImageContent(byte[] value)](#setPreviewImageContent-byte---) | Setzt das Vorschaubild der angehängten Datei als Byte-Array. |
|
|  | [isLink()](#isLink--) | Liefert einen Wert, der angibt, ob der Inhalt nur einen Link zur Datei enthält. |
|
|  | [getSourceFullName()](#getSourceFullName--) | Liefert den vollständigen Namen der angehängten Datei. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Liefert den beschreibenden (alternativen) Text, der mit der angehängten Datei verknüpft ist. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Setzt den beschreibenden (alternativen) Text, der mit der angehängten Datei verknüpft ist. |
|
|  | [getAsposeOleObject()](#getAsposeOleObject--) | <br /> |

|
|  | [getX()](#getX--) | Liefert den horizontalen Versatz des Anhangrahmens vom linken Rand des Arbeitsblatts in Punkten. |
|
|  | [setX(double value)](#setX-double-) | Setzt den horizontalen Versatz des Anhangrahmens vom linken Rand des Arbeitsblatts in Punkten. |
|
|  | [getY()](#getY--) | Liefert den vertikalen Versatz des Anhangrahmens vom oberen Rand des Arbeitsblatts in Punkten. |
|
|  | [setY(double value)](#setY-double-) | Setzt den vertikalen Versatz des Anhangrahmens vom oberen Rand des Arbeitsblatts in Punkten. |
|
|  | [getWidth()](#getWidth--) | Liefert die Breite des Anhangrahmens in Punkten. |
|
|  | [setWidth(double value)](#setWidth-double-) | Setzt die Breite des Anhangrahmens in Punkten. |
|
|  | [getHeight()](#getHeight--) | Liefert die Höhe des Anhangrahmens in Punkten. |
|
|  | [setHeight(double value)](#setHeight-double-) | Setzt die Höhe des Anhangrahmens in Punkten. |
|
|  | [checkImageType()](#checkImageType--) | <br /> |

|
### getContent() {#getContent--}
```
public byte[] getContent()
```


Liest den Inhalt der angehängten Datei.


**Returns:**
byte[] - Der Inhalt der angehängten Datei.

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


Setzt den Inhalt der angehängten Datei.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | byte[] | Der Inhalt der angehängten Datei. |
|

### getPreviewImageContent() {#getPreviewImageContent--}
```
public final byte[] getPreviewImageContent()
```


Liefert das Vorschaubild der angehängten Datei als Byte-Array.


**Returns:**
byte[] - Das Vorschaubild der angehängten Datei als Byte-Array.

### setPreviewImageContent(byte[] value) {#setPreviewImageContent-byte---}
```
public final void setPreviewImageContent(byte[] value)
```


Setzt das Vorschaubild der angehängten Datei als Byte-Array.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | byte[] | Das Vorschaubild der angehängten Datei als Byte-Array. |
|

### isLink() {#isLink--}
```
public final boolean isLink()
```


Liefert einen Wert, der angibt, ob der Inhalt nur einen Link zur Datei enthält.


**Returns:**
boolean - Wahr, wenn die angehängte Datei über einen Link referenziert wird (der Inhalt enthält nicht den Inhalt der angehängten Datei); andernfalls falsch.

### getSourceFullName() {#getSourceFullName--}
```
public final String getSourceFullName()
```


Liefert den vollständigen Namen der angehängten Datei.


**Returns:**
java.lang.String - Der vollständige Name der angehängten Datei.

<br />

*** ** * ** ***

Die Erweiterung wird verwendet, um die geeignete Anwendung zum Öffnen der Datei zu bestimmen.

<br />


### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Liefert den beschreibenden (alternativen) Text, der mit der angehängten Datei verknüpft ist.


**Returns:**
java.lang.String - Der beschreibende (alternative) Text, der mit der angehängten Datei verknüpft ist.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Setzt den beschreibenden (alternativen) Text, der mit der angehängten Datei verknüpft ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.String | Der beschreibende (alternative) Text, der mit der angehängten Datei verknüpft ist. |
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


Liefert den horizontalen Versatz des Anhangrahmens vom linken Rand des Arbeitsblatts in Punkten.


**Returns:**
double - Die x‑Koordinate des Anhangrahmens.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Setzt den horizontalen Versatz des Anhangrahmens vom linken Rand des Arbeitsblatts in Punkten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | double | Die x‑Koordinate des Anhangrahmens. |
|

### getY() {#getY--}
```
public final double getY()
```


Liefert den vertikalen Versatz des Anhangrahmens vom oberen Rand des Arbeitsblatts in Punkten.


**Returns:**
double - Die y‑Koordinate des Anhangrahmens.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Setzt den vertikalen Versatz des Anhangrahmens vom oberen Rand des Arbeitsblatts in Punkten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | double | Die y‑Koordinate des Anhangrahmens. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Liefert die Breite des Anhangrahmens in Punkten.


**Returns:**
double - Die Breite des Anhangrahmens in Punkten.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Setzt die Breite des Anhangrahmens in Punkten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | double | Die Breite des Anhangrahmens in Punkten. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Liefert die Höhe des Anhangrahmens in Punkten.


**Returns:**
double - Die Höhe des Anhangrahmens in Punkten.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Setzt die Höhe des Anhangrahmens in Punkten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | double | Die Höhe des Anhangrahmens in Punkten. |
|

### checkImageType() {#checkImageType--}
```
public final void checkImageType()
```


<br />



