---
title: "TiffImageContent"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta un'immagine TIFF in cui è possibile posizionare una filigrana."
type: docs
weight: 126
url: /it/java/com.groupdocs.watermark.contents/tiffimagecontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content), [com.groupdocs.watermark.contents.ImageContent](../../com.groupdocs.watermark.contents/imagecontent), [com.groupdocs.watermark.contents.MultiframeImageContent](../../com.groupdocs.watermark.contents/multiframeimagecontent)
```
public class TiffImageContent extends MultiframeImageContent
```

Rappresenta un'immagine TIFF in cui è possibile posizionare una filigrana.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [TiffImageContent(StreamContainer stream, StrategyManager<Integer> strategyManager, TiffImageLoadOptions tiffImageLoadOptions, WatermarkerSettings watermarkerSettings)](#TiffImageContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.groupdocs.watermark.options.TiffImageLoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | <br /> |

|
## Metodi

| Metodo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String |  |

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

