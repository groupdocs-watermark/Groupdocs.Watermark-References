---
title: DiagramHeaderFooterPossibleWatermark
second_title: GroupDocs.Watermark for Java API Reference
description: Represents possible watermark in a Visio document header/footer.
type: docs
weight: 14
url: /java/com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)
```
public class DiagramHeaderFooterPossibleWatermark extends PossibleWatermark
```

Represents possible watermark in a Visio document header/footer.
## Constructors

| Constructor | Description |
| --- | --- |
| [DiagramHeaderFooterPossibleWatermark(DiagramContent content, int headerFooterType)](#DiagramHeaderFooterPossibleWatermark-com.groupdocs.watermark.contents.DiagramContent-int-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getParent()](#getParent--) | Gets the parent of this `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)`. |
| [getWidth()](#getWidth--) | Gets the width of this `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` in points. |
| [getHeight()](#getHeight--) | Gets the height of this `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` in points. |
| [getX()](#getX--) | Gets the horizontal offset of this `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` from page left border in points. |
| [getY()](#getY--) | Gets the vertical offset of this `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` from page bottom border in points. |
| [getRotateAngle()](#getRotateAngle--) | Gets the rotate angle of this `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` in degrees. |
| [getText()](#getText--) | Gets the text of this `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)`. |
| [setText(String value)](#setText-java.lang.String-) | Sets the text of this `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)`. |
| [getUnitOfMeasurement()](#getUnitOfMeasurement--) | Gets the `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` of this `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)`. |
| [remove()](#remove--) |  |
### DiagramHeaderFooterPossibleWatermark(DiagramContent content, int headerFooterType) {#DiagramHeaderFooterPossibleWatermark-com.groupdocs.watermark.contents.DiagramContent-int-}
```
public DiagramHeaderFooterPossibleWatermark(DiagramContent content, int headerFooterType)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | [DiagramContent](../../com.groupdocs.watermark.contents/diagramcontent) |  |
| headerFooterType | int |  |

### getParent() {#getParent--}
```
public ContentPart getParent()
```


Gets the parent of this `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)`.

**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)`.
### getWidth() {#getWidth--}
```
public double getWidth()
```


Gets the width of this `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` in points.

**Returns:**
double - The value is always 0 for this type of possible watermark.
### getHeight() {#getHeight--}
```
public double getHeight()
```


Gets the height of this `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` in points.

**Returns:**
double - The value is always 0 for this type of possible watermark.
### getX() {#getX--}
```
public double getX()
```


Gets the horizontal offset of this `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` from page left border in points.

**Returns:**
double - The value is always 0 for this type of possible watermark.
### getY() {#getY--}
```
public double getY()
```


Gets the vertical offset of this `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` from page bottom border in points.

**Returns:**
double - The value is always 0 for this type of possible watermark.
### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Gets the rotate angle of this `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)` in degrees.

**Returns:**
double - The value is always 0 for this type of possible watermark.
### getText() {#getText--}
```
public String getText()
```


Gets the text of this `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)`.

**Returns:**
java.lang.String - The text of this `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)`.
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Sets the text of this `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The text of this `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)`. |

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


Gets the `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` of this `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)`.

**Returns:**
int - The `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` of this `[DiagramHeaderFooterPossibleWatermark](../../com.groupdocs.watermark.search/diagramheaderfooterpossiblewatermark)`.
### remove() {#remove--}
```
public void remove()
```




