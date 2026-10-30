---
title: "PdfPage"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет страницу pdf документа."
type: docs
weight: 730
url: /ru/net/groupdocs.watermark.contents.pdf/pdfpage/
---
## PdfPage class

Представляет страницу pdf документа.

```csharp
public class PdfPage : ContentPart
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Annotations](../../groupdocs.watermark.contents.pdf/pdfpage/annotations) { get; } | Получает коллекцию всех аннотаций этого [`PdfPage`](../pdfpage). |
| [Artifacts](../../groupdocs.watermark.contents.pdf/pdfpage/artifacts) { get; } | Получает коллекцию всех артефактов этого [`PdfPage`](../pdfpage). |
| [Height](../../groupdocs.watermark.contents.pdf/pdfpage/height) { get; } | Получает высоту этого [`PdfPage`](../pdfpage) в пунктах. |
| [Width](../../groupdocs.watermark.contents.pdf/pdfpage/width) { get; } | Получает ширину этого [`PdfPage`](../pdfpage) в пунктах. |
| [XObjects](../../groupdocs.watermark.contents.pdf/pdfpage/xobjects) { get; } | Получает коллекцию всех XObject этого [`PdfPage`](../pdfpage). |

## Методы

| Имя | Описание |
| --- | --- |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Находит все изображения в контенте. Поиск выполняется в объектах, указанных в [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Находит изображения согласно указанным критериям поиска. Поиск выполняется в объектах, указанных в [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| virtual [Rasterize](../../groupdocs.watermark.contents.pdf/pdfpage/rasterize)(int, int, PdfImageConversionFormat) | Преобразует содержимое страницы в изображение. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Находит все возможные водяные знаки в контенте. Поиск выполняется в объектах, указанных в [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Находит возможные водяные знаки в соответствии с указанными критериями поиска. Поиск выполняется в объектах, указанных в [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### См. также

* class [ContentPart](../../groupdocs.watermark.contents/contentpart)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
