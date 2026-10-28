---
title: "MultiframeImageWatermarkOptions"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "멀티 프레임 이미지에 워터마크를 추가할 때 워터마크 추가 옵션을 나타냅니다."
type: docs
weight: 26
url: /ko/java/com.groupdocs.watermark.options/multiframeimagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions)
```
public class MultiframeImageWatermarkOptions extends WatermarkOptions
```

멀티 프레임 이미지에 워터마크를 추가할 때 워터마크 추가 옵션을 나타냅니다.

**Learn more:**

* [Add watermarks to images](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+images)

다음 예제는 다중 프레임 이미지의 특정 프레임에 워터마크를 추가하는 방법을 보여줍니다.
>
> ````
> ```
>
>    ImageLoadOptions loadOptions = new ImageLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\test.gif", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));
>
>    MultiframeImageWatermarkOptions options = new MultiframeImageWatermarkOptions();
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
|  | [MultiframeImageWatermarkOptions()](#MultiframeImageWatermarkOptions--) | 새로운 `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` 클래스의 인스턴스를 초기화합니다. |
|
|  | [MultiframeImageWatermarkOptions(int frameIndex)](#MultiframeImageWatermarkOptions-int-) | 지정된 프레임 인덱스로 `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` 클래스의 새로운 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getFrameIndex()](#getFrameIndex--) | 워터마크를 추가할 프레임의 인덱스를 가져옵니다. |
|
|  | [setFrameIndex(int value)](#setFrameIndex-int-) | 워터마크를 추가할 프레임의 인덱스를 설정합니다. |
|
### MultiframeImageWatermarkOptions() {#MultiframeImageWatermarkOptions--}
```
public MultiframeImageWatermarkOptions()
```


새로운 `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` 클래스의 인스턴스를 초기화합니다.


### MultiframeImageWatermarkOptions(int frameIndex) {#MultiframeImageWatermarkOptions-int-}
```
public MultiframeImageWatermarkOptions(int frameIndex)
```


지정된 프레임 인덱스로 `[MultiframeImageWatermarkOptions](../../com.groupdocs.watermark.options/multiframeimagewatermarkoptions)` 클래스의 새로운 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | frameIndex | int | 워터마크를 추가할 프레임의 인덱스. |
|

### getFrameIndex() {#getFrameIndex--}
```
public final int getFrameIndex()
```


워터마크를 추가할 프레임의 인덱스를 가져옵니다.


**Returns:**
int - 워터마크를 추가할 프레임의 인덱스.

<br />

*** ** * ** ***

-1 means all frames.

<br />


### setFrameIndex(int value) {#setFrameIndex-int-}
```
public final void setFrameIndex(int value)
```


워터마크를 추가할 프레임의 인덱스를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | int | 워터마크를 추가할 프레임의 인덱스. |

<br />

*** ** * ** ***

-1 means all frames.

<br />

|

