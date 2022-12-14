---
title: Content
second_title: Справочник по API GroupDocs.Watermark для .NET
description: Представляет содержимое на которое можно поместить водяной знак.
type: docs
weight: 120
url: /ru/net/groupdocs.watermark.contents/content/
---
## Content class

Представляет содержимое, на которое можно поместить водяной знак.

```csharp
public abstract class Content : ContentPart, IDisposable
```

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Удаляет текущий экземпляр. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Находит все изображения в содержании. Поиск ведется в объектах, указанных в[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Находит изображения по заданным критериям поиска. Поиск ведется в объектах, указанных в[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Находит все возможные водяные знаки в контенте. Поиск ведется в объектах, указанных в[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Находит возможные водяные знаки по заданным критериям поиска. Поиск ведется в объектах, указанных в[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |

### Смотрите также

* class [ContentPart](../contentpart)
* пространство имен [GroupDocs.Watermark.Contents](../../groupdocs.watermark.contents)
* сборка [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
