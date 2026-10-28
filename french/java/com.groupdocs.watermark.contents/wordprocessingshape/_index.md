---
title: "WordProcessingShape"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente une forme de dessin dans un document Word."
type: docs
weight: 141
url: /fr/java/com.groupdocs.watermark.contents/wordprocessingshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject), [com.groupdocs.watermark.search.IHyperlinkContainer](../../com.groupdocs.watermark.search/ihyperlinkcontainer)
```
public class WordProcessingShape extends ShapeSearchAdapter implements IRotatableTwoDObject, IHyperlinkContainer
```

Représente une forme de dessin dans un document Word.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getSection()](#getSection--) | Obtient la section parente de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getHeaderFooter()](#getHeaderFooter--) | Obtient l'en-tête/pied de page parent de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` (si présent). |
|
|  | [getShapeType()](#getShapeType--) | Obtient le type de forme. |
|
|  | [isWordArt()](#isWordArt--) | Obtient une valeur indiquant si ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` est un objet WordArt. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Obtient le texte descriptif (alternatif) associé à ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Définit le texte descriptif (alternatif) associé à ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getName()](#getName--) | Obtient le nom de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getBehindText()](#getBehindText--) | Obtient une valeur indiquant si la forme est au-dessus ou derrière le texte. |
|
|  | [setBehindText(boolean value)](#setBehindText-boolean-) | Définit une valeur indiquant si la forme est au-dessus ou derrière le texte. |
|
|  | [getText()](#getText--) | Obtient le texte de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Définit le texte de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Obtient la collection de fragments de texte formatés de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getImage()](#getImage--) | Obtient l'image de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [setImage(WordProcessingWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.WordProcessingWatermarkableImage-) | Définit l'image de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | Obtient une valeur spécifiant comment la forme est positionnée horizontalement. |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | Obtient une valeur spécifiant comment la forme est positionnée verticalement. |
|
|  | [getRelativeHorizontalPosition()](#getRelativeHorizontalPosition--) | Obtient une valeur spécifiant par rapport à quoi la forme est positionnée horizontalement. |
|
|  | [getRelativeVerticalPosition()](#getRelativeVerticalPosition--) | Obtient une valeur spécifiant par rapport à quoi la forme est positionnée verticalement. |
|
| [getImageFillFormat()](#getImageFillFormat--) |  |
| [getAsposeWordsShape()](#getAsposeWordsShape--) |  |
|  | [getHyperlink()](#getHyperlink--) | Obtient le lien hypertexte associé à ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [setHyperlink(String value)](#setHyperlink-java.lang.String-) | Définit le lien hypertexte associé à ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|
|  | [getWidth()](#getWidth--) | Obtient la largeur de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en points. |
|
|  | [setWidth(double value)](#setWidth-double-) | Définit la largeur de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en points. |
|
|  | [getHeight()](#getHeight--) | Obtient la hauteur de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en points. |
|
|  | [setHeight(double value)](#setHeight-double-) | Définit la hauteur de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en points. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Obtient l'angle de rotation de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en degrés. |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | Définit l'angle de rotation de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en degrés. |
|
|  | [getX()](#getX--) | Obtient ou définit le décalage horizontal de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` depuis la bordure gauche de la page en points. |
|
|  | [setX(double value)](#setX-double-) | Obtient ou définit le décalage horizontal de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` depuis la bordure gauche de la page en points. |
|
|  | [getY()](#getY--) | Obtient le décalage vertical de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` depuis la bordure supérieure de la page en points. |
|
|  | [setY(double value)](#setY-double-) | Définit le décalage vertical de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` depuis la bordure supérieure de la page en points. |
|
| [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) |  |
| [getTextForSearch()](#getTextForSearch--) |  |
| [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) |  |
| [getImageForSearch()](#getImageForSearch--) |  |
| [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) |  |
### getSection() {#getSection--}
```
public final WordProcessingSection getSection()
```


Obtient la section parente de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection) - The parent section of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getHeaderFooter() {#getHeaderFooter--}
```
public final WordProcessingHeaderFooter getHeaderFooter()
```


Obtient l'en-tête/pied de page parent de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` (si présent).


**Returns:**
[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter) - The parent header/footer of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


Obtient le type de forme.


**Returns:**
int - Le type de forme.

### isWordArt() {#isWordArt--}
```
public final boolean isWordArt()
```


Obtient une valeur indiquant si ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` est un objet WordArt.


**Returns:**
boolean - Vrai si la forme est un objet WordArt ; sinon, faux.

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Obtient le texte descriptif (alternatif) associé à ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
java.lang.String - Le texte descriptif (alternatif) associé à ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Définit le texte descriptif (alternatif) associé à ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | java.lang.String | Le texte descriptif (alternatif) associé à ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|

### getName() {#getName--}
```
public final String getName()
```


Obtient le nom de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
java.lang.String - Le nom de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getBehindText() {#getBehindText--}
```
public final boolean getBehindText()
```


Obtient une valeur indiquant si la forme est au-dessus ou derrière le texte.


**Returns:**
boolean - La valeur indiquant si la forme est au-dessus ou derrière le texte. Vrai si la forme est derrière le texte ; sinon, faux.

### setBehindText(boolean value) {#setBehindText-boolean-}
```
public final void setBehindText(boolean value)
```


Définit une valeur indiquant si la forme est au-dessus ou derrière le texte.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | La valeur indiquant si la forme est au-dessus ou derrière le texte. Vrai si la forme est derrière le texte ; sinon, faux. |
|

### getText() {#getText--}
```
public final String getText()
```


Obtient le texte de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
java.lang.String - Le texte de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Définit le texte de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | java.lang.String | Le texte de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


Obtient la collection de fragments de texte formatés de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getImage() {#getImage--}
```
public final WordProcessingWatermarkableImage getImage()
```


Obtient l'image de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
[WordProcessingWatermarkableImage](../../com.groupdocs.watermark.contents/wordprocessingwatermarkableimage) - The image of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` or `null` if the shape has no image.

### setImage(WordProcessingWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.WordProcessingWatermarkableImage-}
```
public final void setImage(WordProcessingWatermarkableImage value)
```


Définit l'image de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [WordProcessingWatermarkableImage](../../com.groupdocs.watermark.contents/wordprocessingwatermarkableimage) | L'image de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` ou `null` si l'image doit être supprimée. |
|

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


Obtient une valeur spécifiant comment la forme est positionnée horizontalement.


**Returns:**
int - La valeur d'alignement horizontal.

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Obtient une valeur spécifiant comment la forme est positionnée verticalement.


**Returns:**
int - La valeur d'alignement vertical.

### getRelativeHorizontalPosition() {#getRelativeHorizontalPosition--}
```
public final int getRelativeHorizontalPosition()
```


Obtient une valeur spécifiant par rapport à quoi la forme est positionnée horizontalement.


**Returns:**
int - La valeur de position horizontale relative.

### getRelativeVerticalPosition() {#getRelativeVerticalPosition--}
```
public final int getRelativeVerticalPosition()
```


Obtient une valeur spécifiant par rapport à quoi la forme est positionnée verticalement.


**Returns:**
int - La valeur de position verticale relative.

### getImageFillFormat() {#getImageFillFormat--}
```
public final WordProcessingImageFillFormat getImageFillFormat()
```




**Returns:**
[WordProcessingImageFillFormat](../../com.groupdocs.watermark.internal/wordprocessingimagefillformat)
### getAsposeWordsShape() {#getAsposeWordsShape--}
```
public final Shape getAsposeWordsShape()
```




**Returns:**
com.aspose.words.Shape
### getHyperlink() {#getHyperlink--}
```
public final String getHyperlink()
```


Obtient le lien hypertexte associé à ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Returns:**
java.lang.String - Le lien hypertexte associé à ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setHyperlink(String value) {#setHyperlink-java.lang.String-}
```
public final void setHyperlink(String value)
```


Définit le lien hypertexte associé à ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | java.lang.String | Le lien hypertexte associé à ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Obtient la largeur de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en points.


**Returns:**
double - La largeur de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en points.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Définit la largeur de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en points.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | double | La largeur de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en points. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Obtient la hauteur de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en points.


**Returns:**
double - La hauteur de cet `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en points.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Définit la hauteur de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en points.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | double | La hauteur de cet `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en points. |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


Obtient l'angle de rotation de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en degrés.


**Returns:**
double - L'angle de rotation de cet `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en degrés.

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


Définit l'angle de rotation de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en degrés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | double | L'angle de rotation de cet `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` en degrés. |
|

### getX() {#getX--}
```
public final double getX()
```


Obtient ou définit le décalage horizontal de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` depuis la bordure gauche de la page en points.


**Returns:**
double - La coordonnée x de cet `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Obtient ou définit le décalage horizontal de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` depuis la bordure gauche de la page en points.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | double | La coordonnée x de cet `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|

### getY() {#getY--}
```
public final double getY()
```


Obtient le décalage vertical de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` depuis la bordure supérieure de la page en points.


**Returns:**
double - La coordonnée y de cet `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Définit le décalage vertical de ce `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` depuis la bordure supérieure de la page en points.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | double | La coordonnée y de cet `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`. |
|

### getFormattedTextFragmentsForSearch() {#getFormattedTextFragmentsForSearch--}
```
public FormattedTextFragmentCollection getFormattedTextFragmentsForSearch()
```




**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
### getTextForSearch() {#getTextForSearch--}
```
public String getTextForSearch()
```




**Returns:**
java.lang.String
### setFoundWatermarkText(String value) {#setFoundWatermarkText-java.lang.String-}
```
public void setFoundWatermarkText(String value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getImageForSearch() {#getImageForSearch--}
```
public WatermarkableImage getImageForSearch()
```




**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### setFoundWatermarkImage(byte[] imageData) {#setFoundWatermarkImage-byte---}
```
public void setFoundWatermarkImage(byte[] imageData)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageData | byte[] |  |

