---
title: "PdfTextPossibleWatermark"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar möjlig vattenstämpel i PDF‑dokumentets text."
type: docs
weight: 43
url: /sv/java/com.groupdocs.watermark.search/pdftextpossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)
```
public class PdfTextPossibleWatermark extends PossibleWatermark
```

Representerar möjlig vattenstämpel i PDF‑dokumentets text.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PdfTextPossibleWatermark(PdfPage parent, TextFragment fragment)](#PdfTextPossibleWatermark-com.groupdocs.watermark.contents.PdfPage-com.aspose.pdf.TextFragment-) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getParent()](#getParent--) | Hämtar föräldern till detta `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`. |
|
|  | [getWidth()](#getWidth--) | Hämtar bredden på detta `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` i punkter. |
|
|  | [getHeight()](#getHeight--) | Hämtar höjden på detta `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` i punkter. |
|
|  | [getX()](#getX--) | Hämtar den horisontella förskjutningen för detta `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` från sidans vänstra kant i punkter. |
|
|  | [getY()](#getY--) | Hämtar den vertikala förskjutningen för detta `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` från sidans nedre kant i punkter. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Hämtar rotationsvinkeln för detta `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` i grader. |
|
|  | [getText()](#getText--) | Hämtar texten för detta `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Ställer in texten för detta `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Hämtar samlingen av formaterade textfragment för detta `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`. |
|
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | Hämtar `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` för detta `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`. |
|
| [remove()](#remove--) |  |
### PdfTextPossibleWatermark(PdfPage parent, TextFragment fragment) {#PdfTextPossibleWatermark-com.groupdocs.watermark.contents.PdfPage-com.aspose.pdf.TextFragment-}
```
public PdfTextPossibleWatermark(PdfPage parent, TextFragment fragment)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parent | [PdfPage](../../com.groupdocs.watermark.contents/pdfpage) |  |
| fragment | com.aspose.pdf.TextFragment |  |

### getParent() {#getParent--}
```
public ContentPart getParent()
```


Hämtar föräldern till detta `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Hämtar bredden på detta `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` i punkter.


**Returns:**
double - bredden på detta `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` i punkter.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Hämtar höjden på detta `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` i punkter.


**Returns:**
double - höjden på detta `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` i punkter.

### getX() {#getX--}
```
public double getX()
```


Hämtar den horisontella förskjutningen för detta `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` från sidans vänstra kant i punkter.


**Returns:**
double - x-koordinaten för detta `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### getY() {#getY--}
```
public double getY()
```


Hämtar den vertikala förskjutningen för detta `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` från sidans nedre kant i punkter.


**Returns:**
double - y-koordinaten för detta `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Hämtar rotationsvinkeln för detta `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` i grader.


**Returns:**
double - Värdet är alltid 0 för denna typ av möjlig vattenstämpel.

### getText() {#getText--}
```
public String getText()
```


Hämtar texten för detta `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.


**Returns:**
java.lang.String - texten för detta `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Ställer in texten för detta `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | java.lang.String | Texten för detta `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public FormattedTextFragmentCollection getFormattedTextFragments()
```


Hämtar samlingen av formaterade textfragment för detta `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


Hämtar `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` för detta `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.


**Returns:**
int - `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` för detta `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### remove() {#remove--}
```
public void remove()
```




