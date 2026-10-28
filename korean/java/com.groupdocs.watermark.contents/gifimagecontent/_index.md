---
title: "GifImageContent"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "워터마크를 배치할 수 있는 gif 이미지를 나타냅니다."
type: docs
weight: 37
url: /ko/java/com.groupdocs.watermark.contents/gifimagecontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content), [com.groupdocs.watermark.contents.ImageContent](../../com.groupdocs.watermark.contents/imagecontent), [com.groupdocs.watermark.contents.MultiframeImageContent](../../com.groupdocs.watermark.contents/multiframeimagecontent)
```
public final class GifImageContent extends MultiframeImageContent
```

워터마크를 배치할 수 있는 gif 이미지를 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [GifImageContent(StreamContainer stream, StrategyManager<Integer> strategyManager, GifImageLoadOptions gifImageLoadOptions, WatermarkerSettings watermarkerSettings)](#GifImageContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.groupdocs.watermark.options.GifImageLoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | <br /> |

|
## 메서드

| 메서드 | 설명 |
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
| 매개변수 | 유형 | 설명 |
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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String |  |

### performSave(OutputStream stream) {#performSave-java.io.OutputStream-}
```
public void performSave(OutputStream stream)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 스트림 | java.io.OutputStream |  |

### add(Watermark watermark, WatermarkOptions options) {#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-}
```
public void add(Watermark watermark, WatermarkOptions options)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) |  |

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public void generatePreview(PreviewOptions previewOptions)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) |  |

