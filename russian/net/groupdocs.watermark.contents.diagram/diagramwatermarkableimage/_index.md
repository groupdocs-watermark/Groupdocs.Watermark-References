---
title: "DiagramWatermarkableImage"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет изображение внутри документа Visio."
type: docs
weight: 290
url: /ru/net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/
---
## DiagramWatermarkableImage class

Представляет изображение внутри документа Visio.

```csharp
public class DiagramWatermarkableImage : WatermarkableImage
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DiagramWatermarkableImage](diagramwatermarkableimage)(byte[]) | Инициализирует новый экземпляр класса [`DiagramWatermarkableImage`](../diagramwatermarkableimage) с использованием указанных данных изображения. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Height](../../groupdocs.watermark.contents.image/watermarkableimage/height) { get; } | Получает высоту этого [`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) в пикселях. |
| [Width](../../groupdocs.watermark.contents.image/watermarkableimage/width) { get; } | Получает ширину этого [`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) в пикселях. |

## Методы

| Имя | Описание |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.image/watermarkableimage/add)(Watermark) | Добавляет водяной знак к этому [`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage). Этот метод предполагает, что смещение и размер водяного знака измеряются в пикселях (если они заданы). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Находит все изображения в контенте. Поиск выполняется в объектах, указанных в [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Находит изображения согласно указанным критериям поиска. Поиск выполняется в объектах, указанных в [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [GetBytes](../../groupdocs.watermark.contents.image/watermarkableimage/getbytes)() | Получает изображение в виде массива байтов. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Находит все возможные водяные знаки в контенте. Поиск выполняется в объектах, указанных в [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Находит возможные водяные знаки в соответствии с указанными критериями поиска. Поиск выполняется в объектах, указанных в [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### См. также

* class [WatermarkableImage](../../groupdocs.watermark.contents.image/watermarkableimage)
* namespace [GroupDocs.Watermark.Contents.Diagram](../../groupdocs.watermark.contents.diagram)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
