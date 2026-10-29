---
title: "TiffImageContent"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar en TIFF-bild där ett vattenmärke kan placeras."
type: docs
weight: 126
url: /sv/java/com.groupdocs.watermark.contents/tiffimagecontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content), [com.groupdocs.watermark.contents.ImageContent](../../com.groupdocs.watermark.contents/imagecontent), [com.groupdocs.watermark.contents.MultiframeImageContent](../../com.groupdocs.watermark.contents/multiframeimagecontent)
```
public class TiffImageContent extends MultiframeImageContent
```

Representerar en TIFF-bild där ett vattenmärke kan placeras.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [TiffImageContent(StreamContainer stream, StrategyManager<Integer> strategyManager, TiffImageLoadOptions tiffImageLoadOptions, WatermarkerSettings watermarkerSettings)](#TiffImageContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.groupdocs.watermark.options.TiffImageLoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | <br /> |

|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [performSave(String filePath)](#performSave-java.lang.String-) | <br /> |

|
| [performSave(OutputStream stream)](#performSave-java.io.OutputStream-) |  |
|  | [add(Watermark watermark, WatermarkOptions options)](#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-) | <br /> |

|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.watermark.options.PreviewOptions-) | <br /> |

|
### TiffImageContent(StreamContainer stream, StrategyManager<Integer> strategyManager, TiffImageLoadOptions tiffImageLoadOptions, WatermarkerSettings watermarkerSettings) {#TiffImageContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.groupdocs.watermark.options.TiffImageLoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public TiffImageContent(StreamContainer stream, StrategyManager<Integer> strategyManager, TiffImageLoadOptions tiffImageLoadOptions, WatermarkerSettings watermarkerSettings)
```


<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [StreamContainer](../../com.groupdocs.watermark.internal/streamcontainer) |  |
| strategyManager | com.groupdocs.watermark.internal.StrategyManager<java.lang.Integer> |  |
| tiffImageLoadOptions | [TiffImageLoadOptions](../../com.groupdocs.watermark.options/tiffimageloadoptions) |  |
| watermarkerSettings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) |  |

### performSave(String filePath) {#performSave-java.lang.String-}
```
public void performSave(String filePath)
```


<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String |  |

### performSave(OutputStream stream) {#performSave-java.io.OutputStream-}
```
public void performSave(OutputStream stream)
```


Sparar innehållet till den angivna strömmen.

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream |  |

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

