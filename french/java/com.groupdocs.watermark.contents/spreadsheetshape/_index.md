---
title: "SpreadsheetShape"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente une forme de dessin dans un document Excel."
type: docs
weight: 117
url: /fr/java/com.groupdocs.watermark.contents/spreadsheetshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject), [com.groupdocs.watermark.search.IHyperlinkContainer](../../com.groupdocs.watermark.search/ihyperlinkcontainer)
```
public class SpreadsheetShape extends ShapeSearchAdapter implements IRotatableTwoDObject, IHyperlinkContainer
```

Représente une forme de dessin dans un document Excel.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getWorksheet()](#getWorksheet--) | Obtient la feuille de calcul parente de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getAutoShapeType()](#getAutoShapeType--) | Obtient le type de forme automatique. |
|
|  | [getMsoDrawingType()](#getMsoDrawingType--) | Obtient le type de dessin mso. |
|
|  | [getText()](#getText--) | Obtient le texte de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Définit le texte de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Obtient la collection de fragments de texte formatés de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getImage()](#getImage--) | Obtient l'image de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [setImage(SpreadsheetWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | Définit l'image de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getImageFillFormat()](#getImageFillFormat--) | Obtient les paramètres du format de remplissage d'image de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getId()](#getId--) | Obtient l'identifiant de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Obtient le texte descriptif (alternatif) associé à ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Définit le texte descriptif (alternatif) associé à ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [isWordArt()](#isWordArt--) | Obtient une valeur indiquant si ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` est un objet WordArt. |
|
|  | [getName()](#getName--) | Obtient le nom de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getAsposeCellsShape()](#getAsposeCellsShape--) | <br /> |

|
|  | [getHyperlink()](#getHyperlink--) | Obtient le lien hypertexte associé à ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [setHyperlink(String value)](#setHyperlink-java.lang.String-) | Définit le lien hypertexte associé à ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|
|  | [getX()](#getX--) | Obtient le décalage horizontal de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` par rapport à la bordure gauche de la feuille de calcul en points. |
|
|  | [setX(double value)](#setX-double-) | Définit le décalage horizontal de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` par rapport à la bordure gauche de la feuille de calcul en points. |
|
|  | [getY()](#getY--) | Obtient le décalage vertical de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` par rapport à la bordure supérieure de la feuille de calcul en points. |
|
|  | [setY(double value)](#setY-double-) | Définit le décalage vertical de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` par rapport à la bordure supérieure de la feuille de calcul en points. |
|
|  | [getWidth()](#getWidth--) | Obtient la largeur de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en points. |
|
|  | [setWidth(double value)](#setWidth-double-) | Définit la largeur de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en points. |
|
|  | [getHeight()](#getHeight--) | Obtient la hauteur de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en points. |
|
|  | [setHeight(double value)](#setHeight-double-) | Définit la hauteur de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en points. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Obtient ou définit l'angle de rotation de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en degrés. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Obtient ou définit l'angle de rotation de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en degrés. |
|
|  | [getImageForSearch()](#getImageForSearch--) | <br /> |

|
|  | [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) | <br /> |

|
|  | [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) | <br /> |

|
|  | [getTextForSearch()](#getTextForSearch--) | <br /> |

|
|  | [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) | <br /> |

|
### getWorksheet() {#getWorksheet--}
```
public final SpreadsheetWorksheet getWorksheet()
```


Obtient la feuille de calcul parente de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) - The parent worksheet of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getAutoShapeType() {#getAutoShapeType--}
```
public final int getAutoShapeType()
```


Obtient le type de forme automatique.


**Returns:**
int - Le type de forme automatique.

### getMsoDrawingType() {#getMsoDrawingType--}
```
public final int getMsoDrawingType()
```


Obtient le type de dessin mso.


**Returns:**
int - Le type de dessin mso.

### getText() {#getText--}
```
public final String getText()
```


Obtient le texte de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
java.lang.String - Le texte de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Définit le texte de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | java.lang.String | Le texte de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Obtient la collection de fragments de texte formatés de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getImage() {#getImage--}
```
public final SpreadsheetWatermarkableImage getImage()
```


Obtient l'image de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The image of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` or null if the shape has no image.

### setImage(SpreadsheetWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public final void setImage(SpreadsheetWatermarkableImage value)
```


Définit l'image de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | L'image de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` ou null si l'image doit être supprimée. |
|

### getImageFillFormat() {#getImageFillFormat--}
```
public final SpreadsheetImageFillFormat getImageFillFormat()
```


Obtient les paramètres du format de remplissage d'image de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
[SpreadsheetImageFillFormat](../../com.groupdocs.watermark.contents/spreadsheetimagefillformat) - The image fill format settings of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getId() {#getId--}
```
public final int getId()
```


Obtient l'identifiant de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
int - L'identifiant de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Obtient le texte descriptif (alternatif) associé à ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
java.lang.String - Le texte descriptif (alternatif) associé à ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Définit le texte descriptif (alternatif) associé à ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | java.lang.String | Le texte descriptif (alternatif) associé à ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### isWordArt() {#isWordArt--}
```
public final boolean isWordArt()
```


Obtient une valeur indiquant si ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` est un objet WordArt.


**Returns:**
boolean - Vrai si la forme est un objet WordArt ; sinon, faux.

### getName() {#getName--}
```
public final String getName()
```


Obtient le nom de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
java.lang.String - Le nom de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getAsposeCellsShape() {#getAsposeCellsShape--}
```
public final Shape getAsposeCellsShape()
```


<br />



**Returns:**
com.aspose.cells.Shape
### getHyperlink() {#getHyperlink--}
```
public final String getHyperlink()
```


Obtient le lien hypertexte associé à ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Returns:**
java.lang.String - Le lien hypertexte associé à ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setHyperlink(String value) {#setHyperlink-java.lang.String-}
```
public final void setHyperlink(String value)
```


Définit le lien hypertexte associé à ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | java.lang.String | Le lien hypertexte associé à ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### getX() {#getX--}
```
public final double getX()
```


Obtient le décalage horizontal de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` par rapport à la bordure gauche de la feuille de calcul en points.


**Returns:**
double - La coordonnée x de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Définit le décalage horizontal de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` par rapport à la bordure gauche de la feuille de calcul en points.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | double | La coordonnée x de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### getY() {#getY--}
```
public final double getY()
```


Obtient le décalage vertical de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` par rapport à la bordure supérieure de la feuille de calcul en points.


**Returns:**
double - La coordonnée y de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Définit le décalage vertical de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` par rapport à la bordure supérieure de la feuille de calcul en points.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | double | La coordonnée y de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Obtient la largeur de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en points.


**Returns:**
double - La largeur de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en points.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Définit la largeur de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en points.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | double | La largeur de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en points. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Obtient la hauteur de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en points.


**Returns:**
double - La hauteur de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en points.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Définit la hauteur de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en points.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | double | La hauteur de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en points. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Obtient ou définit l'angle de rotation de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en degrés.


**Returns:**
double - L'angle de rotation de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en degrés.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Obtient ou définit l'angle de rotation de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en degrés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | double | L'angle de rotation de ce `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` en degrés. |
|

### getImageForSearch() {#getImageForSearch--}
```
public WatermarkableImage getImageForSearch()
```


<br />



**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### setFoundWatermarkImage(byte[] imageData) {#setFoundWatermarkImage-byte---}
```
public void setFoundWatermarkImage(byte[] imageData)
```


<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageData | byte[] |  |

### getFormattedTextFragmentsForSearch() {#getFormattedTextFragmentsForSearch--}
```
public FormattedTextFragmentCollection getFormattedTextFragmentsForSearch()
```


<br />



**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
### getTextForSearch() {#getTextForSearch--}
```
public String getTextForSearch()
```


<br />



**Returns:**
java.lang.String
### setFoundWatermarkText(String value) {#setFoundWatermarkText-java.lang.String-}
```
public void setFoundWatermarkText(String value)
```


<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

