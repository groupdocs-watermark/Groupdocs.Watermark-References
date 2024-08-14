---
title: SpreadsheetContent
second_title: GroupDocs.Watermark for Java API Reference
description: Represents an Excel document where a watermark can be placed.
type: docs
weight: 108
url: /java/com.groupdocs.watermark.contents/spreadsheetcontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content)

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IEncryptable](../../com.groupdocs.watermark.internal/iencryptable)
```
public class SpreadsheetContent extends Content implements IEncryptable
```

Represents an Excel document where a watermark can be placed.

**Learn more:**

 *  [Add watermarks to spreadsheet documents][]
 *  [Shapes in spreadsheet document][]
 *  [Working with spreadsheet document attachments][]
 *  [Working with worksheet backgrounds][]
 *  [Working with worksheet headers and footers][]

The following example demonstrates how to load and save Excel content of any supported type.

> ```
> ```
> 
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\input.xls", loadOptions);
>  
>    // Use add method to add watermark to a particular or all worksheets.
>  
>    // Save changes.
>    watermarker.save("D:\\output.xls");
>    watermarker.close();
>  
> ```
> ```


[Add watermarks to spreadsheet documents]: https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents
[Shapes in spreadsheet document]: https://docs.groupdocs.com/display/watermarkjava/Shapes+in+spreadsheet+document
[Working with spreadsheet document attachments]: https://docs.groupdocs.com/display/watermarkjava/Working+with+spreadsheet+document+attachments
[Working with worksheet backgrounds]: https://docs.groupdocs.com/display/watermarkjava/Working+with+worksheet+backgrounds
[Working with worksheet headers and footers]: https://docs.groupdocs.com/display/watermarkjava/Working+with+worksheet+headers+and+footers
## Constructors

