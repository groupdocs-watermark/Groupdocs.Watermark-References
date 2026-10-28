---
title: "WordProcessingWatermarkPagesOptions"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "Word 문서 페이지에 워터마크를 추가할 때 옵션을 나타냅니다."
type: docs
weight: 76
url: /ko/java/com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkPagesOptions extends WordProcessingWatermarkBaseOptions
```

Word 문서 페이지에 워터마크를 추가할 때 옵션을 나타냅니다.

**Learn more:**

* [Add watermarks to word processing documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+word+processing+documents)

다음 예제는 Word 문서의 특정 페이지에 워터마크를 추가하는 방법을 보여줍니다.
>
> ````
> ```
>
>    WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.doc", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    WordProcessingWatermarkPagesOptions options = new WordProcessingWatermarkPagesOptions();
>    options.setPageNumbers(new int[] { 1 });
>    
>    watermarker.save("D:\\watermarked_test.doc");
>    watermarker.close();
>  
> ```
> ````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [WordProcessingWatermarkPagesOptions()](#WordProcessingWatermarkPagesOptions--) | `[WordProcessingWatermarkPagesOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions)` 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getPageNumbers()](#getPageNumbers--) | 워터마크를 추가할 페이지 번호를 가져옵니다. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | 워터마크를 추가할 페이지 번호를 설정합니다. |
|
### WordProcessingWatermarkPagesOptions() {#WordProcessingWatermarkPagesOptions--}
```
public WordProcessingWatermarkPagesOptions()
```


`[WordProcessingWatermarkPagesOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions)` 클래스의 새 인스턴스를 초기화합니다.


### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


워터마크를 추가할 페이지 번호를 가져옵니다.


**Returns:**
int[] - 워터마크를 추가할 페이지 번호.

<br />

*** ** * ** ***

모든 번호는 1보다 크거나 같아야 합니다. 이 속성은 문서에 워터마크를 추가할 때만 사용됩니다. 이 값이 null 이거나 비어 있으면 워터마크가 모든 페이지에 추가됩니다.

<br />


### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


워터마크를 추가할 페이지 번호를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | int[] | 워터마크를 추가할 페이지 번호. |

<br />

*** ** * ** ***

모든 번호는 1보다 크거나 같아야 합니다. 이 속성은 문서에 워터마크를 추가할 때만 사용됩니다. 이 값이 null 이거나 비어 있으면 워터마크가 모든 페이지에 추가됩니다.

<br />

|

