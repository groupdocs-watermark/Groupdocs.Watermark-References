---
title: "GifImageContent"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "एक GIF छवि का प्रतिनिधित्व करता है जहाँ वॉटरमार्क रखा जा सकता है।"
type: docs
weight: 37
url: /hi/java/com.groupdocs.watermark.contents/gifimagecontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content), [com.groupdocs.watermark.contents.ImageContent](../../com.groupdocs.watermark.contents/imagecontent), [com.groupdocs.watermark.contents.MultiframeImageContent](../../com.groupdocs.watermark.contents/multiframeimagecontent)
```
public final class GifImageContent extends MultiframeImageContent
```

एक GIF छवि का प्रतिनिधित्व करता है जहाँ वॉटरमार्क रखा जा सकता है।

## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [GifImageContent(StreamContainer stream, StrategyManager<Integer> strategyManager, GifImageLoadOptions gifImageLoadOptions, WatermarkerSettings watermarkerSettings)](#GifImageContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.groupdocs.watermark.options.GifImageLoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | <br /> |

|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [performSave(String filePath)](#performSave-java.lang.String-) | <br /> |

|
|  | [performSave(OutputStream stream)](#performSave-java.io.OutputStream-) | <br /> |

|
|  | [add(Watermark watermark, WatermarkOptions options)](#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-) | <br /> |

|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.watermark.options.PreviewOptions-) | <br /> |

|
### GifImageContent(StreamContainer stream, StrategyManager<Integer> strategyManager, GifImageLoadOptions gifImageLoadOptions, WatermarkerSettings watermarkerSettings) {#GifImageContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.groupdocs.watermark.options.GifImageLoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public GifImageContent(StreamContainer stream, StrategyManager<Integer> strategyManager, GifImageLoadOptions gifImageLoadOptions, WatermarkerSettings watermarkerSettings)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | [StreamContainer](../../com.groupdocs.watermark.internal/streamcontainer) |  |
| strategyManager | com.groupdocs.watermark.internal.StrategyManager<java.lang.Integer> |  |
| gifImageLoadOptions | [GifImageLoadOptions](../../com.groupdocs.watermark.options/gifimageloadoptions) |  |
| watermarkerSettings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) |  |

### performSave(String filePath) {#performSave-java.lang.String-}
```
public void performSave(String filePath)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String |  |

### performSave(OutputStream stream) {#performSave-java.io.OutputStream-}
```
public void performSave(OutputStream stream)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream |  |

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

