---
title: "ShapePossibleWatermark"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente un filigrane de forme dans un contenu de tout format pris en charge."
type: docs
weight: 55
url: /fr/java/com.groupdocs.watermark.search/shapepossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark), [com.groupdocs.watermark.search.TwoDObjectPossibleWatermark](../../com.groupdocs.watermark.search/twodobjectpossiblewatermark)
```
public abstract class ShapePossibleWatermark<T> extends TwoDObjectPossibleWatermark
```

Représente un filigrane de forme dans un contenu de tout format pris en charge.


T
: Le type de la forme.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getRotateAngle()](#getRotateAngle--) | Obtient l'angle de rotation de la forme en degrés. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Obtient la collection de fragments de texte formatés de la forme. |
|
|  | [getText()](#getText--) | Obtient le texte de la forme. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Définit le texte de la forme. |
|
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Obtient l'angle de rotation de la forme en degrés.


**Returns:**
double - L'angle de rotation de la forme en degrés.

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public FormattedTextFragmentCollection getFormattedTextFragments()
```


Obtient la collection de fragments de texte formatés de la forme.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of shape.

### getText() {#getText--}
```
public String getText()
```


Obtient le texte de la forme.


**Returns:**
java.lang.String - Le texte de la forme.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Définit le texte de la forme.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | Le texte de la forme. |
|

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




