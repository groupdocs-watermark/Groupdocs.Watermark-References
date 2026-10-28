---
title: "PdfTextPossibleWatermark"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt mogelijk watermerk in pdf-documenttekst voor."
type: docs
weight: 43
url: /nl/java/com.groupdocs.watermark.search/pdftextpossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)
```
public class PdfTextPossibleWatermark extends PossibleWatermark
```

Stelt mogelijk watermerk in pdf-documenttekst voor.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PdfTextPossibleWatermark(PdfPage parent, TextFragment fragment)](#PdfTextPossibleWatermark-com.groupdocs.watermark.contents.PdfPage-com.aspose.pdf.TextFragment-) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getParent()](#getParent--) | Haalt de ouder van dit `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` op. |
|
|  | [getWidth()](#getWidth--) | Haalt de breedte van dit `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` op in punten. |
|
|  | [getHeight()](#getHeight--) | Haalt de hoogte van dit `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` op in punten. |
|
|  | [getX()](#getX--) | Haalt de horizontale offset van dit `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` vanaf de linkerrand van de pagina op in punten. |
|
|  | [getY()](#getY--) | Haalt de verticale offset van dit `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` vanaf de onderrand van de pagina op in punten. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Haalt de rotatiehoek van dit `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` op in graden. |
|
|  | [getText()](#getText--) | Haalt de tekst van dit `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` op. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Stelt de tekst van dit `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` in. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Haalt de collectie van geformatteerde tekstfragmenten van dit `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` op. |
|
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | Haalt de `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` van dit `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` op. |
|
| [remove()](#remove--) |  |
### PdfTextPossibleWatermark(PdfPage parent, TextFragment fragment) {#PdfTextPossibleWatermark-com.groupdocs.watermark.contents.PdfPage-com.aspose.pdf.TextFragment-}
```
public PdfTextPossibleWatermark(PdfPage parent, TextFragment fragment)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parent | [PdfPage](../../com.groupdocs.watermark.contents/pdfpage) |  |
| fragment | com.aspose.pdf.TextFragment |  |

### getParent() {#getParent--}
```
public ContentPart getParent()
```


Haalt de ouder van dit `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` op.


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Haalt de breedte van dit `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` op in punten.


**Returns:**
double - De breedte van dit `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` in punten.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Haalt de hoogte van dit `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` op in punten.


**Returns:**
double - De hoogte van dit `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` in punten.

### getX() {#getX--}
```
public double getX()
```


Haalt de horizontale offset van dit `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` vanaf de linkerrand van de pagina op in punten.


**Returns:**
double - De x-coördinaat van dit `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### getY() {#getY--}
```
public double getY()
```


Haalt de verticale offset van dit `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` vanaf de onderrand van de pagina op in punten.


**Returns:**
double - De y-coördinaat van dit `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Haalt de rotatiehoek van dit `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` op in graden.


**Returns:**
double - De waarde is altijd 0 voor dit type mogelijke watermerk.

### getText() {#getText--}
```
public String getText()
```


Haalt de tekst van dit `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` op.


**Returns:**
java.lang.String - De tekst van dit `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Stelt de tekst van dit `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | java.lang.String | De tekst van dit `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public FormattedTextFragmentCollection getFormattedTextFragments()
```


Haalt de collectie van geformatteerde tekstfragmenten van dit `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` op.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


Haalt de `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` van dit `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` op.


**Returns:**
int - `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` van dit `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### remove() {#remove--}
```
public void remove()
```




