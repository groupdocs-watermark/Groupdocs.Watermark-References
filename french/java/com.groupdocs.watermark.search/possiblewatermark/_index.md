---
title: "PossibleWatermark"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente un filigrane possible trouvé dans un document."
type: docs
weight: 45
url: /fr/java/com.groupdocs.watermark.search/possiblewatermark/
---
**Inheritance:**
java.lang.Object
```
public abstract class PossibleWatermark
```

Représente un filigrane possible trouvé dans un document.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PossibleWatermark()](#PossibleWatermark--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getParent()](#getParent--) | Obtient le parent de ce `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
| [getPageNumber()](#getPageNumber--) |  |
|  | [getWidth()](#getWidth--) | Obtient la largeur de ce `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
|  | [getHeight()](#getHeight--) | Obtient la hauteur de ce `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
|  | [getX()](#getX--) | Obtient la coordonnée x de ce `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
|  | [getY()](#getY--) | Obtient la coordonnée y de ce `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Obtient l'angle de rotation de ce `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` en degrés. |
|
|  | [getText()](#getText--) | Obtient le texte de ce `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Définit le texte de ce `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Obtient la collection de fragments de texte formatés de ce `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
|  | [getImageData()](#getImageData--) | Obtient ou définit l'image de ce `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
| [setImageData(byte[] value)](#setImageData-byte---) |  |
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | Obtient l'unité de mesure `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` de ce `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|
| [getCollection()](#getCollection--) |  |
| [setCollection(PossibleWatermarkCollection value)](#setCollection-com.groupdocs.watermark.search.PossibleWatermarkCollection-) |  |
| [getImageSize()](#getImageSize--) |  |
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### PossibleWatermark() {#PossibleWatermark--}
```
public PossibleWatermark()
```




### getParent() {#getParent--}
```
public abstract ContentPart getParent()
```


Obtient le parent de ce `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```




**Returns:**
java.lang.Integer
### getWidth() {#getWidth--}
```
public double getWidth()
```


Obtient la largeur de ce `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Returns:**
double - La largeur de ce `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Obtient la hauteur de ce `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Returns:**
double - La hauteur de ce `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getX() {#getX--}
```
public double getX()
```


Obtient la coordonnée x de ce `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Returns:**
double - La coordonnée x de ce `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getY() {#getY--}
```
public double getY()
```


Obtient la coordonnée y de ce `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Returns:**
double - La coordonnée y de ce `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Obtient l'angle de rotation de ce `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` en degrés.


**Returns:**
double - L'angle de rotation de ce `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getText() {#getText--}
```
public String getText()
```


Obtient le texte de ce `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Returns:**
java.lang.String - Le texte de ce `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Définit le texte de ce `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | java.lang.String | Le texte de ce `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public FormattedTextFragmentCollection getFormattedTextFragments()
```


Obtient la collection de fragments de texte formatés de ce `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Obtient ou définit l'image de ce `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Returns:**
byte[] - L'image de ce `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` ou null si le filigrane n'a pas d'image.

### setImageData(byte[] value) {#setImageData-byte---}
```
public final void setImageData(byte[] value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


Obtient l'unité de mesure `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` de ce `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.


**Returns:**
int - L'unité de mesure `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` de ce `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

### getCollection() {#getCollection--}
```
public final PossibleWatermarkCollection getCollection()
```




**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection)
### setCollection(PossibleWatermarkCollection value) {#setCollection-com.groupdocs.watermark.search.PossibleWatermarkCollection-}
```
public final void setCollection(PossibleWatermarkCollection value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection) |  |

### getImageSize() {#getImageSize--}
```
public final Size getImageSize()
```




**Returns:**
[Size](../../com.groupdocs.watermark.internal/size)
### getImageInternally() {#getImageInternally--}
```
public WatermarkableImage getImageInternally()
```




**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### remove() {#remove--}
```
public abstract void remove()
```




