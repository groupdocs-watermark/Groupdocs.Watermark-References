---
title: "GifImageWatermarkOptions"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "GIF 이미지에 워터마크를 추가할 때 워터마크 추가 옵션을 나타냅니다."
type: docs
weight: 21
url: /ko/java/com.groupdocs.watermark.options/gifimagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)
```
public final class GifImageWatermarkOptions extends MultiframeImageWatermarkOptions
```

GIF 이미지에 워터마크를 추가할 때 워터마크 추가 옵션을 나타냅니다.

**Learn more:**

* [Add watermarks to images](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+images)

다음 예제는 GIF 이미지의 특정 프레임에 워터마크를 추가하는 방법을 보여줍니다.
>
> ````
> ```
>
>    GifImageLoadOptions loadOptions = new GifImageLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\test.gif", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));
>
>    GifImageWatermarkOptions options = new GifImageWatermarkOptions();
>    options.setFrameIndex(0);
>
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.gif");
>    watermarker.close();
>  
> ```
> ````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [GifImageWatermarkOptions()](#GifImageWatermarkOptions--) | `[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)` 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [GifImageWatermarkOptions(int frameIndex)](#GifImageWatermarkOptions-int-) | `[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)` 클래스의 새 인스턴스를 지정된 프레임 인덱스로 초기화합니다. |
|
### GifImageWatermarkOptions() {#GifImageWatermarkOptions--}
```
public GifImageWatermarkOptions()
```


`[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)` 클래스의 새 인스턴스를 초기화합니다.


### GifImageWatermarkOptions(int frameIndex) {#GifImageWatermarkOptions-int-}
```
public GifImageWatermarkOptions(int frameIndex)
```


`[GifImageWatermarkOptions](../../com.groupdocs.watermark.options/gifimagewatermarkoptions)` 클래스의 새 인스턴스를 지정된 프레임 인덱스로 초기화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | frameIndex | int | 워터마크를 추가할 프레임의 인덱스. |
|

