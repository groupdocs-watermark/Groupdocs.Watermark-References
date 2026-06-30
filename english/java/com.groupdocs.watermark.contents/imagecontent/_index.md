---
title: ImageContent
second_title: GroupDocs.Watermark for Java API Reference
description: Represents an image where a watermark can be placed.
type: docs
weight: 38
url: /java/com.groupdocs.watermark.contents/imagecontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content)
```
public class ImageContent extends Content
```

Represents an image where a watermark can be placed.

**Learn more:**

* [Add watermarks to images](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+images)

## Constructors

| Constructor | Description |
| --- | --- |
| [ImageContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileType fileType, ImageLoadOptions imageLoadOptions, WatermarkerSettings watermarkerSettings)](#ImageContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.groupdocs.watermark.common.FileType-com.groupdocs.watermark.options.ImageLoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | <br />

 |
## Methods

| Method | Description |
| --- | --- |
| [getHeight()](#getHeight--) | Gets the height of this `[ImageContent](../../com.groupdocs.watermark.contents/imagecontent)` in pixels.
 |
| [getWidth()](#getWidth--) | Gets the width of this `[ImageContent](../../com.groupdocs.watermark.contents/imagecontent)` in pixels.
 |
| [getAsposeImageContainer()](#getAsposeImageContainer--) | Gets underlying 
GroupDocs.Watermark.Internal.AsposeImageContainer
.
 |
| [getDocumentInfo()](#getDocumentInfo--) | <br />

 |
| [getFileType()](#getFileType--) | <br />

 |
| [performSave(String filePath)](#performSave-java.lang.String-) | <br />

 |
| [performSave(String filePath, SaveOptions saveOptions)](#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-) | <br />

 |
| [performSave(OutputStream stream)](#performSave-java.io.OutputStream-) | Saves the content to the specified stream.
 |
| [performSave(OutputStream stream, SaveOptions saveOptions)](#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-) | Saves the content to the specified stream.
 |
| [add(Watermark watermark, WatermarkOptions options)](#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-) | <br />

 |
| [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.watermark.options.PreviewOptions-) | <br />

 |
### ImageContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileType fileType, ImageLoadOptions imageLoadOptions, WatermarkerSettings watermarkerSettings) {#ImageContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.groupdocs.watermark.common.FileType-com.groupdocs.watermark.options.ImageLoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public ImageContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileType fileType, ImageLoadOptions imageLoadOptions, WatermarkerSettings watermarkerSettings)
```


<br />



**Parameters:**
| Parameter | Type | Description |
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


Gets the height of this `[ImageContent](../../com.groupdocs.watermark.contents/imagecontent)` in pixels.

Returns the height of the active frame for a multiframe image.


**Returns:**
int - The height of this `[ImageContent](../../com.groupdocs.watermark.contents/imagecontent)` in pixels.

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Gets the width of this `[ImageContent](../../com.groupdocs.watermark.contents/imagecontent)` in pixels.

Returns the width of the active frame for a multiframe image.


**Returns:**
int - The width of this `[ImageContent](../../com.groupdocs.watermark.contents/imagecontent)` in pixels.

### getAsposeImageContainer() {#getAsposeImageContainer--}
```
public final AsposeImageContainer getAsposeImageContainer()
```


Gets underlying 
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
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String |  |

### performSave(String filePath, SaveOptions saveOptions) {#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(String filePath, SaveOptions saveOptions)
```


<br />



**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### performSave(OutputStream stream) {#performSave-java.io.OutputStream-}
```
public void performSave(OutputStream stream)
```


Saves the content to the specified stream.

<br />



**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream |  |

### performSave(OutputStream stream, SaveOptions saveOptions) {#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(OutputStream stream, SaveOptions saveOptions)
```


Saves the content to the specified stream.

<br />



**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream to save the content data to.
 |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | The options tha should be used when saving the content data.
 |

### add(Watermark watermark, WatermarkOptions options) {#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-}
```
public void add(Watermark watermark, WatermarkOptions options)
```


<br />



**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) |  |

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public void generatePreview(PreviewOptions previewOptions)
```


<br />



**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) |  |

