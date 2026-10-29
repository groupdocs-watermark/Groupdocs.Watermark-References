---
title: "PdfContent"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar ett pdf-dokument där ett vattenmärke kan placeras."
type: docs
weight: 60
url: /sv/java/com.groupdocs.watermark.contents/pdfcontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content)

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IEncryptable](../../com.groupdocs.watermark.internal/iencryptable)
```
public class PdfContent extends Content implements IEncryptable
```

Representerar ett pdf-dokument där ett vattenmärke kan placeras.

**Learn more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)
* [Existing objects in PDF document](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document)
* [Rasterize document or page](../https://docs.groupdocs.com/display/watermarkjava/Rasterize+document+or+page)
* [Watermarks in PDF document](../https://docs.groupdocs.com/display/watermarkjava/Watermarks+in+PDF+document)

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [PdfContent(StreamContainer stream, StrategyManager<Integer> strategyManager, PdfLoadOptions pdfLoadOptions, WatermarkerSettings watermarkerSettings)](#PdfContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.groupdocs.watermark.options.PdfLoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | <br /> |

|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getPages()](#getPages--) | Hämtar samlingen av alla sidor för detta `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`. |
|
|  | [getAttachments()](#getAttachments--) | Hämtar samlingen av alla bilagor för detta `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`. |
|
|  | [getPageMarginType()](#getPageMarginType--) | Hämtar PDF-sidmarginaler som ska användas vid vattenmärkning. |
|
|  | [setPageMarginType(int value)](#setPageMarginType-int-) | Ställer in PDF-sidmarginaler som ska användas vid vattenmärkning. |
|
|  | [getAsposePdfDocument()](#getAsposePdfDocument--) | <br /> |

|
|  | [addArtifactWatermark(Watermark watermark)](#addArtifactWatermark-com.groupdocs.watermark.Watermark-) | <br /> |

|
|  | [addAnnotationWatermark(Watermark watermark, boolean isPrintOnly)](#addAnnotationWatermark-com.groupdocs.watermark.Watermark-boolean-) | <br /> |

|
|  | [getDocumentInfo()](#getDocumentInfo--) | <br /> |

|
|  | [getFileType()](#getFileType--) | <br /> |

|
|  | [encrypt(String password)](#encrypt-java.lang.String-) | Krypterar dokumentet med samma lösenord som användarlösenord och ägarlösenord. |
|
|  | [encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm)](#encrypt-java.lang.String-java.lang.String-int-int-) | Krypterar innehållet. |
|
|  | [decrypt()](#decrypt--) | Dekrypterar innehållet. |
|
|  | [rasterize(int horizontalResolution, int verticalResolution, int imageFormat)](#rasterize-int-int-int-) | Konverterar alla innehållssidor till bilder. |
|
|  | [performSave(String filePath)](#performSave-java.lang.String-) | <br /> |

|
|  | [performSave(String filePath, SaveOptions saveOptions)](#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-) | <br /> |

|
|  | [performSave(OutputStream stream)](#performSave-java.io.OutputStream-) | Sparar dokumentdata till den angivna strömmen. |
|
|  | [performSave(OutputStream stream, SaveOptions saveOptions)](#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-) | Sparar dokumentdata till den angivna strömmen. |
|
|  | [add(Watermark watermark, WatermarkOptions options)](#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-) | <br /> |

|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.watermark.options.PreviewOptions-) | <br /> |

|
### PdfContent(StreamContainer stream, StrategyManager<Integer> strategyManager, PdfLoadOptions pdfLoadOptions, WatermarkerSettings watermarkerSettings) {#PdfContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.groupdocs.watermark.options.PdfLoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public PdfContent(StreamContainer stream, StrategyManager<Integer> strategyManager, PdfLoadOptions pdfLoadOptions, WatermarkerSettings watermarkerSettings)
```


<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [StreamContainer](../../com.groupdocs.watermark.internal/streamcontainer) |  |
| strategyManager | com.groupdocs.watermark.internal.StrategyManager<java.lang.Integer> |  |
| pdfLoadOptions | [PdfLoadOptions](../../com.groupdocs.watermark.options/pdfloadoptions) |  |
| watermarkerSettings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) |  |

### getPages() {#getPages--}
```
public final PdfPageCollection getPages()
```


Hämtar samlingen av alla sidor för detta `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`.


**Returns:**
[PdfPageCollection](../../com.groupdocs.watermark.contents/pdfpagecollection) - The collection of all pages of this `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`.

### getAttachments() {#getAttachments--}
```
public final PdfAttachmentCollection getAttachments()
```


Hämtar samlingen av alla bilagor för detta `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`.


**Returns:**
[PdfAttachmentCollection](../../com.groupdocs.watermark.contents/pdfattachmentcollection) - The collection of all attachments of this `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`.

### getPageMarginType() {#getPageMarginType--}
```
public final int getPageMarginType()
```


Hämtar PDF-sidmarginaler som ska användas vid vattenmärkning.

Denna egenskap fungerar endast när `[Watermark.getConsiderParentMargins()](../../com.groupdocs.watermark/watermark#getConsiderParentMargins--)`
är sann. Om `[Watermark.getConsiderParentMargins()](../../com.groupdocs.watermark/watermark#getConsiderParentMargins--)` är falsk,
när pdf CropBox används som vattenmärkningsområde.

Standardvärdet är `[PdfPageMarginType.TrimBox](../../com.groupdocs.watermark.contents/pdfpagemargintype#TrimBox)`.


**Returns:**
int
### setPageMarginType(int value) {#setPageMarginType-int-}
```
public final void setPageMarginType(int value)
```


Ställer in PDF-sidmarginaler som ska användas vid vattenmärkning.

Denna egenskap fungerar endast när `[Watermark.getConsiderParentMargins()](../../com.groupdocs.watermark/watermark#getConsiderParentMargins--)`
är satt till sann. Om `[Watermark.getConsiderParentMargins()](../../com.groupdocs.watermark/watermark#getConsiderParentMargins--)` är falsk,
när pdf CropBox används som vattenmärkningsområde.

Standardvärdet är `[PdfPageMarginType.TrimBox](../../com.groupdocs.watermark.contents/pdfpagemargintype#TrimBox)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getAsposePdfDocument() {#getAsposePdfDocument--}
```
public final Document getAsposePdfDocument()
```


<br />



**Returns:**
com.aspose.pdf.Document
### addArtifactWatermark(Watermark watermark) {#addArtifactWatermark-com.groupdocs.watermark.Watermark-}
```
public final void addArtifactWatermark(Watermark watermark)
```


<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### addAnnotationWatermark(Watermark watermark, boolean isPrintOnly) {#addAnnotationWatermark-com.groupdocs.watermark.Watermark-boolean-}
```
public final void addAnnotationWatermark(Watermark watermark, boolean isPrintOnly)
```


<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| isPrintOnly | boolean |  |

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
### encrypt(String password) {#encrypt-java.lang.String-}
```
public final void encrypt(String password)
```


Krypterar dokumentet med samma lösenord som användarlösenord och ägarlösenord.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | lösenord | java.lang.String | Användar- och ägarlösenord. |
|

### encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm) {#encrypt-java.lang.String-java.lang.String-int-int-}
```
public final void encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm)
```


Krypterar innehållet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | userPassword | java.lang.String | Användarlösenord. |
|
|  | ownerPassword | java.lang.String | Ägarlösenord. |
|
|  | behörigheter | int | Innehållsbehörigheter. |
|
|  | cryptoAlgorithm | int | Kryptografisk algoritm. |
|

### decrypt() {#decrypt--}
```
public final void decrypt()
```


Dekrypterar innehållet.


### rasterize(int horizontalResolution, int verticalResolution, int imageFormat) {#rasterize-int-int-int-}
```
public final void rasterize(int horizontalResolution, int verticalResolution, int imageFormat)
```


Konverterar alla innehållssidor till bilder.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | horizontalResolution | int | Horisontell bildupplösning. |
|
|  | verticalResolution | int | Vertikal bildupplösning. |
|
|  | imageFormat | int | Bildformat. |
|

### performSave(String filePath) {#performSave-java.lang.String-}
```
public void performSave(String filePath)
```


<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String |  |

### performSave(String filePath, SaveOptions saveOptions) {#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(String filePath, SaveOptions saveOptions)
```


<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### performSave(OutputStream stream) {#performSave-java.io.OutputStream-}
```
public void performSave(OutputStream stream)
```


Sparar dokumentdata till den angivna strömmen.

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | stream | java.io.OutputStream | Strömmen att spara innehållsdata till. |
|

### performSave(OutputStream stream, SaveOptions saveOptions) {#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(OutputStream stream, SaveOptions saveOptions)
```


Sparar dokumentdata till den angivna strömmen.

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | stream | java.io.OutputStream | Strömmen att spara innehållsdata till. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | Alternativen som bör användas när innehållsdata sparas. |
|

### add(Watermark watermark, WatermarkOptions options) {#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-}
```
public void add(Watermark watermark, WatermarkOptions options)
```


<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) |  |

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public void generatePreview(PreviewOptions previewOptions)
```


<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) |  |

