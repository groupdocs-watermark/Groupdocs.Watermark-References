---
title: "PresentationBaseSlide"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Предоставляет абстрактный базовый класс для слайдов всех типов в документе PowerPoint."
type: docs
weight: 870
url: /ru/net/groupdocs.watermark.contents.presentation/presentationbaseslide/
---
## PresentationBaseSlide class

Предоставляет абстрактный базовый класс для слайдов всех типов в документе PowerPoint.

```csharp
public abstract class PresentationBaseSlide : ContentPart
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Charts](../../groupdocs.watermark.contents.presentation/presentationbaseslide/charts) { get; } | Получает коллекцию всех диаграмм в презентации. |
| [ImageFillFormat](../../groupdocs.watermark.contents.presentation/presentationbaseslide/imagefillformat) { get; } | Получает настройки формата заливки изображением презентации. |
| [Shapes](../../groupdocs.watermark.contents.presentation/presentationbaseslide/shapes) { get; } | Получает коллекцию всех фигур презентации. |

## Методы

| Имя | Описание |
| --- | --- |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Находит все изображения в контенте. Поиск выполняется в объектах, указанных в [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Находит изображения согласно указанным критериям поиска. Поиск выполняется в объектах, указанных в [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Находит все возможные водяные знаки в контенте. Поиск выполняется в объектах, указанных в [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Находит возможные водяные знаки в соответствии с указанными критериями поиска. Поиск выполняется в объектах, указанных в [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### См. также

* class [ContentPart](../../groupdocs.watermark.contents/contentpart)
* namespace [GroupDocs.Watermark.Contents.Presentation](../../groupdocs.watermark.contents.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
