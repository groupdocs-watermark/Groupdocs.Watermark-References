---
title: "EmailPreviewOptions"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Предоставляет параметры для установки требований и делегатов потоков при генерации предварительного просмотра документа Email."
type: docs
weight: 1780
url: /ru/net/groupdocs.watermark.options.email/emailpreviewoptions/
---
## EmailPreviewOptions class

Предоставляет параметры для установки требований и делегатов потоков при генерации предварительного просмотра документа Email.

```csharp
public class EmailPreviewOptions : PreviewOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmailPreviewOptions](emailpreviewoptions#constructor)(CreatePageStream) | Инициализирует новый экземпляр класса [`EmailPreviewOptions`](../emailpreviewoptions), закрывающий выходной поток. |
| [EmailPreviewOptions](emailpreviewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | Инициализирует новый экземпляр класса [`EmailPreviewOptions`](../emailpreviewoptions), возвращающий выходной поток клиенту для дальнейшего использования. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | Получает или задаёт экземпляр делегата создания потока страницы. |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | Получает или задаёт высоту предварительного просмотра страницы. |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | Получает или задаёт массив номеров страниц для генерации предварительных просмотров. |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | Получает или задает формат изображения предварительного просмотра. |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | Получает или задает экземпляр делегата завершения предварительного просмотра страницы. |
| [Resolution](../../groupdocs.watermark.options.email/emailpreviewoptions/resolution) { get; set; } | Получает или задает разрешение генерируемых изображений в точках на дюйм. |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | Получает или задает ширину предварительного просмотра страницы. |

## Поля

| Имя | Описание |
| --- | --- |
| const [DefaultResolution](../../groupdocs.watermark.options.email/emailpreviewoptions/defaultresolution) | Разрешение по умолчанию в точках на дюйм. |

### См. также

* class [PreviewOptions](../../groupdocs.watermark.options/previewoptions)
* namespace [GroupDocs.Watermark.Options.Email](../../groupdocs.watermark.options.email)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
