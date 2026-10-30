---
title: "PdfArtifactWatermarkOptions"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет параметры добавления водяного знака при добавлении артефактного водяного знака в PDF‑документ."
type: docs
weight: 1940
url: /ru/net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/
---
## PdfArtifactWatermarkOptions class

Представляет параметры добавления водяного знака при добавлении артефактного водяного знака в PDF‑документ.

```csharp
public sealed class PdfArtifactWatermarkOptions : PdfWatermarkOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfArtifactWatermarkOptions](pdfartifactwatermarkoptions)() | Инициализирует новый экземпляр класса [`PdfArtifactWatermarkOptions`](../pdfartifactwatermarkoptions). |

## Свойства

| Имя | Описание |
| --- | --- |
| [PageIndex](../../groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/pageindex) { get; set; } | Получает или задает индекс страницы, к которой будет добавлен водяной знак. |

### Примечания

**Learn more:**

* [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)

### Примеры

Добавьте изображение артефакта водяного знака в PDF‑документ.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf", loadOptions))
{
    using (ImageWatermark watermark = new ImageWatermark(@"D:\icon.png"))
    {
        watermark.HorizontalAlignment = HorizontalAlignment.Right;
        watermark.VerticalAlignment = VerticalAlignment.Bottom;

        PdfArtifactWatermarkOptions options = new PdfArtifactWatermarkOptions();
        options.PageIndex = -1; // default - all pages

        watermarker.Add(watermark, options);
        watermarker.Save();
    }
}
```

### См. также

* class [PdfWatermarkOptions](../pdfwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
