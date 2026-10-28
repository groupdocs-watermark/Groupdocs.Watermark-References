---
title: "ImageContent"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt ein Bild dar, in das ein Wasserzeichen eingefügt werden kann."
type: docs
weight: 38
url: /de/java/com.groupdocs.watermark.contents/imagecontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content)
```
public class ImageContent extends Content
```

Stellt ein Bild dar, in das ein Wasserzeichen eingefügt werden kann.

**Learn more:**

* [Add watermarks to images](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+images)

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [ImageContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileType fileType, ImageLoadOptions imageLoadOptions, WatermarkerSettings watermarkerSettings)](#ImageContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.groupdocs.watermark.common.FileType-com.groupdocs.watermark.options.ImageLoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | <br /> |

|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getHeight()](#getHeight--) | Ermittelt die Höhe dieses `[ImageContent](../../com.groupdocs.watermark.contents/imagecontent)` in Pixeln. |
|
|  | [getWidth()](#getWidth--) | Ermittelt die Breite dieses `[ImageContent](../../com.groupdocs.watermark.contents/imagecontent)` in Pixeln. |
|
|  | [getAsposeImageContainer()](#getAsposeImageContainer--) | Ermittelt das zugrunde liegende |
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
|  | [performSave(OutputStream stream)](#performSave-java.io.OutputStream-) | Speichert den Inhalt in den angegebenen Stream. |
|
|  | [performSave(OutputStream stream, SaveOptions saveOptions)](#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-) | Speichert den Inhalt in den angegebenen Stream. |
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
| Parameter | Typ | Beschreibung |
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


Ermittelt die Höhe dieses `[ImageContent](../../com.groupdocs.watermark.contents/imagecontent)` in Pixeln.

Gibt die Höhe des aktiven Frames für ein Mehrfachbild zurück.


**Returns:**
int - Die Höhe dieses `[ImageContent](../../com.groupdocs.watermark.contents/imagecontent)` in Pixeln.

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ermittelt die Breite dieses `[ImageContent](../../com.groupdocs.watermark.contents/imagecontent)` in Pixeln.

Gibt die Breite des aktiven Frames für ein Mehrfachbild zurück.


**Returns:**
int - Die Breite dieses `[ImageContent](../../com.groupdocs.watermark.contents/imagecontent)` in Pixeln.

### getAsposeImageContainer() {#getAsposeImageContainer--}
```
public final AsposeImageContainer getAsposeImageContainer()
```


Ermittelt das zugrunde liegende
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String |  |

### performSave(String filePath, SaveOptions saveOptions) {#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(String filePath, SaveOptions saveOptions)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### performSave(OutputStream stream) {#performSave-java.io.OutputStream-}
```
public void performSave(OutputStream stream)
```


Speichert den Inhalt in den angegebenen Stream.

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream |  |

### performSave(OutputStream stream, SaveOptions saveOptions) {#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(OutputStream stream, SaveOptions saveOptions)
```


Speichert den Inhalt in den angegebenen Stream.

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | stream | java.io.OutputStream | Der Stream, in den die Inhaltsdaten gespeichert werden sollen. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | Die Optionen, die beim Speichern der Inhaltsdaten verwendet werden sollten. |
|

### add(Watermark watermark, WatermarkOptions options) {#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-}
```
public void add(Watermark watermark, WatermarkOptions options)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) |  |

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public void generatePreview(PreviewOptions previewOptions)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) |  |

