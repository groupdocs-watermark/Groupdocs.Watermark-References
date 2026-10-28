---
title: "PresentationWatermarkSlideOptions"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "프레젠테이션 문서 슬라이드에 워터마크를 추가할 때 옵션을 나타냅니다."
type: docs
weight: 46
url: /ko/java/com.groupdocs.watermark.options/presentationwatermarkslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)
```
public final class PresentationWatermarkSlideOptions extends PresentationWatermarkBaseSlideOptions
```

프레젠테이션 문서 슬라이드에 워터마크를 추가할 때 옵션을 나타냅니다.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

다음 예제는 Power Point 프레젠테이션의 특정 슬라이드에 워터마크를 추가하는 방법을 보여줍니다.
>
> ````
> ```
>
>    PresentationLoadOptions loadOptions = new PresentationLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\Documents\\test.ppt", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36, FontStyle.Bold | FontStyle.Italic));
>    watermark.setHorizontalAlignment(HorizontalAlignment.Center);
>    watermark.setVerticalAlignment(VerticalAlignment.Center);
>  
>    PresentationWatermarkSlideOptions options = new PresentationWatermarkSlideOptions();
>    options.setSlideIndex(0);
>    options.setLocked(false); // default
>    options.setProtectWithUnreadableCharacters(false); // default
>    options.setName(null); // default
>    options.setAlternativeText(null); // default
>    
>    watermarker.save("C:\\Documents\\watermarked_test.ppt");
>    watermarker.close();
>  
> ```
> ````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [PresentationWatermarkSlideOptions()](#PresentationWatermarkSlideOptions--) | `[PresentationWatermarkSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkslideoptions)` 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getSlideIndex()](#getSlideIndex--) | 워터마크를 추가할 슬라이드의 인덱스를 가져옵니다. |
|
|  | [setSlideIndex(int value)](#setSlideIndex-int-) | 워터마크를 추가할 슬라이드의 인덱스를 설정합니다. |
|
### PresentationWatermarkSlideOptions() {#PresentationWatermarkSlideOptions--}
```
public PresentationWatermarkSlideOptions()
```


`[PresentationWatermarkSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkslideoptions)` 클래스의 새 인스턴스를 초기화합니다.


### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```


워터마크를 추가할 슬라이드의 인덱스를 가져옵니다.


**Returns:**
int - 워터마크를 추가할 슬라이드의 인덱스.

<br />

*** ** * ** ***

-1 means all slides.

<br />


### setSlideIndex(int value) {#setSlideIndex-int-}
```
public final void setSlideIndex(int value)
```


워터마크를 추가할 슬라이드의 인덱스를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | int | 워터마크를 추가할 슬라이드의 인덱스. |

<br />

*** ** * ** ***

-1 means all slides.

<br />

|

