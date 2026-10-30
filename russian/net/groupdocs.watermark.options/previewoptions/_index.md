---
title: "PreviewOptions"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Предоставляет параметры для установки требований и делегатов потоков для генерации предварительного просмотра."
type: docs
weight: 2140
url: /ru/net/groupdocs.watermark.options/previewoptions/
---
## PreviewOptions class

Предоставляет параметры для установки требований и делегатов потоков для генерации предварительного просмотра.

```csharp
public class PreviewOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PreviewOptions](previewoptions#constructor)(CreatePageStream) | Инициализирует новый экземпляр класса [`PreviewOptions`](../previewoptions), закрывающий выходной поток. |
| [PreviewOptions](previewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | Инициализирует новый экземпляр класса [`PreviewOptions`](../previewoptions), возвращающий выходной поток клиенту для дальнейшего использования. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | Получает или задаёт экземпляр делегата создания потока страницы. |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | Получает или задаёт высоту предварительного просмотра страницы. |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | Получает или задаёт массив номеров страниц для генерации предварительных просмотров. |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | Получает или задает формат изображения предварительного просмотра. |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | Получает или задает экземпляр делегата завершения предварительного просмотра страницы. |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | Получает или задает ширину предварительного просмотра страницы. |

### См. также

* namespace [GroupDocs.Watermark.Options](../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
