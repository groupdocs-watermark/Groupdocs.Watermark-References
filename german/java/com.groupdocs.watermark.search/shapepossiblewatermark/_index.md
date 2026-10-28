---
title: "ShapePossibleWatermark"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt ein Form‑Wasserzeichen in einem Inhalt eines beliebigen unterstützten Formats dar."
type: docs
weight: 55
url: /de/java/com.groupdocs.watermark.search/shapepossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark), [com.groupdocs.watermark.search.TwoDObjectPossibleWatermark](../../com.groupdocs.watermark.search/twodobjectpossiblewatermark)
```
public abstract class ShapePossibleWatermark<T> extends TwoDObjectPossibleWatermark
```

Stellt ein Form‑Wasserzeichen in einem Inhalt eines beliebigen unterstützten Formats dar.


T
: Der Typ der Form.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getRotateAngle()](#getRotateAngle--) | Gibt den Rotationswinkel der Form in Grad zurück. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Gibt die Sammlung formatierter Textfragmente der Form zurück. |
|
|  | [getText()](#getText--) | Gibt den Text der Form zurück. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Setzt den Text der Form. |
|
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Gibt den Rotationswinkel der Form in Grad zurück.


**Returns:**
double - Der Rotationswinkel der Form in Grad.

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public FormattedTextFragmentCollection getFormattedTextFragments()
```


Gibt die Sammlung formatierter Textfragmente der Form zurück.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of shape.

### getText() {#getText--}
```
public String getText()
```


Gibt den Text der Form zurück.


**Returns:**
java.lang.String - Der Text der Form.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Setzt den Text der Form.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.String | Der Text der Form. |
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




