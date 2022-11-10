---
title: DiagramContent
second_title: GroupDocs.Watermark for Java API Reference
description: Represents a Visio document.
type: docs
weight: 15
url: /java/com.groupdocs.watermark.contents/diagramcontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content)
```
public final class DiagramContent extends Content
```

Represents a Visio document.

**Learn more:**

 *  [Add watermarks to diagram documents][]
 *  [Existing objects in diagram document][]


[Add watermarks to diagram documents]: https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+diagram+documents
[Existing objects in diagram document]: https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+diagram+document
## Constructors

| Constructor | Description |
| --- | --- |
| [DiagramContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileFormatInfo formatInfo, DiagramLoadOptions diagramLoadOptions, WatermarkerSettings watermarkerSettings)](#DiagramContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.aspose.diagram.FileFormatInfo-com.groupdocs.watermark.options.DiagramLoadOptions-com.groupdocs.watermark.WatermarkerSettings-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getPages()](#getPages--) | Gets the collection of all pages of this `[DiagramContent](../../com.groupdocs.watermark.contents/diagramcontent)`. |
| [getHeaderFooter()](#getHeaderFooter--) | Gets the header and footer of this `[DiagramContent](../../com.groupdocs.watermark.contents/diagramcontent)`. |
| [getAsposeDiagram()](#getAsposeDiagram--) |  |
| [addWatermark(Watermark watermark, int watermarkPlacementType, DiagramShapeSettings shapeSettings)](#addWatermark-com.groupdocs.watermark.Watermark-int-com.groupdocs.watermark.internal.DiagramShapeSettings-) |  |
| [performSave(String filePath)](#performSave-java.lang.String-) |  |
| [performSave(String filePath, SaveOptions saveOptions)](#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-) |  |
| [performSave(OutputStream stream)](#performSave-java.io.OutputStream-) |  |
| [performSave(OutputStream stream, SaveOptions saveOptions)](#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-) |  |
| [add(Watermark watermark, WatermarkOptions options)](#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-) |  |
| [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.watermark.options.PreviewOptions-) |  |
| [afterWatermarkAdding()](#afterWatermarkAdding--) |  |
| [getDocumentInfo()](#getDocumentInfo--) |  |
| [getFileType()](#getFileType--) |  |
| [getFontIdByName(String fontName)](#getFontIdByName-java.lang.String-) |  |
| [addFont(String fontName)](#addFont-java.lang.String-) |  |
| [isNewFormat()](#isNewFormat--) |  |
### DiagramContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileFormatInfo formatInfo, DiagramLoadOptions diagramLoadOptions, WatermarkerSettings watermarkerSettings) {#DiagramContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.aspose.diagram.FileFormatInfo-com.groupdocs.watermark.options.DiagramLoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public DiagramContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileFormatInfo formatInfo, DiagramLoadOptions diagramLoadOptions, WatermarkerSettings watermarkerSettings)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.groupdocs.watermark.internal.StreamContainer |  |
| strategyManager | com.groupdocs.watermark.internal.StrategyManager<java.lang.Integer> |  |
| formatInfo | com.aspose.diagram.FileFormatInfo |  |
| diagramLoadOptions | [DiagramLoadOptions](../../com.groupdocs.watermark.options/diagramloadoptions) |  |
| watermarkerSettings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) |  |

### getPages() {#getPages--}
```
public final DiagramPageCollection getPages()
```


Gets the collection of all pages of this `[DiagramContent](../../com.groupdocs.watermark.contents/diagramcontent)`.

**Returns:**
[DiagramPageCollection](../../com.groupdocs.watermark.contents/diagrampagecollection) - The collection of all pages of this `[DiagramContent](../../com.groupdocs.watermark.contents/diagramcontent).`
### getHeaderFooter() {#getHeaderFooter--}
```
public final DiagramHeaderFooter getHeaderFooter()
```


Gets the header and footer of this `[DiagramContent](../../com.groupdocs.watermark.contents/diagramcontent)`.

**Returns:**
[DiagramHeaderFooter](../../com.groupdocs.watermark.contents/diagramheaderfooter) - The header and footer of this `[DiagramContent](../../com.groupdocs.watermark.contents/diagramcontent).`
### getAsposeDiagram() {#getAsposeDiagram--}
```
public final Diagram getAsposeDiagram()
```




**Returns:**
com.aspose.diagram.Diagram
### addWatermark(Watermark watermark, int watermarkPlacementType, DiagramShapeSettings shapeSettings) {#addWatermark-com.groupdocs.watermark.Watermark-int-com.groupdocs.watermark.internal.DiagramShapeSettings-}
```
public final void addWatermark(Watermark watermark, int watermarkPlacementType, DiagramShapeSettings shapeSettings)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| watermarkPlacementType | int |  |
| shapeSettings | com.groupdocs.watermark.internal.DiagramShapeSettings |  |

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

### afterWatermarkAdding() {#afterWatermarkAdding--}
```
public void afterWatermarkAdding()
```




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
### getFontIdByName(String fontName) {#getFontIdByName-java.lang.String-}
```
public final int getFontIdByName(String fontName)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String |  |

**Returns:**
int
### addFont(String fontName) {#addFont-java.lang.String-}
```
public final int addFont(String fontName)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String |  |

**Returns:**
int
### isNewFormat() {#isNewFormat--}
```
public final boolean isNewFormat()
```




**Returns:**
boolean
