---
title: "Содержание"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет содержимое, в котором может быть размещён водяной знак."
type: docs
weight: 150
url: /ru/net/groupdocs.watermark.contents/content/
---
## Content class

Представляет содержимое, в котором может быть размещён водяной знак.

```csharp
public abstract class Content : ContentPart, IDisposable
```

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Освобождает текущий экземпляр. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Находит все изображения в контенте. Поиск выполняется в объектах, указанных в [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Находит изображения согласно указанным критериям поиска. Поиск выполняется в объектах, указанных в [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Находит все возможные водяные знаки в контенте. Поиск выполняется в объектах, указанных в [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Находит возможные водяные знаки в соответствии с указанными критериями поиска. Поиск выполняется в объектах, указанных в [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### См. также

* class [ContentPart](../contentpart)
* namespace [GroupDocs.Watermark.Contents](../../groupdocs.watermark.contents)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
