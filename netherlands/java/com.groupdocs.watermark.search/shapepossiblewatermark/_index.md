---
title: "ShapePossibleWatermark"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Geeft een vormwatermerk weer in de inhoud van elk ondersteund formaat."
type: docs
weight: 55
url: /nl/java/com.groupdocs.watermark.search/shapepossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark), [com.groupdocs.watermark.search.TwoDObjectPossibleWatermark](../../com.groupdocs.watermark.search/twodobjectpossiblewatermark)
```
public abstract class ShapePossibleWatermark<T> extends TwoDObjectPossibleWatermark
```

Geeft een vormwatermerk weer in de inhoud van elk ondersteund formaat.


T
: Het type van de vorm.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getRotateAngle()](#getRotateAngle--) | Haalt de rotatiehoek van de vorm op in graden. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Haalt de collectie van opgemaakte tekstfragmenten van de vorm op. |
|
|  | [getText()](#getText--) | Haalt de tekst van de vorm op. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Stelt de tekst van de vorm in. |
|
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Haalt de rotatiehoek van de vorm op in graden.


**Returns:**
double - De rotatiehoek van de vorm in graden.

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public FormattedTextFragmentCollection getFormattedTextFragments()
```


Haalt de collectie van opgemaakte tekstfragmenten van de vorm op.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of shape.

### getText() {#getText--}
```
public String getText()
```


Haalt de tekst van de vorm op.


**Returns:**
java.lang.String - De tekst van de vorm.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Stelt de tekst van de vorm in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | De tekst van de vorm. |
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




