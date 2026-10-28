---
title: "PdfAnnotationWatermarkOptions"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "PDF 문서에 주석 워터마크를 추가할 때 워터마크 추가 옵션을 나타냅니다."
type: docs
weight: 28
url: /ko/java/com.groupdocs.watermark.options/pdfannotationwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfAnnotationWatermarkOptions extends PdfWatermarkOptions
```

PDF 문서에 주석 워터마크를 추가할 때 워터마크 추가 옵션을 나타냅니다.

**Learn more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

다음 예제는 PDF 문서에 이미지 주석 워터마크를 추가하는 방법을 보여줍니다.
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.pdf", loadOptions);
>
>    ImageWatermark watermark = new ImageWatermark("D:\\icon.png");
>
>    PdfAnnotationWatermarkOptions options = new PdfAnnotationWatermarkOptions();
>    options.setPageIndex(-1); // default - all pages
>
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.pdf");
>    watermark.close();
>    watermarker.close();
>  
> ```
> ````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [PdfAnnotationWatermarkOptions()](#PdfAnnotationWatermarkOptions--) | `[PdfAnnotationWatermarkOptions](../../com.groupdocs.watermark.options/pdfannotationwatermarkoptions)` 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | 워터마크를 추가할 페이지 인덱스를 가져옵니다. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | 워터마크를 추가할 페이지 인덱스를 설정합니다. |
|
|  | [getPrintOnly()](#getPrintOnly--) | 주석이 인쇄되지만 PDF 뷰어 애플리케이션에 표시되지 않는지 여부를 나타내는 값을 가져옵니다. |
|
|  | [setPrintOnly(boolean value)](#setPrintOnly-boolean-) | 주석이 인쇄되지만 PDF 뷰어 애플리케이션에 표시되지 않는지 여부를 나타내는 값을 설정합니다. |
|
### PdfAnnotationWatermarkOptions() {#PdfAnnotationWatermarkOptions--}
```
public PdfAnnotationWatermarkOptions()
```


`[PdfAnnotationWatermarkOptions](../../com.groupdocs.watermark.options/pdfannotationwatermarkoptions)` 클래스의 새 인스턴스를 초기화합니다.


### getPageIndex() {#getPageIndex--}
```
public final int getPageIndex()
```


워터마크를 추가할 페이지 인덱스를 가져옵니다.


**Returns:**
int - 워터마크를 추가할 페이지 인덱스.

<br />

*** ** * ** ***

-1 means all pages.

<br />


### setPageIndex(int value) {#setPageIndex-int-}
```
public final void setPageIndex(int value)
```


워터마크를 추가할 페이지 인덱스를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | int | 워터마크를 추가할 페이지 인덱스. |

<br />

*** ** * ** ***

-1 means all pages.

<br />

|

### getPrintOnly() {#getPrintOnly--}
```
public final boolean getPrintOnly()
```


주석이 인쇄되지만 PDF 뷰어 애플리케이션에 표시되지 않는지 여부를 나타내는 값을 가져옵니다.


**Returns:**
boolean - 주석이 인쇄되지만 PDF 뷰어 애플리케이션에 표시되지 않는지 여부를 나타내는 값.

### setPrintOnly(boolean value) {#setPrintOnly-boolean-}
```
public final void setPrintOnly(boolean value)
```


주석이 인쇄되지만 PDF 뷰어 애플리케이션에 표시되지 않는지 여부를 나타내는 값을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 주석이 인쇄되지만 PDF 뷰어 애플리케이션에 표시되지 않는지 여부를 나타내는 값. |
|

