---
title: WordProcessingWatermarkableImage
second_title: Справочник по API GroupDocs.Watermark для .NET
description: Представляет изображение внутри документа Word.
type: docs
weight: 1460
url: /ru/net/groupdocs.watermark.contents.wordprocessing/wordprocessingwatermarkableimage/
---
## WordProcessingWatermarkableImage class

Представляет изображение внутри документа Word.

```csharp
public class WordProcessingWatermarkableImage : WatermarkableImage
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [WordProcessingWatermarkableImage](wordprocessingwatermarkableimage)(byte[]) | Инициализирует новый экземпляр[`WordProcessingWatermarkableImage`](../wordprocessingwatermarkableimage) класс, использующий указанные данные изображения. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Height](../../groupdocs.watermark.contents.image/watermarkableimage/height) { get; } | Получает высоту этого[`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) в пикселях. |
| [Width](../../groupdocs.watermark.contents.image/watermarkableimage/width) { get; } | Получает ширину этого[`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) в пикселях. |

## Методы

| Имя | Описание |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.image/watermarkableimage/add)(Watermark) | Добавляет к этому водяной знак[`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) . Этот метод предполагает, что смещение и размер водяного знака измеряются в пикселях (если они назначены). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Находит все изображения в содержании. Поиск ведется в объектах, указанных в[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Находит изображения по заданным критериям поиска. Поиск ведется в объектах, указанных в[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [GetBytes](../../groupdocs.watermark.contents.image/watermarkableimage/getbytes)() | Получает изображение в виде массива байтов. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Находит все возможные водяные знаки в контенте. Поиск ведется в объектах, указанных в[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Находит возможные водяные знаки по заданным критериям поиска. Поиск ведется в объектах, указанных в[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |

### Смотрите также

* class [WatermarkableImage](../../groupdocs.watermark.contents.image/watermarkableimage)
* пространство имен [GroupDocs.Watermark.Contents.WordProcessing](../../groupdocs.watermark.contents.wordprocessing)
* сборка [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
