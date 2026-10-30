---
title: "ImageColorHistogramSearchCriteria"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет критерий поиска для нахождения изображений в содержимом."
type: docs
weight: 2620
url: /ru/net/groupdocs.watermark.search.searchcriteria/imagecolorhistogramsearchcriteria/
---
## ImageColorHistogramSearchCriteria class

Представляет критерий поиска для нахождения изображений в содержимом.

```csharp
public class ImageColorHistogramSearchCriteria : ImageSearchCriteria
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ImageColorHistogramSearchCriteria](imagecolorhistogramsearchcriteria#constructor)(Stream) | Инициализирует новый экземпляр класса [`ImageColorHistogramSearchCriteria`](../imagecolorhistogramsearchcriteria) с указанным потоком. |
| [ImageColorHistogramSearchCriteria](imagecolorhistogramsearchcriteria#constructor_1)(string) | Инициализирует новый экземпляр класса [`ImageColorHistogramSearchCriteria`](../imagecolorhistogramsearchcriteria) с указанным путем к файлу. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BinsCount](../../groupdocs.watermark.search.searchcriteria/imagecolorhistogramsearchcriteria/binscount) { get; set; } | Получает или задает количество корзин, которые будут использоваться для построения цветовых гистограмм. |
| [MaxDifference](../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria/maxdifference) { get; set; } | Получает или задает максимальную допустимую разницу между изображениями. |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | Получает или задает список конкретных номеров страниц |

## Методы

| Имя | Описание |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | Объединяет этот [`SearchCriteria`](../searchcriteria) с другими критериями с помощью логического оператора И. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | Отрицает этот [`SearchCriteria`](../searchcriteria). |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | Объединяет этот [`SearchCriteria`](../searchcriteria) с другими критериями с помощью логического оператора ИЛИ. |

### Примечания

Этот критерий поиска использует цветовые гистограммы изображений для вычисления схожести изображений.

### См. также

* class [ImageSearchCriteria](../imagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