| Constructor | Description |
| --- | --- |
| [SpreadsheetContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileFormatInfo fileFormatInfo, SpreadsheetLoadOptions spreadsheetLoadOptions, WatermarkerSettings watermarkerSettings)](#SpreadsheetContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.aspose.cells.FileFormatInfo-com.groupdocs.watermark.options.SpreadsheetLoadOptions-com.groupdocs.watermark.WatermarkerSettings-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getWorksheets()](#getWorksheets--) | Gets the collection of all worksheets of this `[SpreadsheetContent](../../com.groupdocs.watermark.contents/spreadsheetcontent)`. |
| [getAsposeCellsWorkbook()](#getAsposeCellsWorkbook--) |  |
| [addWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects)](#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-) |  |
| [addWatermarkAsBackground(Watermark watermark, int backgroundWidth, int backgroundHeight)](#addWatermarkAsBackground-com.groupdocs.watermark.Watermark-int-int-) |  |
| [addModernWordArtWatermark(TextWatermark watermark, SpreadsheetShapeSettings shapeSettings)](#addModernWordArtWatermark-com.groupdocs.watermark.watermarks.TextWatermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-) |  |
| [addWatermarkIntoHeaderFooter(Watermark watermark)](#addWatermarkIntoHeaderFooter-com.groupdocs.watermark.Watermark-) |  |
| [encrypt(String password)](#encrypt-java.lang.String-) | Encrypts the content. |
| [decrypt()](#decrypt--) | Decrypts the document. |
| [performSave(String filePath)](#performSave-java.lang.String-) |  |
| [performSave(String filePath, SaveOptions saveOptions)](#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-) |  |
| [performSave(OutputStream stream)](#performSave-java.io.OutputStream-) |  |
| [performSave(OutputStream stream, SaveOptions saveOptions)](#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-) |  |
| [getDocumentInfo()](#getDocumentInfo--) |  |
| [getFileType()](#getFileType--) |  |
| [add(Watermark watermark, WatermarkOptions options)](#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-) |  |
| [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.watermark.options.PreviewOptions-) |  |
### SpreadsheetContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileFormatInfo fileFormatInfo, SpreadsheetLoadOptions spreadsheetLoadOptions, WatermarkerSettings watermarkerSettings) {#SpreadsheetContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.aspose.cells.FileFormatInfo-com.groupdocs.watermark.options.SpreadsheetLoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public SpreadsheetContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileFormatInfo fileFormatInfo, SpreadsheetLoadOptions spreadsheetLoadOptions, WatermarkerSettings watermarkerSettings)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | [StreamContainer](../../com.groupdocs.watermark.internal/streamcontainer) |  |
| strategyManager | com.groupdocs.watermark.internal.StrategyManager<java.lang.Integer> |  |
| fileFormatInfo | com.aspose.cells.FileFormatInfo |  |
| spreadsheetLoadOptions | [SpreadsheetLoadOptions](../../com.groupdocs.watermark.options/spreadsheetloadoptions) |  |
| watermarkerSettings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) |  |

### getWorksheets() {#getWorksheets--}
```
public final SpreadsheetWorksheetCollection getWorksheets()
```


Gets the collection of all worksheets of this `[SpreadsheetContent](../../com.groupdocs.watermark.contents/spreadsheetcontent)`.

**Returns:**
[SpreadsheetWorksheetCollection](../../com.groupdocs.watermark.contents/spreadsheetworksheetcollection) - The collection of all worksheets of this `[SpreadsheetContent](../../com.groupdocs.watermark.contents/spreadsheetcontent)`.
### getAsposeCellsWorkbook() {#getAsposeCellsWorkbook--}
```
public final Workbook getAsposeCellsWorkbook()
```




**Returns:**
com.aspose.cells.Workbook
### addWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects) {#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-}
```
public final void addWatermark(Watermark watermark, SpreadsheetShapeSettings shapeSettings, ISpreadsheetWatermarkEffects effects)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| shapeSettings | [SpreadsheetShapeSettings](../../com.groupdocs.watermark.options/spreadsheetshapesettings) |  |
| effects | [ISpreadsheetWatermarkEffects](../../com.groupdocs.watermark.options/ispreadsheetwatermarkeffects) |  |

### addWatermarkAsBackground(Watermark watermark, int backgroundWidth, int backgroundHeight) {#addWatermarkAsBackground-com.groupdocs.watermark.Watermark-int-int-}
```
public final void addWatermarkAsBackground(Watermark watermark, int backgroundWidth, int backgroundHeight)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| backgroundWidth | int |  |
| backgroundHeight | int |  |

### addModernWordArtWatermark(TextWatermark watermark, SpreadsheetShapeSettings shapeSettings) {#addModernWordArtWatermark-com.groupdocs.watermark.watermarks.TextWatermark-com.groupdocs.watermark.options.SpreadsheetShapeSettings-}
```
public final void addModernWordArtWatermark(TextWatermark watermark, SpreadsheetShapeSettings shapeSettings)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| watermark | [TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark) |  |
| shapeSettings | [SpreadsheetShapeSettings](../../com.groupdocs.watermark.options/spreadsheetshapesettings) |  |

### addWatermarkIntoHeaderFooter(Watermark watermark) {#addWatermarkIntoHeaderFooter-com.groupdocs.watermark.Watermark-}
```
public final void addWatermarkIntoHeaderFooter(Watermark watermark)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### encrypt(String password) {#encrypt-java.lang.String-}
```
public final void encrypt(String password)
```


Encrypts the content.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | The password that will be required to open the document. |

### decrypt() {#decrypt--}
```
public final void decrypt()
```


Decrypts the document.

### performSave(String filePath) {#performSave-java.lang.String-}
```
public void performSave(String filePath)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String |  |

### performSave(String filePath, SaveOptions saveOptions) {#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(String filePath, SaveOptions saveOptions)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### performSave(OutputStream stream) {#performSave-java.io.OutputStream-}
```
public void performSave(OutputStream stream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream |  |

### performSave(OutputStream stream, SaveOptions saveOptions) {#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(OutputStream stream, SaveOptions saveOptions)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### getDocumentInfo() {#getDocumentInfo--}
```
public IDocumentInfo getDocumentInfo()
```




**Returns:**
[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo)
### getFileType() {#getFileType--}
```
public FileType getFileType()
```




**Returns:**
[FileType](../../com.groupdocs.watermark.common/filetype)
### add(Watermark watermark, WatermarkOptions options) {#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-}
```
public void add(Watermark watermark, WatermarkOptions options)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) |  |

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public void generatePreview(PreviewOptions previewOptions)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) |  |

