---
title: "ImageDctHashSearchCriteria"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет критерий поиска для нахождения изображений в документе."
type: docs
weight: 2630
url: /ru/net/groupdocs.watermark.search.searchcriteria/imagedcthashsearchcriteria/
---
## ImageDctHashSearchCriteria class

Представляет критерий поиска для нахождения изображений в документе.

```csharp
public class ImageDctHashSearchCriteria : ImageSearchCriteria
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ImageDctHashSearchCriteria](imagedcthashsearchcriteria#constructor)(Stream) | Создаёт новый экземпляр класса [`ImageDctHashSearchCriteria`](../imagedcthashsearchcriteria) с указанным потоком. |
| [ImageDctHashSearchCriteria](imagedcthashsearchcriteria#constructor_1)(string) | Создаёт новый экземпляр класса [`ImageDctHashSearchCriteria`](../imagedcthashsearchcriteria) с указанным путём к файлу. |

## Свойства

| Имя | Описание |
| --- | --- |
| [MaxDifference](../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria/maxdifference) { get; set; } | Получает или задает максимальную допустимую разницу между изображениями. |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | Получает или задает список конкретных номеров страниц |

## Методы

| Имя | Описание |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | Объединяет этот [`SearchCriteria`](../searchcriteria) с другими критериями с помощью логического оператора И. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | Отрицает этот [`SearchCriteria`](../searchcriteria). |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | Объединяет этот [`SearchCriteria`](../searchcriteria) с другими критериями с помощью логического оператора ИЛИ. |

### Примечания

Этот критерий поиска использует основанный на DCT перцептивный хеш изображения для вычисления сходства изображений. **Learn more:**

* [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

### Примеры

Искать изображения во вложенных файлах (pdf).

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    PdfSearchableObjects = PdfSearchableObjects.All
};
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf", loadOptions, settings))
{
    // Укажите образец изображения для сравнения с изображениями документа
    ImageSearchCriteria criteria = new ImageDctHashSearchCriteria(@"D:\sample.png");
    // Искать похожие изображения
    PossibleWatermarkCollection possibleWatermarks = watermarker.Search(criteria);
    // Удалить или изменить найденные водяные знаки изображений
    // ...
}
```

### См. также

* class [ImageSearchCriteria](../imagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
