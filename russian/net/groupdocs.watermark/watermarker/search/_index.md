---
title: Search
second_title: Справочник по API GroupDocs.Watermark для .NET
description: Поиск всех возможных водяных знаков в документе.
type: docs
weight: 110
url: /ru/net/groupdocs.watermark/watermarker/search/
---
## Search() {#search}

Поиск всех возможных водяных знаков в документе.

```csharp
public PossibleWatermarkCollection Search()
```

### Возвращаемое значение

Коллекция возможных водяных знаков.

### Примечания

Поиск ведется по объектам, указанным в[`SearchableObjects`](../searchableobjects).

Узнайте больше о поиске водяных знаков [Поиск водяных знаков](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Примеры

Подсчет возможных водяных знаков в документе любого поддерживаемого типа.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    PossibleWatermarkCollection watermarks = watermarker.Search();
    Console.WrileLine(watermarks.Count);
}
```

### Смотрите также

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [Watermarker](../../watermarker)
* пространство имен [GroupDocs.Watermark](../../watermarker)
* сборка [GroupDocs.Watermark](../../../)

---

## Search(SearchCriteria) {#search_1}

Ищет возможные водяные знаки в соответствии с указанными критериями поиска.

```csharp
public PossibleWatermarkCollection Search(SearchCriteria searchCriteria)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| searchCriteria | SearchCriteria | Используемые критерии поиска. |

### Возвращаемое значение

Коллекция возможных водяных знаков.

### Примечания

Поиск ведется по объектам, указанным в[`SearchableObjects`](../searchableobjects).

Узнайте больше о поиске водяных знаков [Поиск водяных знаков](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Примеры

Найти и удалить все возможные водяные знаки, содержащие определенный текст или изображение, из документа любого поддерживаемого типа.

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

### Смотрите также

* class [PossibleWatermarkCollection](../../../groupdocs.watermark.search/possiblewatermarkcollection)
* class [SearchCriteria](../../../groupdocs.watermark.search.searchcriteria/searchcriteria)
* class [Watermarker](../../watermarker)
* пространство имен [GroupDocs.Watermark](../../watermarker)
* сборка [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
