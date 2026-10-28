---
title: "PresentationBaseShape"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Fournit la classe de base abstraite pour les formes de tous types dans un document PowerPoint."
type: docs
weight: 77
url: /fr/java/com.groupdocs.watermark.contents/presentationbaseshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.ITwoDObject](../../com.groupdocs.watermark.search/itwodobject), [com.groupdocs.watermark.contents.IPresentationHyperlinkContainer](../../com.groupdocs.watermark.contents/ipresentationhyperlinkcontainer)
```
public abstract class PresentationBaseShape extends ShapeSearchAdapter implements ITwoDObject, IPresentationHyperlinkContainer
```

Fournit la classe de base abstraite pour les formes de tous types dans un document PowerPoint.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getPresentation()](#getPresentation--) | Obtient la présentation parente de cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getImageFillFormat()](#getImageFillFormat--) | Obtient les paramètres du format de remplissage d'image de cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getName()](#getName--) | Obtient le nom de cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Obtient le texte descriptif (alternatif) associé à cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Définit le texte descriptif (alternatif) associé à cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getId()](#getId--) | Obtient l'identifiant de cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getZOrderPosition()](#getZOrderPosition--) | Obtient la position de cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` dans l'ordre Z. |
|
|  | [getHyperlink(int actionType)](#getHyperlink-int-) | Obtient le lien hypertexte associé à cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [setHyperlink(int actionType, String url)](#setHyperlink-int-java.lang.String-) | Définit le lien hypertexte associé à cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|
|  | [getX()](#getX--) | Obtient le décalage horizontal de cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` depuis la bordure gauche de la présentation en points. |
|
|  | [setX(double value)](#setX-double-) | Définit le décalage horizontal de cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` depuis la bordure gauche de la présentation en points. |
|
|  | [getY()](#getY--) | Obtient ou définit le décalage vertical de cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` depuis la bordure supérieure de la présentation en points. |
|
|  | [setY(double value)](#setY-double-) | Obtient ou définit le décalage vertical de cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` depuis la bordure supérieure de la présentation en points. |
|
|  | [getWidth()](#getWidth--) | Obtient la largeur de cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` en points. |
|
|  | [setWidth(double value)](#setWidth-double-) | Définit la largeur de cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` en points. |
|
|  | [getHeight()](#getHeight--) | Obtient la hauteur de cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` en points. |
|
|  | [setHeight(double value)](#setHeight-double-) | Définit la hauteur de cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` en points. |
|
### getPresentation() {#getPresentation--}
```
public final PresentationBaseSlide getPresentation()
```


Obtient la présentation parente de cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Returns:**
[PresentationBaseSlide](../../com.groupdocs.watermark.contents/presentationbaseslide) - The parent presentation of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getImageFillFormat() {#getImageFillFormat--}
```
public final PresentationImageFillFormat getImageFillFormat()
```


Obtient les paramètres du format de remplissage d'image de cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Returns:**
[PresentationImageFillFormat](../../com.groupdocs.watermark.contents/presentationimagefillformat) - The image fill format settings of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getName() {#getName--}
```
public final String getName()
```


Obtient le nom de cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Returns:**
java.lang.String - Le nom de cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Obtient le texte descriptif (alternatif) associé à cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Returns:**
java.lang.String - Le texte descriptif (alternatif) associé à cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Définit le texte descriptif (alternatif) associé à cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | java.lang.String | Le texte descriptif (alternatif) associé à cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|

### getId() {#getId--}
```
public final long getId()
```


Obtient l'identifiant de cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Returns:**
long - L'identifiant de cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getZOrderPosition() {#getZOrderPosition--}
```
public final int getZOrderPosition()
```


Obtient la position de cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` dans l'ordre Z.

Une forme avec un ordre Z supérieur est toujours devant une forme avec un ordre Z inférieur.


**Returns:**
int - La position de cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` dans l'ordre Z.

### getHyperlink(int actionType) {#getHyperlink-int-}
```
public final String getHyperlink(int actionType)
```


Obtient le lien hypertexte associé à cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | actionType | int | L'action qui active le lien hypertexte. |
|

**Returns:**
java.lang.String - L'url du lien hypertexte qui est activé lors de l'action spécifiée.

### setHyperlink(int actionType, String url) {#setHyperlink-int-java.lang.String-}
```
public final void setHyperlink(int actionType, String url)
```


Définit le lien hypertexte associé à cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | actionType | int | L'action qui active le lien hypertexte. |
|
|  | url | java.lang.String | L'url du lien hypertexte. |
|

### getX() {#getX--}
```
public final double getX()
```


Obtient le décalage horizontal de cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` depuis la bordure gauche de la présentation en points.


**Returns:**
double - La coordonnée x de cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Définit le décalage horizontal de cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` depuis la bordure gauche de la présentation en points.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | double | La coordonnée x de cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|

### getY() {#getY--}
```
public final double getY()
```


Obtient ou définit le décalage vertical de cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` depuis la bordure supérieure de la présentation en points.


**Returns:**
double - La coordonnée y de cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Obtient ou définit le décalage vertical de cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` depuis la bordure supérieure de la présentation en points.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | double | La coordonnée y de cet `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Obtient la largeur de cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` en points.


**Returns:**
double - La largeur de cet `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` en points.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Définit la largeur de cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` en points.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | double | La largeur de cet `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` en points. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Obtient la hauteur de cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` en points.


**Returns:**
double - La hauteur de cet `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` en points.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Définit la hauteur de cette `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` en points.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | double | La hauteur de cet `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` en points. |
|

