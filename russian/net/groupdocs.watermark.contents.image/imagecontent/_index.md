---
title: "ImageContent"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет изображение, на которое можно разместить водяной знак."
type: docs
weight: 400
url: /ru/net/groupdocs.watermark.contents.image/imagecontent/
---
## ImageContent class

Представляет изображение, на которое можно разместить водяной знак.

```csharp
public class ImageContent : Content
```

## Свойства

| Имя | Описание |
| --- | --- |
| virtual [Height](../../groupdocs.watermark.contents.image/imagecontent/height) { get; } | Получает высоту этого [`ImageContent`](../imagecontent) в пикселях. |
| virtual [Width](../../groupdocs.watermark.contents.image/imagecontent/width) { get; } | Получает ширину этого [`ImageContent`](../imagecontent) в пикселях. |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Освобождает текущий экземпляр. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Находит все изображения в контенте. Поиск выполняется в объектах, указанных в [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Находит изображения согласно указанным критериям поиска. Поиск выполняется в объектах, указанных в [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Находит все возможные водяные знаки в контенте. Поиск выполняется в объектах, указанных в [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Находит возможные водяные знаки в соответствии с указанными критериями поиска. Поиск выполняется в объектах, указанных в [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Примечания

**Learn more:**

* [Add watermarks to images](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images)

### См. также

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Image](../../groupdocs.watermark.contents.image)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
