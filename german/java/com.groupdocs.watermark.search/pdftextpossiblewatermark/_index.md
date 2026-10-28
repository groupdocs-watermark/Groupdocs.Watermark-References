---
title: "PdfTextPossibleWatermark"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt mögliche Wasserzeichen im Text eines PDF‑Dokuments dar."
type: docs
weight: 43
url: /de/java/com.groupdocs.watermark.search/pdftextpossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)
```
public class PdfTextPossibleWatermark extends PossibleWatermark
```

Stellt mögliche Wasserzeichen im Text eines PDF‑Dokuments dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfTextPossibleWatermark(PdfPage parent, TextFragment fragment)](#PdfTextPossibleWatermark-com.groupdocs.watermark.contents.PdfPage-com.aspose.pdf.TextFragment-) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getParent()](#getParent--) | Gibt das übergeordnete Element dieses `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` zurück. |
|
|  | [getWidth()](#getWidth--) | Ermittelt die Breite dieses `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` in Punkten. |
|
|  | [getHeight()](#getHeight--) | Ermittelt die Höhe dieses `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` in Punkten. |
|
|  | [getX()](#getX--) | Ermittelt den horizontalen Versatz dieses `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` vom linken Seitenrand in Punkten. |
|
|  | [getY()](#getY--) | Ermittelt den vertikalen Versatz dieses `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` vom unteren Seitenrand in Punkten. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Ermittelt den Rotationswinkel dieses `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` in Grad. |
|
|  | [getText()](#getText--) | Ermittelt den Text dieses `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Setzt den Text dieses `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Ermittelt die Sammlung formatierter Textfragmente dieses `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`. |
|
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | Ermittelt die `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` dieses `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`. |
|
| [remove()](#remove--) |  |
### PdfTextPossibleWatermark(PdfPage parent, TextFragment fragment) {#PdfTextPossibleWatermark-com.groupdocs.watermark.contents.PdfPage-com.aspose.pdf.TextFragment-}
```
public PdfTextPossibleWatermark(PdfPage parent, TextFragment fragment)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parent | [PdfPage](../../com.groupdocs.watermark.contents/pdfpage) |  |
| Fragment | com.aspose.pdf.TextFragment |  |

### getParent() {#getParent--}
```
public ContentPart getParent()
```


Gibt das übergeordnete Element dieses `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` zurück.


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Ermittelt die Breite dieses `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` in Punkten.


**Returns:**
double - Die Breite dieses `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` in Punkten.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Ermittelt die Höhe dieses `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` in Punkten.


**Returns:**
double - Die Höhe dieses `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` in Punkten.

### getX() {#getX--}
```
public double getX()
```


Ermittelt den horizontalen Versatz dieses `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` vom linken Seitenrand in Punkten.


**Returns:**
double - Die x-Koordinate dieses `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### getY() {#getY--}
```
public double getY()
```


Ermittelt den vertikalen Versatz dieses `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` vom unteren Seitenrand in Punkten.


**Returns:**
double - Die y-Koordinate dieses `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Ermittelt den Rotationswinkel dieses `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` in Grad.


**Returns:**
double - Der Wert ist für diesen Typ von möglichem Wasserzeichen immer 0.

### getText() {#getText--}
```
public String getText()
```


Ermittelt den Text dieses `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.


**Returns:**
java.lang.String - Der Text dieses `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Setzt den Text dieses `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | java.lang.String | Der Text dieses `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public FormattedTextFragmentCollection getFormattedTextFragments()
```


Ermittelt die Sammlung formatierter Textfragmente dieses `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


Ermittelt die `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` dieses `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.


**Returns:**
int - `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` dieses `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### remove() {#remove--}
```
public void remove()
```




