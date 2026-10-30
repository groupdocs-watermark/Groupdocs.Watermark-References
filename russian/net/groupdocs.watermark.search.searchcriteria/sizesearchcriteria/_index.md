---
title: "SizeSearchCriteria"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет критерии, позволяющие фильтровать по размеру водяного знака."
type: docs
weight: 2730
url: /ru/net/groupdocs.watermark.search.searchcriteria/sizesearchcriteria/
---
## SizeSearchCriteria class

Представляет критерии, позволяющие фильтровать по размеру водяного знака.

```csharp
public class SizeSearchCriteria : SearchCriteria
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SizeSearchCriteria](sizesearchcriteria)(Dimension, double, double) | Инициализирует новый экземпляр класса [`SizeSearchCriteria`](../sizesearchcriteria) с указанным измерением, начальным значением и конечным значением. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Dimension](../../groupdocs.watermark.search.searchcriteria/sizesearchcriteria/dimension) { get; } | Получает измерение водяного знака для поиска. |
| [Maximum](../../groupdocs.watermark.search.searchcriteria/sizesearchcriteria/maximum) { get; } | Получает конечное значение. |
| [Minimum](../../groupdocs.watermark.search.searchcriteria/sizesearchcriteria/minimum) { get; } | Получает начальное значение. |

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
using (Watermarker watermarker = new Watermarker(@"C:\test.some_ext"))
{
    SizeSearchCriteria widthRange = new SizeSearchCriteria(Dimension.Width, 50, 100);
    RotateAngleSearchCriteria rotateAngle = new RotateAngleSearchCriteria(0, 45);
    TextSearchCriteria textCriteria = new TextSearchCriteria(new Regex("^Test watermark$"));
    PossibleWatermarkCollection watermarks = watermarker.Search(textCriteria.And(widthRange.Or(rotateAngle)));
    watermarks.Clear();
    watermarker.Save();
}
```

### См. также

* class [SearchCriteria](../searchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
