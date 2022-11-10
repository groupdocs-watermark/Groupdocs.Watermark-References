---
title: SpreadsheetWatermarkShapeOptions
second_title: GroupDocs.Watermark for Java API Reference
description: Represents options when adding shape watermark to a Spreadsheet worksheet.
type: docs
weight: 60
url: /java/com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkBaseOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkbaseoptions)
```
public final class SpreadsheetWatermarkShapeOptions extends SpreadsheetWatermarkBaseOptions
```

Represents options when adding shape watermark to a Spreadsheet worksheet.

**Learn more:**

 *  [Add watermarks to spreadsheet documents][]

The following example demonstrates how to add a watermark to a particular worksheet of an Excel document.

> ```
> ```
> 
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.xls", loadOptions);
> 
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
> 
>    SpreadsheetWatermarkShapeOptions options = new SpreadsheetWatermarkShapeOptions();
>    options.setWorksheetIndex(0);
>    
>    watermarker.save("D:\\watermarked_test.xlsx");
>    watermarker.close();
>  
> ```
> ```


[Add watermarks to spreadsheet documents]: https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents
## Constructors

| Constructor | Description |
| --- | --- |
| [SpreadsheetWatermarkShapeOptions()](#SpreadsheetWatermarkShapeOptions--) | Initializes a new instance of the `[SpreadsheetWatermarkShapeOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions)` class. |
## Methods

| Method | Description |
| --- | --- |
| [getWorksheetIndex()](#getWorksheetIndex--) | Gets the index of worksheet to add the watermark to. |
| [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Sets the index of worksheet to add the watermark to. |
| [getEffects()](#getEffects--) | Gets a value of `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` or `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` for effects that should be applied to the watermark. |
| [setEffects(ISpreadsheetWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-) | Gets or sets a value of `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` or `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` for effects that should be applied to the watermark. |
### SpreadsheetWatermarkShapeOptions() {#SpreadsheetWatermarkShapeOptions--}
```
public SpreadsheetWatermarkShapeOptions()
```


Initializes a new instance of the `[SpreadsheetWatermarkShapeOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions)` class.

### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


Gets the index of worksheet to add the watermark to.

**Returns:**
int - The index of worksheet to add the watermark to.

--------------------

\-1 means every worksheet.
### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Sets the index of worksheet to add the watermark to.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The index of worksheet to add the watermark to.

--------------------

\-1 means every worksheet. |

### getEffects() {#getEffects--}
```
public final ISpreadsheetWatermarkEffects getEffects()
```


Gets a value of `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` or `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` for effects that should be applied to the watermark.

**Returns:**
[ISpreadsheetWatermarkEffects](../../com.groupdocs.watermark.options/ispreadsheetwatermarkeffects) - The `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` or `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` for effects that should be applied to the watermark.
### setEffects(ISpreadsheetWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-}
```
public final void setEffects(ISpreadsheetWatermarkEffects value)
```


Gets or sets a value of `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` or `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` for effects that should be applied to the watermark.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISpreadsheetWatermarkEffects](../../com.groupdocs.watermark.options/ispreadsheetwatermarkeffects) | The `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` or `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` for effects that should be applied to the watermark. |

