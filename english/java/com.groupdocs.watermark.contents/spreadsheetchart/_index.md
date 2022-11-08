---
title: SpreadsheetChart
second_title: GroupDocs.Watermark for Java API Reference
description: Represents a chart in an Excel document.
type: docs
weight: 106
url: /java/com.groupdocs.watermark.contents/spreadsheetchart/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IHyperlinkContainer](../../com.groupdocs.watermark.search/ihyperlinkcontainer), [com.groupdocs.watermark.search.ITwoDObject](../../com.groupdocs.watermark.search/itwodobject)
```
public class SpreadsheetChart implements IHyperlinkContainer, ITwoDObject
```

Represents a chart in an Excel document.
## Methods

| Method | Description |
| --- | --- |
| [getWorksheet()](#getWorksheet--) | Gets the parent worksheet of this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`. |
| [getId()](#getId--) | Gets the identifier of this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`. |
| [getImageFillFormat()](#getImageFillFormat--) | Gets the image fill format settings of this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`. |
| [getName()](#getName--) | Gets the name of this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`. |
| [getAlternativeText()](#getAlternativeText--) | Gets the descriptive (alternative) text associated with this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`. |
| [getHyperlink()](#getHyperlink--) | Gets the hyperlink associated with this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`. |
| [setHyperlink(String value)](#setHyperlink-java.lang.String-) | Sets the hyperlink associated with this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`. |
| [getX()](#getX--) | Gets the horizontal offset of this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` from worksheet left border in points. |
| [getY()](#getY--) | Gets the vertical offset of this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` from worksheet top border in points. |
| [getWidth()](#getWidth--) | Gets the width of this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` in points. |
| [getHeight()](#getHeight--) | Gets the height of this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` in points. |
### getWorksheet() {#getWorksheet--}
```
public final SpreadsheetWorksheet getWorksheet()
```


Gets the parent worksheet of this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`.

**Returns:**
[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) - The parent worksheet of this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`.
### getId() {#getId--}
```
public final int getId()
```


Gets the identifier of this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`.

**Returns:**
int - The identifier of this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`.
### getImageFillFormat() {#getImageFillFormat--}
```
public final SpreadsheetImageFillFormat getImageFillFormat()
```


Gets the image fill format settings of this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`.

**Returns:**
[SpreadsheetImageFillFormat](../../com.groupdocs.watermark.contents/spreadsheetimagefillformat) - The image fill format settings of this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`.
### getName() {#getName--}
```
public final String getName()
```


Gets the name of this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`.

**Returns:**
java.lang.String - The name of this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`.
### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Gets the descriptive (alternative) text associated with this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`.

**Returns:**
java.lang.String - The descriptive (alternative) text associated with this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`.
### getHyperlink() {#getHyperlink--}
```
public final String getHyperlink()
```


Gets the hyperlink associated with this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`.

**Returns:**
java.lang.String - The hyperlink associated with this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`.
### setHyperlink(String value) {#setHyperlink-java.lang.String-}
```
public final void setHyperlink(String value)
```


Sets the hyperlink associated with this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The hyperlink associated with this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`. |

### getX() {#getX--}
```
public final double getX()
```


Gets the horizontal offset of this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` from worksheet left border in points.

**Returns:**
double - The x-coordinate of this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`.
### getY() {#getY--}
```
public final double getY()
```


Gets the vertical offset of this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` from worksheet top border in points.

**Returns:**
double - The y-coordinate of this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)`.
### getWidth() {#getWidth--}
```
public final double getWidth()
```


Gets the width of this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` in points.

**Returns:**
double - The width of this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` in points.
### getHeight() {#getHeight--}
```
public final double getHeight()
```


Gets the height of this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` in points.

**Returns:**
double - The height of this `[SpreadsheetChart](../../com.groupdocs.watermark.contents/spreadsheetchart)` in points.
