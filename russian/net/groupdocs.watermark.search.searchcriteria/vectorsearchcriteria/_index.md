---
title: "VectorSearchCriteria"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет критерии, позволяющие фильтровать по цвету водяного знака."
type: docs
weight: 2760
url: /ru/net/groupdocs.watermark.search.searchcriteria/vectorsearchcriteria/
---
## VectorSearchCriteria class

Представляет критерии, позволяющие фильтровать по цвету водяного знака.

```csharp
public class VectorSearchCriteria : SearchCriteria
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [VectorSearchCriteria](vectorsearchcriteria)() | Инициализирует новый экземпляр класса [`VectorSearchCriteria`](../vectorsearchcriteria). |

## Свойства

| Имя | Описание |
| --- | --- |
| [VectorColorRange](../../groupdocs.watermark.search.searchcriteria/vectorsearchcriteria/vectorcolorrange) { get; set; } | Получает или задает диапазон цветов, используемых для фильтрации векторных водяных знаков по цвету переднего плана. |

## Методы

| Имя | Описание |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | Объединяет этот [`SearchCriteria`](../searchcriteria) с другими критериями с помощью логического оператора И. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | Отрицает этот [`SearchCriteria`](../searchcriteria). |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | Объединяет этот [`SearchCriteria`](../searchcriteria) с другими критериями с помощью логического оператора ИЛИ. |

### Примечания

**Learn more:**

* [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

### Примеры

Найдите и удалите водяной знак, используя критерий поиска.

```csharp
using (Watermarker watermarker = new Watermarker(@"C:\test.pdf"))
{
    VectorSearchCriteria searchCriteria = new VectorSearchCriteria();
    Color watermarkColor = ColorTranslator.FromHtml("#a9aaae");
    GroupDocs.Watermark.Watermarks.Color fromSystemColor = GroupDocs.Watermark.Watermarks.Color.FromArgb(watermarkColor.A, watermarkColor.R, watermarkColor.G, watermarkColor.B);
    ColorRange criteriaVectorColorRange = new ColorRange(fromSystemColor)
    {
       MinBrightness = 0.1f,
       MaxBrightness = 0.7f
    };
    searchCriteria.VectorColorRange = criteriaVectorColorRange;
    PossibleWatermarkCollection possibleWatermarkCollection = watermarker.Search(searchCriteria);
    possibleWatermarkCollection.Clear();
    watermarker.Save(@"C:\modified_test.pdf");
}
```

### См. также

* class [SearchCriteria](../searchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
