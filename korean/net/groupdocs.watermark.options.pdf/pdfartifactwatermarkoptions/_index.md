---
title: PdfArtifactWatermarkOptions
second_title: .NET API 참조용 GroupDocs.Watermark
description: PDF 문서에 아티팩트 워터마크를 추가할 때 워터마크 추가 옵션을 나타냅니다.
type: docs
weight: 1870
url: /ko/net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/
---
## PdfArtifactWatermarkOptions class

PDF 문서에 아티팩트 워터마크를 추가할 때 워터마크 추가 옵션을 나타냅니다.

```csharp
public sealed class PdfArtifactWatermarkOptions : PdfWatermarkOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfArtifactWatermarkOptions](pdfartifactwatermarkoptions)() | 의 새 인스턴스를 초기화합니다.[`PdfArtifactWatermarkOptions`](../pdfartifactwatermarkoptions) 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [PageIndex](../../groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/pageindex) { get; set; } | 워터마크를 추가할 페이지 인덱스를 가져오거나 설정합니다. |

### 비고

**더 알아보기:**

* [PDF 문서에 워터마크 추가](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)

### 예

PDF 문서에 이미지 아티팩트 워터마크를 추가합니다.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf", loadOptions))
{
    using (ImageWatermark watermark = new ImageWatermark(@"D:\icon.png"))
    {
        watermark.HorizontalAlignment = HorizontalAlignment.Right;
        watermark.VerticalAlignment = VerticalAlignment.Bottom;

        PdfArtifactWatermarkOptions options = new PdfArtifactWatermarkOptions();
        options.PageIndex = -1; // 기본값 - 모든 페이지

        watermarker.Add(watermark, options);
        watermarker.Save();
    }
}
```

### 또한보십시오

* class [PdfWatermarkOptions](../pdfwatermarkoptions)
* 네임스페이스 [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* 집회 [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
