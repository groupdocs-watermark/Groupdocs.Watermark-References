---
title: SpreadsheetWatermarkHeaderFooterOptions
second_title: GroupDocs.Watermark for Java API Reference
description: Represents options when adding the watermark to a Spreadsheet header/footer.
type: docs
weight: 57
url: /java/com.groupdocs.watermark.options/spreadsheetwatermarkheaderfooteroptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions)
```
public final class SpreadsheetWatermarkHeaderFooterOptions extends SpreadsheetWatermarkOptions
```

Represents options when adding the watermark to a Spreadsheet header/footer.

**Learn more:**

 *  [Add watermarks to spreadsheet documents][]

The following example demonstrates how to add a text watermark into Excel worksheet header.

> ```
> ```
> 
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.xls", loadOptions);
> 
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
> 
>    SpreadsheetWatermarkHeaderFooterOptions options = new SpreadsheetWatermarkHeaderFooterOptions();
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
| [SpreadsheetWatermarkHeaderFooterOptions()](#SpreadsheetWatermarkHeaderFooterOptions--) | Initializes a new instance of the `[SpreadsheetWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkheaderfooteroptions)` class. |
## Methods

| Method | Description |
| --- | --- |
| [getWorksheetIndex()](#getWorksheetIndex--) | Gets the index of worksheet to add the watermark to. |
| [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Sets the index of worksheet to add the watermark to. |
### SpreadsheetWatermarkHeaderFooterOptions() {#SpreadsheetWatermarkHeaderFooterOptions--}
```
public SpreadsheetWatermarkHeaderFooterOptions()
```


Initializes a new instance of the `[SpreadsheetWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkheaderfooteroptions)` class.

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

