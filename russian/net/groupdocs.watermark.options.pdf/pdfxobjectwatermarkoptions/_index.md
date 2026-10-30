---
title: "PdfXObjectWatermarkOptions"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет параметры добавления водяного знака при добавлении XObject‑водяного знака в PDF‑документ."
type: docs
weight: 1990
url: /ru/net/groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/
---
## PdfXObjectWatermarkOptions class

Представляет параметры добавления водяного знака при добавлении XObject‑водяного знака в PDF‑документ.

```csharp
public sealed class PdfXObjectWatermarkOptions : PdfWatermarkOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfXObjectWatermarkOptions](pdfxobjectwatermarkoptions)() | Инициализирует новый экземпляр класса [`PdfXObjectWatermarkOptions`](../pdfxobjectwatermarkoptions). |

## Свойства

| Имя | Описание |
| --- | --- |
| [PageIndex](../../groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/pageindex) { get; set; } | Получает или задает индекс страницы, к которой будет добавлен водяной знак. |

### Примечания

**Learn more:**

* [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)

### Примеры

Добавьте водяной знак на определённую страницу PDF‑документа.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\doc.pdf", loadOptions))
using (ImageWatermark watermark = new ImageWatermark(@"C:\watermark.png"))
{
    PdfXObjectWatermarkOptions options = new PdfXObjectWatermarkOptions();
    options.PageIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### См. также

* class [PdfWatermarkOptions](../pdfwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
