---
title: "DiagramContent"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Bir Visio belgesini temsil eder."
type: docs
weight: 15
url: /tr/java/com.groupdocs.watermark.contents/diagramcontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content)
```
public final class DiagramContent extends Content
```

Bir Visio belgesini temsil eder.

**Learn more:**

* [Add watermarks to diagram documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+diagram+documents)
* [Existing objects in diagram document](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+diagram+document)

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [DiagramContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileFormatInfo formatInfo, DiagramLoadOptions diagramLoadOptions, WatermarkerSettings watermarkerSettings)](#DiagramContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.aspose.diagram.FileFormatInfo-com.groupdocs.watermark.options.DiagramLoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | <br /> |

|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPages()](#getPages--) | Bu `[DiagramContent](../../com.groupdocs.watermark.contents/diagramcontent)` öğesinin tüm sayfalarının koleksiyonunu alır. |
|
|  | [getHeaderFooter()](#getHeaderFooter--) | Bu `[DiagramContent](../../com.groupdocs.watermark.contents/diagramcontent)` öğesinin üstbilgi ve altbilgisini alır. |
|
|  | [getAsposeDiagram()](#getAsposeDiagram--) | <br /> |

|
|  | [addWatermark(Watermark watermark, int watermarkPlacementType, DiagramShapeSettings shapeSettings)](#addWatermark-com.groupdocs.watermark.Watermark-int-com.groupdocs.watermark.internal.DiagramShapeSettings-) | <br /> |

|
|  | [performSave(String filePath)](#performSave-java.lang.String-) | <br /> |

|
|  | [performSave(String filePath, SaveOptions saveOptions)](#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-) | <br /> |

|
|  | [performSave(OutputStream stream)](#performSave-java.io.OutputStream-) | <br /> |

|
|  | [performSave(OutputStream stream, SaveOptions saveOptions)](#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-) | <br /> |

|
|  | [add(Watermark watermark, WatermarkOptions options)](#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-) | <br /> |

|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.watermark.options.PreviewOptions-) | <br /> |

|
|  | [afterWatermarkAdding()](#afterWatermarkAdding--) | <br /> |

|
|  | [getDocumentInfo()](#getDocumentInfo--) | <br /> |

|
|  | [getFileType()](#getFileType--) | <br /> |

|
|  | [getFontIdByName(String fontName)](#getFontIdByName-java.lang.String-) | <br /> |

|
|  | [addFont(String fontName)](#addFont-java.lang.String-) | <br /> |

|
|  | [isNewFormat()](#isNewFormat--) | <br /> |

|
### DiagramContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileFormatInfo formatInfo, DiagramLoadOptions diagramLoadOptions, WatermarkerSettings watermarkerSettings) {#DiagramContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.aspose.diagram.FileFormatInfo-com.groupdocs.watermark.options.DiagramLoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public DiagramContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileFormatInfo formatInfo, DiagramLoadOptions diagramLoadOptions, WatermarkerSettings watermarkerSettings)
```


<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [StreamContainer](../../com.groupdocs.watermark.internal/streamcontainer) |  |
| strategyManager | com.groupdocs.watermark.internal.StrategyManager<java.lang.Integer> |  |
| formatInfo | com.aspose.diagram.FileFormatInfo |  |
| diagramLoadOptions | [DiagramLoadOptions](../../com.groupdocs.watermark.options/diagramloadoptions) |  |
| watermarkerSettings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) |  |

### getPages() {#getPages--}
```
public final DiagramPageCollection getPages()
```


Bu `[DiagramContent](../../com.groupdocs.watermark.contents/diagramcontent)` öğesinin tüm sayfalarının koleksiyonunu alır.


**Returns:**
[DiagramPageCollection](../../com.groupdocs.watermark.contents/diagrampagecollection) - The collection of all pages of this `[DiagramContent](../../com.groupdocs.watermark.contents/diagramcontent).`

### getHeaderFooter() {#getHeaderFooter--}
```
public final DiagramHeaderFooter getHeaderFooter()
```


Bu `[DiagramContent](../../com.groupdocs.watermark.contents/diagramcontent)` öğesinin üstbilgi ve altbilgisini alır.


**Returns:**
[DiagramHeaderFooter](../../com.groupdocs.watermark.contents/diagramheaderfooter) - The header and footer of this `[DiagramContent](../../com.groupdocs.watermark.contents/diagramcontent).`

### getAsposeDiagram() {#getAsposeDiagram--}
```
public final Diagram getAsposeDiagram()
```


<br />



**Returns:**
com.aspose.diagram.Diagram
### addWatermark(Watermark watermark, int watermarkPlacementType, DiagramShapeSettings shapeSettings) {#addWatermark-com.groupdocs.watermark.Watermark-int-com.groupdocs.watermark.internal.DiagramShapeSettings-}
```
public final void addWatermark(Watermark watermark, int watermarkPlacementType, DiagramShapeSettings shapeSettings)
```


<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| watermarkPlacementType | int |  |
| shapeSettings | [DiagramShapeSettings](../../com.groupdocs.watermark.internal/diagramshapesettings) |  |

### performSave(String filePath) {#performSave-java.lang.String-}
```
public void performSave(String filePath)
```


<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String |  |

### performSave(String filePath, SaveOptions saveOptions) {#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(String filePath, SaveOptions saveOptions)
```


<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### performSave(OutputStream stream) {#performSave-java.io.OutputStream-}
```
public void performSave(OutputStream stream)
```


<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream |  |

### performSave(OutputStream stream, SaveOptions saveOptions) {#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(OutputStream stream, SaveOptions saveOptions)
```


<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### add(Watermark watermark, WatermarkOptions options) {#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-}
```
public void add(Watermark watermark, WatermarkOptions options)
```


<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) |  |

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public void generatePreview(PreviewOptions previewOptions)
```


<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) |  |

### afterWatermarkAdding() {#afterWatermarkAdding--}
```
public void afterWatermarkAdding()
```


<br />



### getDocumentInfo() {#getDocumentInfo--}
```
public IDocumentInfo getDocumentInfo()
```


<br />



**Returns:**
[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo)
### getFileType() {#getFileType--}
```
public FileType getFileType()
```


<br />



**Returns:**
[FileType](../../com.groupdocs.watermark.common/filetype)
### getFontIdByName(String fontName) {#getFontIdByName-java.lang.String-}
```
public final int getFontIdByName(String fontName)
```


<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | java.lang.String |  |

**Returns:**
int
### addFont(String fontName) {#addFont-java.lang.String-}
```
public final int addFont(String fontName)
```


<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | java.lang.String |  |

**Returns:**
int
### isNewFormat() {#isNewFormat--}
```
public final boolean isNewFormat()
```


<br />



**Returns:**
boolean
