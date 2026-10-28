---
title: "SpreadsheetHeaderFooterPossibleWatermark"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente un filigrane possible dans l'en-tête ou le pied de page d'un document Excel."
type: docs
weight: 62
url: /fr/java/com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)
```
public class SpreadsheetHeaderFooterPossibleWatermark extends PossibleWatermark
```

Représente un filigrane possible dans l'en-tête ou le pied de page d'un document Excel.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SpreadsheetHeaderFooterPossibleWatermark(SpreadsheetHeaderFooterSection section)](#SpreadsheetHeaderFooterPossibleWatermark-com.groupdocs.watermark.contents.SpreadsheetHeaderFooterSection-) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getParent()](#getParent--) | Obtient le parent de ce `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`. |
|
|  | [getWidth()](#getWidth--) | Obtient la largeur de ce `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` en points. |
|
|  | [getHeight()](#getHeight--) | Obtient la hauteur de ce `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` en points. |
|
|  | [getX()](#getX--) | Obtient le décalage horizontal de ce `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` par rapport à la bordure gauche de la feuille de calcul en points. |
|
|  | [getY()](#getY--) | Obtient le décalage vertical de ce `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` par rapport à la bordure supérieure de la feuille de calcul en points. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Obtient l'angle de rotation de ce `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` en degrés. |
|
|  | [getText()](#getText--) | Obtient le texte de ce `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Définit le texte de ce `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`. |
|
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | Obtient le `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` de ce `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`. |
|
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### SpreadsheetHeaderFooterPossibleWatermark(SpreadsheetHeaderFooterSection section) {#SpreadsheetHeaderFooterPossibleWatermark-com.groupdocs.watermark.contents.SpreadsheetHeaderFooterSection-}
```
public SpreadsheetHeaderFooterPossibleWatermark(SpreadsheetHeaderFooterSection section)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| section | [SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection) |  |

### getParent() {#getParent--}
```
public ContentPart getParent()
```


Obtient le parent de ce `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`.


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Obtient la largeur de ce `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` en points.


**Returns:**
double - La largeur de ce `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` en points.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Obtient la hauteur de ce `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` en points.


**Returns:**
double - La hauteur de ce `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` en points.

### getX() {#getX--}
```
public double getX()
```


Obtient le décalage horizontal de ce `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` par rapport à la bordure gauche de la feuille de calcul en points.


**Returns:**
double - La coordonnée x de ce `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`.

### getY() {#getY--}
```
public double getY()
```


Obtient le décalage vertical de ce `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` par rapport à la bordure supérieure de la feuille de calcul en points.


**Returns:**
double - La coordonnée y de ce `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Obtient l'angle de rotation de ce `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` en degrés.


**Returns:**
double - L'angle de rotation de ce `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)` en degrés.

### getText() {#getText--}
```
public String getText()
```


Obtient le texte de ce `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`.


**Returns:**
java.lang.String - Le texte de ce `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Définit le texte de ce `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | java.lang.String | Le texte de ce `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`. |
|

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


Obtient le `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` de ce `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`.


**Returns:**
int - Le `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` de ce `[SpreadsheetHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheetheaderfooterpossiblewatermark)`.

### getImageInternally() {#getImageInternally--}
```
public WatermarkableImage getImageInternally()
```




**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### remove() {#remove--}
```
public void remove()
```




