---
title: DiagramPreviewOptions
second_title: Справочник по API GroupDocs.Watermark для .NET
description: Предоставляет параметры для установки требований и потока делегатов для предварительного создания документа диаграммы.
type: docs
weight: 1660
url: /ru/net/groupdocs.watermark.options.diagram/diagrampreviewoptions/
---
## DiagramPreviewOptions class

Предоставляет параметры для установки требований и потока делегатов для предварительного создания документа диаграммы.

```csharp
public class DiagramPreviewOptions : PreviewOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DiagramPreviewOptions](diagrampreviewoptions#constructor)(CreatePageStream) | Инициализирует новый экземпляр[`DiagramPreviewOptions`](../diagrampreviewoptions) класс, вызывающий закрытие выходного потока. |
| [DiagramPreviewOptions](diagrampreviewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | Инициализирует новый экземпляр[`DiagramPreviewOptions`](../diagrampreviewoptions) класс, вызывающий возврат выходного потока клиенту для дальнейшего использования. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | Получает или задает экземпляр делегата создания потока страниц. |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | Получает или задает высоту предварительного просмотра страницы. |
| [HighQualityRendering](../../groupdocs.watermark.options.diagram/diagrampreviewoptions/highqualityrendering) { get; set; } | Получает или устанавливает флаг высококачественного рендеринга. |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | Получает или задает массив номеров страниц для создания превью. |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | Получает или задает формат изображения предварительного просмотра. |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | Получает или задает экземпляр делегата завершения предварительного просмотра страницы. |
| [Resolution](../../groupdocs.watermark.options.diagram/diagrampreviewoptions/resolution) { get; set; } | Получает или задает разрешение сгенерированных изображений в точках на дюйм. |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | Получает или задает ширину предварительного просмотра страницы. |

## Поля

| Имя | Описание |
| --- | --- |
| const [DefaultResolution](../../groupdocs.watermark.options.diagram/diagrampreviewoptions/defaultresolution) | Разрешение по умолчанию в точках на дюйм. |

### Смотрите также

* class [PreviewOptions](../../groupdocs.watermark.options/previewoptions)
* пространство имен [GroupDocs.Watermark.Options.Diagram](../../groupdocs.watermark.options.diagram)
* сборка [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
