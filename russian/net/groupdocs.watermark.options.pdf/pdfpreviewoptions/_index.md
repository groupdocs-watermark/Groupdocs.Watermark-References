---
title: "PdfPreviewOptions"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Предоставляет параметры для установки требований и делегатов потоков при генерации предварительного просмотра PDF‑документа."
type: docs
weight: 1960
url: /ru/net/groupdocs.watermark.options.pdf/pdfpreviewoptions/
---
## PdfPreviewOptions class

Предоставляет параметры для установки требований и делегатов потоков при генерации предварительного просмотра PDF‑документа.

```csharp
public class PdfPreviewOptions : PreviewOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PdfPreviewOptions](pdfpreviewoptions#constructor)(CreatePageStream) | Инициализирует новый экземпляр класса [`PdfPreviewOptions`](../pdfpreviewoptions), вызывая закрытие выходного потока. |
| [PdfPreviewOptions](pdfpreviewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | Инициализирует новый экземпляр класса [`PdfPreviewOptions`](../pdfpreviewoptions), при этом выходной поток возвращается клиенту для дальнейшего использования. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | Получает или задаёт экземпляр делегата создания потока страницы. |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | Получает или задаёт высоту предварительного просмотра страницы. |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | Получает или задаёт массив номеров страниц для генерации предварительных просмотров. |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | Получает или задает формат изображения предварительного просмотра. |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | Получает или задает экземпляр делегата завершения предварительного просмотра страницы. |
| [Resolution](../../groupdocs.watermark.options.pdf/pdfpreviewoptions/resolution) { get; set; } | Получает или задает разрешение генерируемых изображений в точках на дюйм. |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | Получает или задает ширину предварительного просмотра страницы. |

## Поля

| Имя | Описание |
| --- | --- |
| const [DefaultResolution](../../groupdocs.watermark.options.pdf/pdfpreviewoptions/defaultresolution) | Разрешение по умолчанию в точках на дюйм. |

### См. также

* class [PreviewOptions](../../groupdocs.watermark.options/previewoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
