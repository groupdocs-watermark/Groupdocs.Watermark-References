---
title: PdfPage
second_title: Справочник по API GroupDocs.Watermark для .NET
description: Представляет страницу документа PDF.
type: docs
weight: 660
url: /ru/net/groupdocs.watermark.contents.pdf/pdfpage/
---
## PdfPage class

Представляет страницу документа PDF.

```csharp
public class PdfPage : ContentPart
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Annotations](../../groupdocs.watermark.contents.pdf/pdfpage/annotations) { get; } | Получает коллекцию всех аннотаций этого[`PdfPage`](../pdfpage) . |
| [Artifacts](../../groupdocs.watermark.contents.pdf/pdfpage/artifacts) { get; } | Получает коллекцию всех артефактов этого[`PdfPage`](../pdfpage) . |
| [Height](../../groupdocs.watermark.contents.pdf/pdfpage/height) { get; } | Получает высоту этого[`PdfPage`](../pdfpage)в пунктах. |
| [Width](../../groupdocs.watermark.contents.pdf/pdfpage/width) { get; } | Получает ширину этого[`PdfPage`](../pdfpage)в пунктах. |
| [XObjects](../../groupdocs.watermark.contents.pdf/pdfpage/xobjects) { get; } | Получает коллекцию всех XObject этого[`PdfPage`](../pdfpage) . |

## Методы

| Имя | Описание |
| --- | --- |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Находит все изображения в содержании. Поиск ведется в объектах, указанных в[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Находит изображения по заданным критериям поиска. Поиск ведется в объектах, указанных в[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| virtual [Rasterize](../../groupdocs.watermark.contents.pdf/pdfpage/rasterize)(int, int, PdfImageConversionFormat) | Преобразует содержимое страницы в изображение. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Находит все возможные водяные знаки в контенте. Поиск ведется в объектах, указанных в[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Находит возможные водяные знаки по заданным критериям поиска. Поиск ведется в объектах, указанных в[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |

### Смотрите также

* class [ContentPart](../../groupdocs.watermark.contents/contentpart)
* пространство имен [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* сборка [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->