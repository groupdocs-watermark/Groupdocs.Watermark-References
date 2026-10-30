---
title: "ImageThumbnailSearchCriteria"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет критерий поиска для нахождения изображений в содержимом."
type: docs
weight: 2650
url: /ru/net/groupdocs.watermark.search.searchcriteria/imagethumbnailsearchcriteria/
---
## ImageThumbnailSearchCriteria class

Представляет критерий поиска для нахождения изображений в содержимом.

```csharp
public class ImageThumbnailSearchCriteria : ImageSearchCriteria
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ImageThumbnailSearchCriteria](imagethumbnailsearchcriteria#constructor)(Stream) | Создает новый экземпляр класса [`ImageThumbnailSearchCriteria`](../imagethumbnailsearchcriteria) с указанным потоком. |
| [ImageThumbnailSearchCriteria](imagethumbnailsearchcriteria#constructor_1)(string) | Создает новый экземпляр класса [`ImageThumbnailSearchCriteria`](../imagethumbnailsearchcriteria) с указанным путем к файлу. |

## Свойства

| Имя | Описание |
| --- | --- |
| [MaxDifference](../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria/maxdifference) { get; set; } | Получает или задает максимальную допустимую разницу между изображениями. |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | Получает или задает список конкретных номеров страниц |
| [ThumbnailSize](../../groupdocs.watermark.search.searchcriteria/imagethumbnailsearchcriteria/thumbnailsize) { get; set; } | Получает или задает размер миниатюры. |

## Методы

| Имя | Описание |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | Объединяет этот [`SearchCriteria`](../searchcriteria) с другими критериями с помощью логического оператора И. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | Отрицает этот [`SearchCriteria`](../searchcriteria). |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | Объединяет этот [`SearchCriteria`](../searchcriteria) с другими критериями с помощью логического оператора ИЛИ. |

### Примечания

Этот критерий поиска использует бинаризованную миниатюру изображения для вычисления сходства изображений.

### См. также

* class [ImageSearchCriteria](../imagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
