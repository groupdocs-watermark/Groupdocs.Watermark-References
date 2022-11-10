---
title: SpreadsheetHyperlinkPossibleWatermark
second_title: GroupDocs.Watermark for Java API Reference
description: Represents possible hyperlink watermark in an Excel document.
type: docs
weight: 63
url: /java/com.groupdocs.watermark.search/spreadsheethyperlinkpossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark), [com.groupdocs.watermark.search.HyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/hyperlinkpossiblewatermark)
```
public class SpreadsheetHyperlinkPossibleWatermark extends HyperlinkPossibleWatermark
```

Represents possible hyperlink watermark in an Excel document.
## Constructors

| Constructor | Description |
| --- | --- |
| [SpreadsheetHyperlinkPossibleWatermark(SpreadsheetWorksheet worksheet, Hyperlink hyperlink)](#SpreadsheetHyperlinkPossibleWatermark-com.groupdocs.watermark.contents.SpreadsheetWorksheet-com.aspose.cells.Hyperlink-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getParent()](#getParent--) | Gets the parent of this `[SpreadsheetHyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheethyperlinkpossiblewatermark)`. |
| [getWidth()](#getWidth--) | Gets the width of this `[SpreadsheetHyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheethyperlinkpossiblewatermark)` in points. |
| [getHeight()](#getHeight--) | Gets the height of this `[SpreadsheetHyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheethyperlinkpossiblewatermark)` in points. |
| [getX()](#getX--) | Gets the horizontal offset of this `[SpreadsheetHyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheethyperlinkpossiblewatermark)` from worksheet left border in points. |
| [getY()](#getY--) | Gets the vertical offset of this `[SpreadsheetHyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheethyperlinkpossiblewatermark)` from worksheet top border in points. |
| [getRotateAngle()](#getRotateAngle--) | Gets the rotate angle of this `[SpreadsheetHyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheethyperlinkpossiblewatermark)` in degrees. |
| [getText()](#getText--) | Gets the url of this `[SpreadsheetHyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheethyperlinkpossiblewatermark)`. |
| [setText(String value)](#setText-java.lang.String-) | Sets the url of this `[SpreadsheetHyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheethyperlinkpossiblewatermark)`. |
| [getUnitOfMeasurement()](#getUnitOfMeasurement--) | Gets the `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` of this `[SpreadsheetHyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheethyperlinkpossiblewatermark)`. |
| [remove()](#remove--) |  |
### SpreadsheetHyperlinkPossibleWatermark(SpreadsheetWorksheet worksheet, Hyperlink hyperlink) {#SpreadsheetHyperlinkPossibleWatermark-com.groupdocs.watermark.contents.SpreadsheetWorksheet-com.aspose.cells.Hyperlink-}
```
public SpreadsheetHyperlinkPossibleWatermark(SpreadsheetWorksheet worksheet, Hyperlink hyperlink)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheet | [SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) |  |
| hyperlink | com.aspose.cells.Hyperlink |  |

### getParent() {#getParent--}
```
public ContentPart getParent()
```


Gets the parent of this `[SpreadsheetHyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheethyperlinkpossiblewatermark)`.

**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[SpreadsheetHyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheethyperlinkpossiblewatermark)`.
### getWidth() {#getWidth--}
```
public double getWidth()
```


Gets the width of this `[SpreadsheetHyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheethyperlinkpossiblewatermark)` in points.

**Returns:**
double - The width of this `[SpreadsheetHyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheethyperlinkpossiblewatermark)` in points.
### getHeight() {#getHeight--}
```
public double getHeight()
```


Gets the height of this `[SpreadsheetHyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheethyperlinkpossiblewatermark)` in points.

**Returns:**
double - The height of this `[SpreadsheetHyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheethyperlinkpossiblewatermark)` in points.
### getX() {#getX--}
```
public double getX()
```


Gets the horizontal offset of this `[SpreadsheetHyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheethyperlinkpossiblewatermark)` from worksheet left border in points.

**Returns:**
double - The x-coordinate of this `[SpreadsheetHyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheethyperlinkpossiblewatermark)`.
### getY() {#getY--}
```
public double getY()
```


Gets the vertical offset of this `[SpreadsheetHyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheethyperlinkpossiblewatermark)` from worksheet top border in points.

**Returns:**
double - The y-coordinate of this `[SpreadsheetHyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheethyperlinkpossiblewatermark)`.
### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Gets the rotate angle of this `[SpreadsheetHyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheethyperlinkpossiblewatermark)` in degrees.

**Returns:**
double - The value is always 0 for this type of possible watermark.
### getText() {#getText--}
```
public String getText()
```


Gets the url of this `[SpreadsheetHyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheethyperlinkpossiblewatermark)`.

**Returns:**
java.lang.String - The url of this `[SpreadsheetHyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheethyperlinkpossiblewatermark)`.
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Sets the url of this `[SpreadsheetHyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheethyperlinkpossiblewatermark)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The url of this `[SpreadsheetHyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheethyperlinkpossiblewatermark)`. |

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


Gets the `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` of this `[SpreadsheetHyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheethyperlinkpossiblewatermark)`.

**Returns:**
int - The `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` of this `[SpreadsheetHyperlinkPossibleWatermark](../../com.groupdocs.watermark.search/spreadsheethyperlinkpossiblewatermark)`.
### remove() {#remove--}
```
public void remove()
```




