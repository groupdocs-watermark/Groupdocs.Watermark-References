---
title: "TiffImageContent"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "워터마크를 배치할 수 있는 TIFF 이미지를 나타냅니다."
type: docs
weight: 126
url: /ko/java/com.groupdocs.watermark.contents/tiffimagecontent/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.Content](../../com.groupdocs.watermark.contents/content), [com.groupdocs.watermark.contents.ImageContent](../../com.groupdocs.watermark.contents/imagecontent), [com.groupdocs.watermark.contents.MultiframeImageContent](../../com.groupdocs.watermark.contents/multiframeimagecontent)
```
public class TiffImageContent extends MultiframeImageContent
```

워터마크를 배치할 수 있는 TIFF 이미지를 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [TiffImageContent(StreamContainer stream, StrategyManager<Integer> strategyManager, TiffImageLoadOptions tiffImageLoadOptions, WatermarkerSettings watermarkerSettings)](#TiffImageContent-com.groupdocs.watermark.internal.StreamContainer-com.groupdocs.watermark.internal.StrategyManager-java.lang.Integer--com.groupdocs.watermark.options.TiffImageLoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | <br /> |

|
## 메서드

| 메서드 | 설명 |
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
| 매개변수 | 유형 | 설명 |
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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String |  |

### performSave(OutputStream stream) {#performSave-java.io.OutputStream-}
```
public void performSave(OutputStream stream)
```


지정된 스트림에 콘텐츠를 저장합니다.

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

