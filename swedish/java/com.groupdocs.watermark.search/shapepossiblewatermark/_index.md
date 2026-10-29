---
title: "ShapePossibleWatermark"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar formvattenstämpel i ett innehåll av vilket som helst stödformat."
type: docs
weight: 55
url: /sv/java/com.groupdocs.watermark.search/shapepossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark), [com.groupdocs.watermark.search.TwoDObjectPossibleWatermark](../../com.groupdocs.watermark.search/twodobjectpossiblewatermark)
```
public abstract class ShapePossibleWatermark<T> extends TwoDObjectPossibleWatermark
```

Representerar formvattenstämpel i ett innehåll av vilket som helst stödformat.


T
: Typen av formen.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getRotateAngle()](#getRotateAngle--) | Hämtar rotationsvinkeln för formen i grader. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Hämtar samlingen av formaterade textfragment för formen. |
|
|  | [getText()](#getText--) | Hämtar texten för formen. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Ställer in texten för formen. |
|
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Hämtar rotationsvinkeln för formen i grader.


**Returns:**
double - Rotationsvinkeln för formen i grader.

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public FormattedTextFragmentCollection getFormattedTextFragments()
```


Hämtar samlingen av formaterade textfragment för formen.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of shape.

### getText() {#getText--}
```
public String getText()
```


Hämtar texten för formen.


**Returns:**
java.lang.String - Texten för formen.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Ställer in texten för formen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.lang.String | Texten för formen. |
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




