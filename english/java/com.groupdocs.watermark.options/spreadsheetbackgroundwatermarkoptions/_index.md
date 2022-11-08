---
title: SpreadsheetBackgroundWatermarkOptions
second_title: GroupDocs.Watermark for Java API Reference
description: Represents options when adding the watermark as a background to a Spreadsheet worksheet.
type: docs
weight: 49
url: /java/com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions)
```
public final class SpreadsheetBackgroundWatermarkOptions extends SpreadsheetWatermarkOptions
```

Represents options when adding the watermark as a background to a Spreadsheet worksheet.

**Learn more:**

 *  [Add watermarks to spreadsheet documents][]

The following example demonstrates how to add a text watermark to an Excel document worksheet as background.

> ```
> ```
> 
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\Documents\\test.xlsx", loadOptions);
> 
>    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36));
> 
>    SpreadsheetBackgroundWatermarkOptions options = new SpreadsheetBackgroundWatermarkOptions();
>    options.setWorksheetIndex(-1); // default
>    options.setBackgroundWidth(800);
>    options.setBackgroundHeight(600);
>    
>    watermarker.save("C:\\Documents\\watermarked_test.xlsx");
>    watermarker.close();
>  
> ```
> ```


[Add watermarks to spreadsheet documents]: https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents
## Constructors

| Constructor | Description |
| --- | --- |
| [SpreadsheetBackgroundWatermarkOptions()](#SpreadsheetBackgroundWatermarkOptions--) | Initializes a new instance of the `[SpreadsheetBackgroundWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions)` class. |
## Methods

| Method | Description |
| --- | --- |
| [getWorksheetIndex()](#getWorksheetIndex--) | Get the index of worksheet to add the watermark to. |
| [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Sets the index of worksheet to add the watermark to. |
| [getBackgroundWidth()](#getBackgroundWidth--) | Get the desired width of the background image in pixels. |
| [setBackgroundWidth(int value)](#setBackgroundWidth-int-) | Sets the desired width of the background image in pixels. |
| [getBackgroundHeight()](#getBackgroundHeight--) | Gets or sets the desired height of the background image in pixels. |
| [setBackgroundHeight(int value)](#setBackgroundHeight-int-) | Gets or sets the desired height of the background image in pixels. |
### SpreadsheetBackgroundWatermarkOptions() {#SpreadsheetBackgroundWatermarkOptions--}
```
public SpreadsheetBackgroundWatermarkOptions()
```


Initializes a new instance of the `[SpreadsheetBackgroundWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions)` class.

### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


Get the index of worksheet to add the watermark to.

\-1 means every worksheet.

**Returns:**
int - The index of worksheet to add the watermark to.
### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Sets the index of worksheet to add the watermark to.

\-1 means every worksheet.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The index of worksheet to add the watermark to. |

### getBackgroundWidth() {#getBackgroundWidth--}
```
public final int getBackgroundWidth()
```


Get the desired width of the background image in pixels.

**Returns:**
int - The desired width of the background image in pixels.
### setBackgroundWidth(int value) {#setBackgroundWidth-int-}
```
public final void setBackgroundWidth(int value)
```


Sets the desired width of the background image in pixels.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The desired width of the background image in pixels. |

### getBackgroundHeight() {#getBackgroundHeight--}
```
public final int getBackgroundHeight()
```


Gets or sets the desired height of the background image in pixels.

**Returns:**
int - The desired height of the background image in pixels.
### setBackgroundHeight(int value) {#setBackgroundHeight-int-}
```
public final void setBackgroundHeight(int value)
```


Gets or sets the desired height of the background image in pixels.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The desired height of the background image in pixels. |

