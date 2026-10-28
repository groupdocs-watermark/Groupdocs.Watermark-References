---
title: "WordProcessingWatermarkSectionOptions"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "Word 문서 섹션에 도형 워터마크를 추가할 때 옵션을 나타냅니다."
type: docs
weight: 77
url: /ko/java/com.groupdocs.watermark.options/wordprocessingwatermarksectionoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkSectionOptions extends WordProcessingWatermarkBaseOptions
```

Word 문서 섹션에 도형 워터마크를 추가할 때 옵션을 나타냅니다.

**Learn more:**

* [Add watermarks to word processing documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+word+processing+documents)

다음 예제는 Word 문서의 특정 섹션에 워터마크를 추가하는 방법을 보여줍니다.
>
> ````
> ```
>
>    WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.doc", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    WordProcessingWatermarkSectionOptions options = new WordProcessingWatermarkSectionOptions();
>    options.setSectionIndex(0);
>    
>    watermarker.save("D:\\watermarked_test.doc");
>    watermarker.close();
>  
> ```
> ````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [WordProcessingWatermarkSectionOptions()](#WordProcessingWatermarkSectionOptions--) | `[WordProcessingWatermarkSectionOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarksectionoptions)` 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getSectionIndex()](#getSectionIndex--) | 워터마크를 추가할 섹션의 인덱스를 가져옵니다. |
|
|  | [setSectionIndex(int value)](#setSectionIndex-int-) | 워터마크를 추가할 섹션의 인덱스를 설정합니다. |
|
### WordProcessingWatermarkSectionOptions() {#WordProcessingWatermarkSectionOptions--}
```
public WordProcessingWatermarkSectionOptions()
```


`[WordProcessingWatermarkSectionOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarksectionoptions)` 클래스의 새 인스턴스를 초기화합니다.


### getSectionIndex() {#getSectionIndex--}
```
public final int getSectionIndex()
```


워터마크를 추가할 섹션의 인덱스를 가져옵니다.


**Returns:**
int - 워터마크를 추가할 섹션의 인덱스.

<br />

*** ** * ** ***

-1 means all sections.

<br />


### setSectionIndex(int value) {#setSectionIndex-int-}
```
public final void setSectionIndex(int value)
```


워터마크를 추가할 섹션의 인덱스를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | int | 워터마크를 추가할 섹션의 인덱스. |

<br />

*** ** * ** ***

-1 means all sections.

<br />

|

