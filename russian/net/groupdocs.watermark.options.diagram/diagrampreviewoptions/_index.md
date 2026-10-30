---
title: "DiagramPreviewOptions"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Предоставляет параметры для установки требований и делегатов потоков при генерации предварительного просмотра документа Diagram."
type: docs
weight: 1730
url: /ru/net/groupdocs.watermark.options.diagram/diagrampreviewoptions/
---
## DiagramPreviewOptions class

Предоставляет параметры для установки требований и делегатов потоков при генерации предварительного просмотра документа Diagram.

```csharp
public class DiagramPreviewOptions : PreviewOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DiagramPreviewOptions](diagrampreviewoptions#constructor)(CreatePageStream) | Инициализирует новый экземпляр класса [`DiagramPreviewOptions`](../diagrampreviewoptions), закрывая выходной поток. |
| [DiagramPreviewOptions](diagrampreviewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | Инициализирует новый экземпляр класса [`DiagramPreviewOptions`](../diagrampreviewoptions), возвращая выходной поток клиенту для дальнейшего использования. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | Получает или задаёт экземпляр делегата создания потока страницы. |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | Получает или задаёт высоту предварительного просмотра страницы. |
| [HighQualityRendering](../../groupdocs.watermark.options.diagram/diagrampreviewoptions/highqualityrendering) { get; set; } | Получает или задает флаг высокого качества рендеринга. |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | Получает или задаёт массив номеров страниц для генерации предварительных просмотров. |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | Получает или задает формат изображения предварительного просмотра. |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | Получает или задает экземпляр делегата завершения предварительного просмотра страницы. |
| [Resolution](../../groupdocs.watermark.options.diagram/diagrampreviewoptions/resolution) { get; set; } | Получает или задает разрешение генерируемых изображений в точках на дюйм. |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | Получает или задает ширину предварительного просмотра страницы. |

## Поля

| Имя | Описание |
| --- | --- |
| const [DefaultResolution](../../groupdocs.watermark.options.diagram/diagrampreviewoptions/defaultresolution) | Разрешение по умолчанию в точках на дюйм. |

### См. также

* class [PreviewOptions](../../groupdocs.watermark.options/previewoptions)
* namespace [GroupDocs.Watermark.Options.Diagram](../../groupdocs.watermark.options.diagram)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
