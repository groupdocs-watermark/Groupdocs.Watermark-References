---
title: "SpreadsheetAttachment"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente un fichier joint à un document Excel."
type: docs
weight: 101
url: /fr/java/com.groupdocs.watermark.contents/spreadsheetattachment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.ITwoDObject](../../com.groupdocs.watermark.search/itwodobject)
```
public class SpreadsheetAttachment extends Attachment implements ITwoDObject
```

Représente un fichier joint à un document Excel.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getContent()](#getContent--) | Obtient le contenu du fichier joint. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | Définit le contenu du fichier joint. |
|
|  | [getPreviewImageContent()](#getPreviewImageContent--) | Obtient l'image d'aperçu du fichier joint sous forme de tableau d'octets. |
|
|  | [setPreviewImageContent(byte[] value)](#setPreviewImageContent-byte---) | Définit l'image d'aperçu du fichier joint sous forme de tableau d'octets. |
|
|  | [isLink()](#isLink--) | Obtient une valeur indiquant si le contenu ne contient qu'un lien vers le fichier. |
|
|  | [getSourceFullName()](#getSourceFullName--) | Obtient le nom complet du fichier joint. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Obtient le texte descriptif (alternatif) associé au fichier joint. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Définit le texte descriptif (alternatif) associé au fichier joint. |
|
|  | [getAsposeOleObject()](#getAsposeOleObject--) | <br /> |

|
|  | [getX()](#getX--) | Obtient le décalage horizontal du cadre de la pièce jointe par rapport à la bordure gauche de la feuille de calcul en points. |
|
|  | [setX(double value)](#setX-double-) | Définit le décalage horizontal du cadre de la pièce jointe par rapport à la bordure gauche de la feuille de calcul en points. |
|
|  | [getY()](#getY--) | Obtient le décalage vertical du cadre de la pièce jointe par rapport à la bordure supérieure de la feuille de calcul en points. |
|
|  | [setY(double value)](#setY-double-) | Définit le décalage vertical du cadre de la pièce jointe par rapport à la bordure supérieure de la feuille de calcul en points. |
|
|  | [getWidth()](#getWidth--) | Obtient la largeur du cadre de la pièce jointe en points. |
|
|  | [setWidth(double value)](#setWidth-double-) | Définit la largeur du cadre de la pièce jointe en points. |
|
|  | [getHeight()](#getHeight--) | Obtient la hauteur du cadre de la pièce jointe en points. |
|
|  | [setHeight(double value)](#setHeight-double-) | Définit la hauteur du cadre de la pièce jointe en points. |
|
|  | [checkImageType()](#checkImageType--) | <br /> |

|
### getContent() {#getContent--}
```
public byte[] getContent()
```


Obtient le contenu du fichier joint.


**Returns:**
byte[] - Le contenu du fichier joint.

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


Définit le contenu du fichier joint.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | byte[] | Le contenu du fichier joint. |
|

### getPreviewImageContent() {#getPreviewImageContent--}
```
public final byte[] getPreviewImageContent()
```


Obtient l'image d'aperçu du fichier joint sous forme de tableau d'octets.


**Returns:**
byte[] - L'image d'aperçu du fichier joint sous forme de tableau d'octets.

### setPreviewImageContent(byte[] value) {#setPreviewImageContent-byte---}
```
public final void setPreviewImageContent(byte[] value)
```


Définit l'image d'aperçu du fichier joint sous forme de tableau d'octets.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | byte[] | L'image d'aperçu du fichier joint sous forme de tableau d'octets. |
|

### isLink() {#isLink--}
```
public final boolean isLink()
```


Obtient une valeur indiquant si le contenu ne contient qu'un lien vers le fichier.


**Returns:**
boolean - Vrai si le fichier joint est référencé par un lien (le contenu ne contient pas le contenu du fichier joint) ; sinon, faux.

### getSourceFullName() {#getSourceFullName--}
```
public final String getSourceFullName()
```


Obtient le nom complet du fichier joint.


**Returns:**
java.lang.String - Le nom complet du fichier joint.

<br />

*** ** * ** ***

L'extension est utilisée pour déterminer l'application appropriée pour ouvrir le fichier.

<br />


### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Obtient le texte descriptif (alternatif) associé au fichier joint.


**Returns:**
java.lang.String - Le texte descriptif (alternatif) associé au fichier joint.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Définit le texte descriptif (alternatif) associé au fichier joint.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | Le texte descriptif (alternatif) associé au fichier joint. |
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


Obtient le décalage horizontal du cadre de la pièce jointe par rapport à la bordure gauche de la feuille de calcul en points.


**Returns:**
double - La coordonnée x du cadre de la pièce jointe.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Définit le décalage horizontal du cadre de la pièce jointe par rapport à la bordure gauche de la feuille de calcul en points.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | double | La coordonnée x du cadre de la pièce jointe. |
|

### getY() {#getY--}
```
public final double getY()
```


Obtient le décalage vertical du cadre de la pièce jointe par rapport à la bordure supérieure de la feuille de calcul en points.


**Returns:**
double - La coordonnée y du cadre de la pièce jointe.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Définit le décalage vertical du cadre de la pièce jointe par rapport à la bordure supérieure de la feuille de calcul en points.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | double | La coordonnée y du cadre de la pièce jointe. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Obtient la largeur du cadre de la pièce jointe en points.


**Returns:**
double - La largeur du cadre de la pièce jointe en points.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Définit la largeur du cadre de la pièce jointe en points.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | double | La largeur du cadre de la pièce jointe en points. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Obtient la hauteur du cadre de la pièce jointe en points.


**Returns:**
double - La hauteur du cadre de la pièce jointe en points.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Définit la hauteur du cadre de la pièce jointe en points.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | double | La hauteur du cadre de la pièce jointe en points. |
|

### checkImageType() {#checkImageType--}
```
public final void checkImageType()
```


<br />



