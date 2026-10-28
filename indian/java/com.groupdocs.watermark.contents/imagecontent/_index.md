---
title: "ImageContent"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "एक छवि का प्रतिनिधित्व करता है जहाँ वॉटरमार्क रखा जा सकता है।"
type: docs
weight: 38
url: /hi/java/com.groupdocs.watermark.contents/imagecontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content)
```
public class ImageContent extends Content
```

एक छवि का प्रतिनिधित्व करता है जहाँ वॉटरमार्क रखा जा सकता है।

**Learn more:**

* [Add watermarks to images](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+images)

## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [ImageContent(StreamContainer stream, StrategyManager<Integer> strategyManager, FileType fileType, ImageLoadOptions imageLoadOptions, WatermarkerSettings watermarkerSettings)](#ImageContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.groupdocs.watermark.common.FileType-com.groupdocs.watermark.options.ImageLoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | <br /> |

|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getHeight()](#getHeight--) | इस `[ImageContent](../../com.groupdocs.watermark.contents/imagecontent)` की ऊँचाई पिक्सेल में प्राप्त करता है। |
|
|  | [getWidth()](#getWidth--) | इस `[ImageContent](../../com.groupdocs.watermark.contents/imagecontent)` की चौड़ाई पिक्सेल में प्राप्त करता है। |
|
|  | [getAsposeImageContainer()](#getAsposeImageContainer--) | अंतर्निहित प्राप्त करता है |
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
|  | [performSave(OutputStream stream)](#performSave-java.io.OutputStream-) | निर्दिष्ट स्ट्रीम में सामग्री को सहेजता है। |
|
|  | [performSave(OutputStream stream, SaveOptions saveOptions)](#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-) | निर्दिष्ट स्ट्रीम में सामग्री को सहेजता है। |
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
| पैरामीटर | प्रकार | विवरण |
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


इस `[ImageContent](../../com.groupdocs.watermark.contents/imagecontent)` की ऊँचाई पिक्सेल में प्राप्त करता है।

एक मल्टीफ़्रेम छवि के सक्रिय फ्रेम की ऊँचाई लौटाता है।


**Returns:**
int - इस `[ImageContent](../../com.groupdocs.watermark.contents/imagecontent)` की पिक्सेल में ऊँचाई।

### getWidth() {#getWidth--}
```
public final int getWidth()
```


इस `[ImageContent](../../com.groupdocs.watermark.contents/imagecontent)` की चौड़ाई पिक्सेल में प्राप्त करता है।

एक मल्टीफ़्रेम छवि के सक्रिय फ्रेम की चौड़ाई लौटाता है।


**Returns:**
int - इस `[ImageContent](../../com.groupdocs.watermark.contents/imagecontent)` की पिक्सेल में चौड़ाई।

### getAsposeImageContainer() {#getAsposeImageContainer--}
```
public final AsposeImageContainer getAsposeImageContainer()
```


अंतर्निहित प्राप्त करता है
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String |  |

### performSave(String filePath, SaveOptions saveOptions) {#performSave-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(String filePath, SaveOptions saveOptions)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String |  |
| saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) |  |

### performSave(OutputStream stream) {#performSave-java.io.OutputStream-}
```
public void performSave(OutputStream stream)
```


निर्दिष्ट स्ट्रीम में सामग्री को सहेजता है।

<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream |  |

### performSave(OutputStream stream, SaveOptions saveOptions) {#performSave-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public void performSave(OutputStream stream, SaveOptions saveOptions)
```


निर्दिष्ट स्ट्रीम में सामग्री को सहेजता है।

<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | stream | java.io.OutputStream | सामग्री डेटा को सहेजने के लिए स्ट्रीम। |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | सामग्री डेटा को सहेजते समय उपयोग किए जाने वाले विकल्प। |
|

### add(Watermark watermark, WatermarkOptions options) {#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-}
```
public void add(Watermark watermark, WatermarkOptions options)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) |  |

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public void generatePreview(PreviewOptions previewOptions)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) |  |

