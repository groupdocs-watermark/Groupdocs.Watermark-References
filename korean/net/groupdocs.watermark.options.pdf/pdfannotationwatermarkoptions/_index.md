---
title: PdfAnnotationWatermarkOptions
second_title: .NET API 참조용 GroupDocs.Watermark
description: PDF 문서에 주석 워터마크를 추가할 때 워터마크 추가 옵션을 나타냅니다.
type: docs
weight: 1860
url: /ko/net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/
---
## PdfAnnotationWatermarkOptions class

PDF 문서에 주석 워터마크를 추가할 때 워터마크 추가 옵션을 나타냅니다.

```csharp
public sealed class PdfAnnotationWatermarkOptions : PdfWatermarkOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfAnnotationWatermarkOptions](pdfannotationwatermarkoptions)() | 의 새 인스턴스를 초기화합니다.[`PdfAnnotationWatermarkOptions`](../pdfannotationwatermarkoptions) 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [PageIndex](../../groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/pageindex) { get; set; } | 워터마크를 추가할 페이지 인덱스를 가져오거나 설정합니다. |
| [PrintOnly](../../groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/printonly) { get; set; } | 주석을 인쇄할지 여부를 나타내는 값을 가져오거나 설정하지만 pdf 보기 응용 프로그램에서 표시되지 않습니다. |

### 비고

**더 알아보기:**

* [PDF 문서에 워터마크 추가](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)

### 예

PDF 문서에 이미지 주석 워터마크를 추가합니다.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf", loadOptions))
{
    using (ImageWatermark watermark = new ImageWatermark(@"D:\icon.png"))
    {
        PdfAnnotationWatermarkOptions options = new PdfAnnotationWatermarkOptions();
        options.PageIndex = -1; // 기본값 - 모든 페이지

        watermarker.Add(watermark, options);
    }

    watermarker.Save();
}
```

### 또한보십시오

* class [PdfWatermarkOptions](../pdfwatermarkoptions)
* 네임스페이스 [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* 집회 [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->