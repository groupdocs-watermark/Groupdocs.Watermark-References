---
title: "PdfXObjectWatermarkOptions"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "PDF 문서에 XObject 워터마크를 추가할 때 워터마크 추가 옵션을 나타냅니다."
type: docs
weight: 34
url: /ko/java/com.groupdocs.watermark.options/pdfxobjectwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfXObjectWatermarkOptions extends PdfWatermarkOptions
```

PDF 문서에 XObject 워터마크를 추가할 때 워터마크 추가 옵션을 나타냅니다.

**Learn more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

다음 예제는 PDF 문서의 특정 페이지에 워터마크를 추가하는 방법을 보여줍니다.
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\doc.pdf", loadOptions);
>
>    ImageWatermark watermark = new ImageWatermark("C:\\watermark.png");
>
>    PdfXObjectWatermarkOptions options = new PdfXObjectWatermarkOptions();
>    options.setPageIndex(0);
>
>    watermarker.add(watermark, options);
>    watermarker.save("C:\\watermarked_doc.pdf");
>    watermark.close();
>    watermarker.close();
>  
> ```
> ````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [PdfXObjectWatermarkOptions()](#PdfXObjectWatermarkOptions--) | `[PdfXObjectWatermarkOptions](../../com.groupdocs.watermark.options/pdfxobjectwatermarkoptions)` 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | 워터마크를 추가할 페이지 인덱스를 가져옵니다. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | 워터마크를 추가할 페이지 인덱스를 설정합니다. |
|
### PdfXObjectWatermarkOptions() {#PdfXObjectWatermarkOptions--}
```
public PdfXObjectWatermarkOptions()
```


`[PdfXObjectWatermarkOptions](../../com.groupdocs.watermark.options/pdfxobjectwatermarkoptions)` 클래스의 새 인스턴스를 초기화합니다.


### getPageIndex() {#getPageIndex--}
```
public final int getPageIndex()
```


워터마크를 추가할 페이지 인덱스를 가져옵니다.


**Returns:**
int - 워터마크를 추가할 페이지 인덱스.

### setPageIndex(int value) {#setPageIndex-int-}
```
public final void setPageIndex(int value)
```


워터마크를 추가할 페이지 인덱스를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | int | 워터마크를 추가할 페이지 인덱스. |
|

