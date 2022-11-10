---
title: GifImageContent
second_title: GroupDocs.Watermark for Java API Reference
description: Represents a gif image where a watermark can be placed.
type: docs
weight: 37
url: /java/com.groupdocs.watermark.contents/gifimagecontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content), [com.groupdocs.watermark.contents.ImageContent](../../com.groupdocs.watermark.contents/imagecontent), [com.groupdocs.watermark.contents.MultiframeImageContent](../../com.groupdocs.watermark.contents/multiframeimagecontent)
```
public final class GifImageContent extends MultiframeImageContent
```

Represents a gif image where a watermark can be placed.
## Constructors

| Constructor | Description |
| --- | --- |
| [GifImageContent(StreamContainer stream, StrategyManager<Integer> strategyManager, GifImageLoadOptions gifImageLoadOptions, WatermarkerSettings watermarkerSettings)](#GifImageContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.groupdocs.watermark.options.GifImageLoadOptions-com.groupdocs.watermark.WatermarkerSettings-) |  |
## Methods

| Method | Description |
| --- | --- |
| [performSave(String filePath)](#performSave-java.lang.String-) |  |
| [performSave(OutputStream stream)](#performSave-java.io.OutputStream-) |  |
| [add(Watermark watermark, WatermarkOptions options)](#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-) |  |
| [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.watermark.options.PreviewOptions-) |  |
### GifImageContent(StreamContainer stream, StrategyManager<Integer> strategyManager, GifImageLoadOptions gifImageLoadOptions, WatermarkerSettings watermarkerSettings) {#GifImageContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.groupdocs.watermark.options.GifImageLoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public GifImageContent(StreamContainer stream, StrategyManager<Integer> strategyManager, GifImageLoadOptions gifImageLoadOptions, WatermarkerSettings watermarkerSettings)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.groupdocs.watermark.internal.StreamContainer |  |
| strategyManager | com.groupdocs.watermark.internal.StrategyManager<java.lang.Integer> |  |
| gifImageLoadOptions | [GifImageLoadOptions](../../com.groupdocs.watermark.options/gifimageloadoptions) |  |
| watermarkerSettings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) |  |

### performSave(String filePath) {#performSave-java.lang.String-}
```
public void performSave(String filePath)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String |  |

### performSave(OutputStream stream) {#performSave-java.io.OutputStream-}
```
public void performSave(OutputStream stream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream |  |

### add(Watermark watermark, WatermarkOptions options) {#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-}
```
public void add(Watermark watermark, WatermarkOptions options)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) |  |

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public void generatePreview(PreviewOptions previewOptions)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) |  |

