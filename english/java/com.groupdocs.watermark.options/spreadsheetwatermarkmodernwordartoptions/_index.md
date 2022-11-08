---
title: SpreadsheetWatermarkModernWordArtOptions
second_title: GroupDocs.Watermark for Java API Reference
description: Represents options when adding modern word art watermark to a Spreadsheet worksheet.
type: docs
weight: 58
url: /java/com.groupdocs.watermark.options/spreadsheetwatermarkmodernwordartoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkBaseOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkbaseoptions)
```
public final class SpreadsheetWatermarkModernWordArtOptions extends SpreadsheetWatermarkBaseOptions
```

Represents options when adding modern word art watermark to a Spreadsheet worksheet.

**Learn more:**

 *  [Add watermarks to spreadsheet documents][]

The following example demonstrates how to add a modern WordArt watermark to an Excel document.

> ```
> ```
> 
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.xls", loadOptions);
> 
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
> 
>    SpreadsheetWatermarkModernWordArtOptions options = new SpreadsheetWatermarkModernWordArtOptions();
>    options.setWorksheetIndex(-1); // default
>    options.setLocked(false); // default
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
| [SpreadsheetWatermarkModernWordArtOptions()](#SpreadsheetWatermarkModernWordArtOptions--) | Initializes a new instance of the `[SpreadsheetWatermarkModernWordArtOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkmodernwordartoptions)` class. |
## Methods

| Method | Description |
| --- | --- |
| [getWorksheetIndex()](#getWorksheetIndex--) | Gets the index of worksheet to add the watermark to. |
| [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Sets the index of worksheet to add the watermark to. |
### SpreadsheetWatermarkModernWordArtOptions() {#SpreadsheetWatermarkModernWordArtOptions--}
```
public SpreadsheetWatermarkModernWordArtOptions()
```


Initializes a new instance of the `[SpreadsheetWatermarkModernWordArtOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkmodernwordartoptions)` class.

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

