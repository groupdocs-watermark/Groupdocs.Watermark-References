---
title: "PdfTextPossibleWatermark"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente un filigrane possible dans le texte d'un document PDF."
type: docs
weight: 43
url: /fr/java/com.groupdocs.watermark.search/pdftextpossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)
```
public class PdfTextPossibleWatermark extends PossibleWatermark
```

Représente un filigrane possible dans le texte d'un document PDF.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfTextPossibleWatermark(PdfPage parent, TextFragment fragment)](#PdfTextPossibleWatermark-com.groupdocs.watermark.contents.PdfPage-com.aspose.pdf.TextFragment-) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getParent()](#getParent--) | Obtient le parent de cet `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`. |
|
|  | [getWidth()](#getWidth--) | Obtient la largeur de cet `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` en points. |
|
|  | [getHeight()](#getHeight--) | Obtient la hauteur de cet `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` en points. |
|
|  | [getX()](#getX--) | Obtient le décalage horizontal de cet `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` par rapport à la bordure gauche de la page en points. |
|
|  | [getY()](#getY--) | Obtient le décalage vertical de cet `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` par rapport à la bordure inférieure de la page en points. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Obtient l'angle de rotation de cet `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` en degrés. |
|
|  | [getText()](#getText--) | Obtient le texte de cet `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Définit le texte de cet `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Obtient la collection de fragments de texte formatés de cet `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`. |
|
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | Obtient le `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` de cet `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`. |
|
| [remove()](#remove--) |  |
### PdfTextPossibleWatermark(PdfPage parent, TextFragment fragment) {#PdfTextPossibleWatermark-com.groupdocs.watermark.contents.PdfPage-com.aspose.pdf.TextFragment-}
```
public PdfTextPossibleWatermark(PdfPage parent, TextFragment fragment)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| parent | [PdfPage](../../com.groupdocs.watermark.contents/pdfpage) |  |
| fragment | com.aspose.pdf.TextFragment |  |

### getParent() {#getParent--}
```
public ContentPart getParent()
```


Obtient le parent de cet `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Obtient la largeur de cet `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` en points.


**Returns:**
double - La largeur de cet `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` en points.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Obtient la hauteur de cet `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` en points.


**Returns:**
double - La hauteur de cet `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` en points.

### getX() {#getX--}
```
public double getX()
```


Obtient le décalage horizontal de cet `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` par rapport à la bordure gauche de la page en points.


**Returns:**
double - La coordonnée x de cet `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### getY() {#getY--}
```
public double getY()
```


Obtient le décalage vertical de cet `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` par rapport à la bordure inférieure de la page en points.


**Returns:**
double - La coordonnée y de cet `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Obtient l'angle de rotation de cet `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)` en degrés.


**Returns:**
double - La valeur est toujours 0 pour ce type de filigrane possible.

### getText() {#getText--}
```
public String getText()
```


Obtient le texte de cet `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.


**Returns:**
java.lang.String - Le texte de cet `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Définit le texte de cet `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | java.lang.String | Le texte de cet `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public FormattedTextFragmentCollection getFormattedTextFragments()
```


Obtient la collection de fragments de texte formatés de cet `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


Obtient le `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` de cet `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.


**Returns:**
int - `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` de cet `[PdfTextPossibleWatermark](../../com.groupdocs.watermark.search/pdftextpossiblewatermark)`.

### remove() {#remove--}
```
public void remove()
```




