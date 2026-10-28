---
title: "PresentationWatermarkMasterSlideOptions"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "Presentation 문서 마스터 슬라이드에 워터마크를 추가할 때 옵션을 나타냅니다."
type: docs
weight: 43
url: /ko/java/com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)
```
public final class PresentationWatermarkMasterSlideOptions extends PresentationWatermarkBaseSlideOptions
```

Presentation 문서 마스터 슬라이드에 워터마크를 추가할 때 옵션을 나타냅니다.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

`[PresentationWatermarkBaseSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions)`의 사용 예제를 참조하십시오.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [PresentationWatermarkMasterSlideOptions()](#PresentationWatermarkMasterSlideOptions--) | `[PresentationWatermarkMasterSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions)` 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getMasterSlideIndex()](#getMasterSlideIndex--) | 워터마크를 추가할 마스터 슬라이드의 인덱스를 가져옵니다. |
|
|  | [setMasterSlideIndex(int value)](#setMasterSlideIndex-int-) | 워터마크를 추가할 마스터 슬라이드의 인덱스를 설정합니다. |
|
### PresentationWatermarkMasterSlideOptions() {#PresentationWatermarkMasterSlideOptions--}
```
public PresentationWatermarkMasterSlideOptions()
```


`[PresentationWatermarkMasterSlideOptions](../../com.groupdocs.watermark.options/presentationwatermarkmasterslideoptions)` 클래스의 새 인스턴스를 초기화합니다.


### getMasterSlideIndex() {#getMasterSlideIndex--}
```
public final int getMasterSlideIndex()
```


워터마크를 추가할 마스터 슬라이드의 인덱스를 가져옵니다.


**Returns:**
int - 워터마크를 추가할 마스터 슬라이드의 인덱스.

<br />

*** ** * ** ***

-1 means all slides.

<br />


### setMasterSlideIndex(int value) {#setMasterSlideIndex-int-}
```
public final void setMasterSlideIndex(int value)
```


워터마크를 추가할 마스터 슬라이드의 인덱스를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | int | 워터마크를 추가할 마스터 슬라이드의 인덱스. |

<br />

*** ** * ** ***

-1 means all slides.

<br />

|

