---
title: "Search"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Ищет все возможные водяные знаки в документе."
type: docs
weight: 110
url: /ru/net/groupdocs.watermark/watermarker/search/
---
## Search() {#search}

Ищет все возможные водяные знаки в документе.

```csharp
public PossibleWatermarkCollection Search()
```

### Возвращаемое значение

Коллекция возможных водяных знаков.

### Примечания

Поиск проводится в объектах, указанных в [`SearchableObjects`](../searchableobjects).

Узнайте больше о поиске водяных знаков [Поиск водяных знаков](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Примеры

Подсчитать количество возможных водяных знаков в документе любого поддерживаемого типа.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    PossibleWatermarkCollection watermarks = watermarker.Search();
    Console.WrileLine(watermarks.Count);
}
```

### См. также

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Search(SearchCriteria) {#search_1}

Ищет возможные водяные знаки согласно указанным критериям поиска.

```csharp
public PossibleWatermarkCollection Search(SearchCriteria searchCriteria)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| searchCriteria | SearchCriteria | Критерии поиска для использования. |

### Возвращаемое значение

Коллекция возможных водяных знаков.

### Примечания

Поиск проводится в объектах, указанных в [`SearchableObjects`](../searchableobjects).

Узнайте больше о поиске водяных знаков [Поиск водяных знаков](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Примеры

Найти и удалить все возможные водяные знаки, содержащие определённый текст или изображение, из документа любого поддерживаемого типа.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria(@"D:\logo.png");
    Regex regex = new Regex(@"^Company\sName$", RegexOptions.IgnoreCase);
    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(regex);
    PossibleWatermarkCollection watermarks = watermarker.Search(textSearchCriteria.Or(imageSearchCriteria));
    watermarks.Clear();
    watermarker.Save(@"D:\output.doc");
}
```

### См. также

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [SearchCriteria](../../../groupdocs.watermark.search.searchcriteria/searchcriteria)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
