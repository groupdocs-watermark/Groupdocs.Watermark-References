---
title: "ImageContent"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta un'immagine in cui può essere posizionata una filigrana."
type: docs
weight: 38
url: /it/java/com.groupdocs.watermark.contents/imagecontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content)
```
public class ImageContent extends Content
```

Rappresenta un'immagine in cui può essere posizionata una filigrana.

**Learn more:**

* [Add watermarks to images](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+images)

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [ImageContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileType fileType, ImageLoadOptions imageLoadOptions, WatermarkerSettings watermarkerSettings)](#ImageContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.groupdocs.watermark.common.FileType-com.groupdocs.watermark.options.ImageLoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | <br /> |

|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getHeight()](#getHeight--) | Restituisce l'altezza di questo `[ImageContent](../../com.groupdocs.watermark.contents/imagecontent)` in pixel. |
|
|  | [getWidth()](#getWidth--) | Restituisce la larghezza di questo `[ImageContent](../../com.groupdocs.watermark.contents/imagecontent)` in pixel. |
|
|  | [getAsposeImageContainer()](#getAsposeImageContainer--) | Ottiene sottostante |
GroupDocs.Watermark.Internal.AsposeImageContainer
.
|
|  | [getDocumentInfo()](#getDocumentInfo--) | <br /> |

|
|  | [getFileType()](#getFileType--) | <br /> |

|
|  | [performSave(String filePath)](#performSave-java.lang.String-) | <br /> |

|
|  | [performSave(String filePath, SaveOptions saveOptions)](#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-) | <br /> |

|
|  | [performSave(OutputStream stream)](#performSave-java.io.OutputStream-) | Salva il contenuto nello stream specificato. |
|
|  | [performSave(OutputStream stream, SaveOptions saveOptions)](#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-) | Salva il contenuto nello stream specificato. |
|
|  | [add(Watermark watermark, WatermarkOptions options)](#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-) | <br /> |

|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.watermark.options.PreviewOptions-) | <br /> |

|
### ImageContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileType fileType, ImageLoadOptions imageLoadOptions, WatermarkerSettings watermarkerSettings) {#ImageContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.groupdocs.watermark.common.FileType-com.groupdocs.watermark.options.ImageLoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public ImageContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileType fileType, ImageLoadOptions imageLoadOptions, WatermarkerSettings watermarkerSettings)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [StreamContainer](../../com.groupdocs.watermark.internal/streamcontainer) |  |
| strategyManager | com.groupdocs.watermark.internal.StrategyManager<java.lang.Integer> |  |
| fileType | [FileType](../../com.groupdocs.watermark.common/filetype) |  |
| imageLoadOptions | [ImageLoadOptions](../../com.groupdocs.watermark.options/imageloadoptions) |  |
| watermarkerSettings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Restituisce l'altezza di questo `[ImageContent](../../com.groupdocs.watermark.contents/imagecontent)` in pixel.

Restituisce l'altezza del fotogramma attivo per un'immagine multiframe.


**Returns:**
int - L'altezza di questo `[ImageContent](../../com.groupdocs.watermark.contents/imagecontent)` in pixel.

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Restituisce la larghezza di questo `[ImageContent](../../com.groupdocs.watermark.contents/imagecontent)` in pixel.

Restituisce la larghezza del fotogramma attivo per un'immagine multiframe.


**Returns:**
int - La larghezza di questo `[ImageContent](../../com.groupdocs.watermark.contents/imagecontent)` in pixel.

### getAsposeImageContainer() {#getAsposeImageContainer--}
```
public final AsposeImageContainer getAsposeImageContainer()
```


Ottiene sottostante
GroupDocs.Watermark.Internal.AsposeImageContainer
.


**Returns:**
[AsposeImageContainer](../../com.groupdocs.watermark.contents/asposeimagecontainer)
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


Salva il contenuto nello stream specificato.

<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream |  |

### performSave(OutputStream stream, SaveOptions saveOptions) {#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(OutputStream stream, SaveOptions saveOptions)
```


Salva il contenuto nello stream specificato.

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

