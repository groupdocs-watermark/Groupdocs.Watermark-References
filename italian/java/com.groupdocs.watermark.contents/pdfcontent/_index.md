---
title: "PdfContent"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta un documento PDF dove può essere posizionata una filigrana."
type: docs
weight: 60
url: /it/java/com.groupdocs.watermark.contents/pdfcontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content)

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IEncryptable](../../com.groupdocs.watermark.internal/iencryptable)
```
public class PdfContent extends Content implements IEncryptable
```

Rappresenta un documento PDF dove può essere posizionata una filigrana.

**Learn more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)
* [Existing objects in PDF document](../https://docs.groupdocs.com/display/watermarkjava/Existing+objects+in+PDF+document)
* [Rasterize document or page](../https://docs.groupdocs.com/display/watermarkjava/Rasterize+document+or+page)
* [Watermarks in PDF document](../https://docs.groupdocs.com/display/watermarkjava/Watermarks+in+PDF+document)

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [PdfContent(StreamContainer stream, StrategyManager<Integer> strategyManager, PdfLoadOptions pdfLoadOptions, WatermarkerSettings watermarkerSettings)](#PdfContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.groupdocs.watermark.options.PdfLoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | <br /> |

|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getPages()](#getPages--) | Restituisce la collezione di tutte le pagine di questo `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`. |
|
|  | [getAttachments()](#getAttachments--) | Restituisce la collezione di tutti gli allegati di questo `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`. |
|
|  | [getPageMarginType()](#getPageMarginType--) | Restituisce i margini della pagina PDF da utilizzare durante l'aggiunta della filigrana. |
|
|  | [setPageMarginType(int value)](#setPageMarginType-int-) | Imposta i margini della pagina PDF da utilizzare durante l'aggiunta della filigrana. |
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
|  | [encrypt(String password)](#encrypt-java.lang.String-) | Cifra il documento usando la stessa password dell'utente e del proprietario. |
|
|  | [encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm)](#encrypt-java.lang.String-java.lang.String-int-int-) | Cifra il contenuto. |
|
|  | [decrypt()](#decrypt--) | Decifra il contenuto. |
|
|  | [rasterize(int horizontalResolution, int verticalResolution, int imageFormat)](#rasterize-int-int-int-) | Converte tutte le pagine del contenuto in immagini. |
|
|  | [performSave(String filePath)](#performSave-java.lang.String-) | <br /> |

|
|  | [performSave(String filePath, SaveOptions saveOptions)](#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-) | <br /> |

|
|  | [performSave(OutputStream stream)](#performSave-java.io.OutputStream-) | Salva i dati del documento nello stream specificato. |
|
|  | [performSave(OutputStream stream, SaveOptions saveOptions)](#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-) | Salva i dati del documento nello stream specificato. |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [StreamContainer](../../com.groupdocs.watermark.internal/streamcontainer) |  |
| strategyManager | com.groupdocs.watermark.internal.StrategyManager<java.lang.Integer> |  |
| pdfLoadOptions | [PdfLoadOptions](../../com.groupdocs.watermark.options/pdfloadoptions) |  |
| watermarkerSettings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) |  |

### getPages() {#getPages--}
```
public final PdfPageCollection getPages()
```


Restituisce la collezione di tutte le pagine di questo `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`.


**Returns:**
[PdfPageCollection](../../com.groupdocs.watermark.contents/pdfpagecollection) - The collection of all pages of this `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`.

### getAttachments() {#getAttachments--}
```
public final PdfAttachmentCollection getAttachments()
```


Restituisce la collezione di tutti gli allegati di questo `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`.


**Returns:**
[PdfAttachmentCollection](../../com.groupdocs.watermark.contents/pdfattachmentcollection) - The collection of all attachments of this `[PdfContent](../../com.groupdocs.watermark.contents/pdfcontent)`.

### getPageMarginType() {#getPageMarginType--}
```
public final int getPageMarginType()
```


Restituisce i margini della pagina PDF da utilizzare durante l'aggiunta della filigrana.

Questa proprietà funziona solo quando `[Watermark.getConsiderParentMargins()](../../com.groupdocs.watermark/watermark#getConsiderParentMargins--)`
è vero. Se `[Watermark.getConsiderParentMargins()](../../com.groupdocs.watermark/watermark#getConsiderParentMargins--)` è falso,
quando il CropBox PDF è usato come area di filigrana.

Il valore predefinito è `[PdfPageMarginType.TrimBox](../../com.groupdocs.watermark.contents/pdfpagemargintype#TrimBox)`.


**Returns:**
int
### setPageMarginType(int value) {#setPageMarginType-int-}
```
public final void setPageMarginType(int value)
```


Imposta i margini della pagina PDF da utilizzare durante l'aggiunta della filigrana.

Questa proprietà funziona solo quando `[Watermark.getConsiderParentMargins()](../../com.groupdocs.watermark/watermark#getConsiderParentMargins--)`
è impostato su vero. Se `[Watermark.getConsiderParentMargins()](../../com.groupdocs.watermark/watermark#getConsiderParentMargins--)` è falso,
quando il CropBox PDF è usato come area di filigrana.

Il valore predefinito è `[PdfPageMarginType.TrimBox](../../com.groupdocs.watermark.contents/pdfpagemargintype#TrimBox)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### addAnnotationWatermark(Watermark watermark, boolean isPrintOnly) {#addAnnotationWatermark-com.groupdocs.watermark.Watermark-boolean-}
```
public final void addAnnotationWatermark(Watermark watermark, boolean isPrintOnly)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
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


Cifra il documento usando la stessa password dell'utente e del proprietario.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | password | java.lang.String | Password utente e proprietario. |
|

### encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm) {#encrypt-java.lang.String-java.lang.String-int-int-}
```
public final void encrypt(String userPassword, String ownerPassword, int permissions, int cryptoAlgorithm)
```


Cifra il contenuto.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | userPassword | java.lang.String | Password utente. |
|
|  | ownerPassword | java.lang.String | Password del proprietario. |
|
|  | permessi | int | Permessi del contenuto. |
|
|  | cryptoAlgorithm | int | Algoritmo crittografico. |
|

### decrypt() {#decrypt--}
```
public final void decrypt()
```


Decifra il contenuto.


### rasterize(int horizontalResolution, int verticalResolution, int imageFormat) {#rasterize-int-int-int-}
```
public final void rasterize(int horizontalResolution, int verticalResolution, int imageFormat)
```


Converte tutte le pagine del contenuto in immagini.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | horizontalResolution | int | Risoluzione orizzontale dell'immagine. |
|
|  | verticalResolution | int | Risoluzione verticale dell'immagine. |
|
|  | imageFormat | int | Formato immagine. |
|

### performSave(String filePath) {#performSave-java.lang.String-}
```
public void performSave(String filePath)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String |  |

### performSave(String filePath, SaveOptions saveOptions) {#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(String filePath, SaveOptions saveOptions)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### performSave(OutputStream stream) {#performSave-java.io.OutputStream-}
```
public void performSave(OutputStream stream)
```


Salva i dati del documento nello stream specificato.

<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | stream | java.io.OutputStream | Lo stream su cui salvare i dati del contenuto. |
|

### performSave(OutputStream stream, SaveOptions saveOptions) {#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(OutputStream stream, SaveOptions saveOptions)
```


Salva i dati del documento nello stream specificato.

<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | stream | java.io.OutputStream | Lo stream su cui salvare i dati del contenuto. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | Le opzioni che dovrebbero essere usate durante il salvataggio dei dati del contenuto. |
|

### add(Watermark watermark, WatermarkOptions options) {#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-}
```
public void add(Watermark watermark, WatermarkOptions options)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) |  |

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public void generatePreview(PreviewOptions previewOptions)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) |  |

