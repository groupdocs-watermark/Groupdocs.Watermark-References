---
title: "PresentationPreviewOptions"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Предоставляет параметры для установки требований и делегатов потоков при генерации предварительного просмотра документа Presentation."
type: docs
weight: 2030
url: /ru/net/groupdocs.watermark.options.presentation/presentationpreviewoptions/
---
## PresentationPreviewOptions class

Предоставляет параметры для установки требований и делегатов потоков при генерации предварительного просмотра документа Presentation.

```csharp
public class PresentationPreviewOptions : PreviewOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PresentationPreviewOptions](presentationpreviewoptions#constructor)(CreatePageStream) | Инициализирует новый экземпляр класса [`PresentationPreviewOptions`](../presentationpreviewoptions), закрывая поток вывода. |
| [PresentationPreviewOptions](presentationpreviewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | Инициализирует новый экземпляр класса [`PresentationPreviewOptions`](../presentationpreviewoptions), возвращая поток вывода клиенту для дальнейшего использования. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | Получает или задаёт экземпляр делегата создания потока страницы. |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | Получает или задаёт высоту предварительного просмотра страницы. |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | Получает или задаёт массив номеров страниц для генерации предварительных просмотров. |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | Получает или задает формат изображения предварительного просмотра. |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | Получает или задает экземпляр делегата завершения предварительного просмотра страницы. |
| [Resolution](../../groupdocs.watermark.options.presentation/presentationpreviewoptions/resolution) { get; set; } | Получает или задает разрешение генерируемых изображений в точках на дюйм. |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | Получает или задает ширину предварительного просмотра страницы. |

## Поля

| Имя | Описание |
| --- | --- |
| const [DefaultResolution](../../groupdocs.watermark.options.presentation/presentationpreviewoptions/defaultresolution) | Разрешение по умолчанию в точках на дюйм. |

### См. также

* class [PreviewOptions](../../groupdocs.watermark.options/previewoptions)
* namespace [GroupDocs.Watermark.Options.Presentation](../../groupdocs.watermark.options.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
