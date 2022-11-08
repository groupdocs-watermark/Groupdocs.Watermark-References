---
title: ShapePossibleWatermark
second_title: GroupDocs.Watermark for Java API Reference
description: Represents shape watermark in a content of any supported format.
type: docs
weight: 55
url: /java/com.groupdocs.watermark.search/shapepossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark), [com.groupdocs.watermark.search.TwoDObjectPossibleWatermark](../../com.groupdocs.watermark.search/twodobjectpossiblewatermark)
```
public abstract class ShapePossibleWatermark<T> extends TwoDObjectPossibleWatermark
```

Represents shape watermark in a content of any supported format.

 T : The type of the shape.
## Methods

| Method | Description |
| --- | --- |
| [getRotateAngle()](#getRotateAngle--) | Gets the rotate angle of the shape in degrees. |
| [getFormattedTextFragments()](#getFormattedTextFragments--) | Gets the collection of formatted text fragments of the shape. |
| [getText()](#getText--) | Gets the text of the shape. |
| [setText(String value)](#setText-java.lang.String-) | Sets the text of the shape. |
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Gets the rotate angle of the shape in degrees.

**Returns:**
double - The rotate angle of the shape in degrees.
### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public FormattedTextFragmentCollection getFormattedTextFragments()
```


Gets the collection of formatted text fragments of the shape.

**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of shape.
### getText() {#getText--}
```
public String getText()
```


Gets the text of the shape.

**Returns:**
java.lang.String - The text of the shape.
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Sets the text of the shape.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The text of the shape. |

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




