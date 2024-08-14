---
title: PossibleWatermark
second_title: GroupDocs.Watermark for Java API Reference
description: Represents possible watermark found in a document.
type: docs
weight: 45
url: /java/com.groupdocs.watermark.search/possiblewatermark/
---
**Inheritance:**
java.lang.Object
```
public abstract class PossibleWatermark
```

Represents possible watermark found in a document.
## Constructors

| Constructor | Description |
| --- | --- |
| [PossibleWatermark()](#PossibleWatermark--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getParent()](#getParent--) | Gets the parent of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
| [getWidth()](#getWidth--) | Gets the width of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
| [getHeight()](#getHeight--) | Gets the height of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
| [getX()](#getX--) | Gets the x-coordinate of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
| [getY()](#getY--) | Gets the y-coordinate of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
| [getRotateAngle()](#getRotateAngle--) | Gets the rotate angle of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` in degrees. |
| [getText()](#getText--) | Gets the text of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
| [setText(String value)](#setText-java.lang.String-) | Sets the text of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
| [getFormattedTextFragments()](#getFormattedTextFragments--) | Gets the collection of formatted text fragments of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
| [getImageData()](#getImageData--) | Gets or sets the image of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
| [setImageData(byte[] value)](#setImageData-byte---) |  |
| [getUnitOfMeasurement()](#getUnitOfMeasurement--) | Gets the unit of measurement `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |
| [getCollection()](#getCollection--) |  |
| [setCollection(PossibleWatermarkCollection value)](#setCollection-com.groupdocs.watermark.search.PossibleWatermarkCollection-) |  |
| [getImageSize()](#getImageSize--) |  |
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### PossibleWatermark() {#PossibleWatermark--}
```
public PossibleWatermark()
```




### getParent() {#getParent--}
```
public abstract ContentPart getParent()
```


Gets the parent of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.
### getWidth() {#getWidth--}
```
public double getWidth()
```


Gets the width of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

**Returns:**
double - The width of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.
### getHeight() {#getHeight--}
```
public double getHeight()
```


Gets the height of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

**Returns:**
double - The height of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.
### getX() {#getX--}
```
public double getX()
```


Gets the x-coordinate of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

**Returns:**
double - The x-coordinate of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.
### getY() {#getY--}
```
public double getY()
```


Gets the y-coordinate of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

**Returns:**
double - The y-coordinate of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.
### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Gets the rotate angle of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` in degrees.

**Returns:**
double - The rotate angle of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.
### getText() {#getText--}
```
public String getText()
```


Gets the text of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

**Returns:**
java.lang.String - The text of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Sets the text of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The text of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`. |

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public FormattedTextFragmentCollection getFormattedTextFragments()
```


Gets the collection of formatted text fragments of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.
### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Gets or sets the image of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

**Returns:**
byte[] - The image of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)` or null if the watermark has no image.
### setImageData(byte[] value) {#setImageData-byte---}
```
public final void setImageData(byte[] value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


Gets the unit of measurement `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.

**Returns:**
int - The unit of measurement `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` of this `[PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)`.
### getCollection() {#getCollection--}
```
public final PossibleWatermarkCollection getCollection()
```




**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection)
### setCollection(PossibleWatermarkCollection value) {#setCollection-com.groupdocs.watermark.search.PossibleWatermarkCollection-}
```
public final void setCollection(PossibleWatermarkCollection value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection) |  |

### getImageSize() {#getImageSize--}
```
public final Size getImageSize()
```




**Returns:**
[Size](../../com.groupdocs.watermark.internal/size)
### getImageInternally() {#getImageInternally--}
```
public WatermarkableImage getImageInternally()
```




**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### remove() {#remove--}
```
public abstract void remove()
```




