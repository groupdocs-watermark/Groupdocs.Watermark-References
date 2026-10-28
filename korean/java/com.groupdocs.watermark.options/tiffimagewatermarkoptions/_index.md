---
title: "TiffImageWatermarkOptions"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "TIFF 이미지에 워터마크를 추가할 때 워터마크 추가 옵션을 나타냅니다."
type: docs
weight: 63
url: /ko/java/com.groupdocs.watermark.options/tiffimagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)
```
public final class TiffImageWatermarkOptions extends MultiframeImageWatermarkOptions
```

TIFF 이미지에 워터마크를 추가할 때 워터마크 추가 옵션을 나타냅니다.

**Learn more:**

* [Add watermarks to images](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+images)

다음 예제는 TIFF 이미지의 특정 프레임에 워터마크를 추가하는 방법을 보여줍니다.
>
> ````
> ```
>
>    TiffImageImageLoadOptions loadOptions = new TiffImageImageLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\test.tiff", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));
>
>    TiffImageWatermarkOptions options = new TiffImageWatermarkOptions();
>    options.setFrameIndex(0);
>
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.tiff");
>    watermarker.close();
>  
> ```
> ````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [TiffImageWatermarkOptions()](#TiffImageWatermarkOptions--) | `[TiffImageWatermarkOptions](../../com.groupdocs.watermark.options/tiffimagewatermarkoptions)` 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [TiffImageWatermarkOptions(int frameIndex)](#TiffImageWatermarkOptions-int-) | 지정된 프레임 인덱스로 `[TiffImageWatermarkOptions](../../com.groupdocs.watermark.options/tiffimagewatermarkoptions)` 클래스의 새 인스턴스를 초기화합니다. |
|
### TiffImageWatermarkOptions() {#TiffImageWatermarkOptions--}
```
public TiffImageWatermarkOptions()
```


`[TiffImageWatermarkOptions](../../com.groupdocs.watermark.options/tiffimagewatermarkoptions)` 클래스의 새 인스턴스를 초기화합니다.


### TiffImageWatermarkOptions(int frameIndex) {#TiffImageWatermarkOptions-int-}
```
public TiffImageWatermarkOptions(int frameIndex)
```


지정된 프레임 인덱스로 `[TiffImageWatermarkOptions](../../com.groupdocs.watermark.options/tiffimagewatermarkoptions)` 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | frameIndex | int | 워터마크를 추가할 프레임의 인덱스. |
|

