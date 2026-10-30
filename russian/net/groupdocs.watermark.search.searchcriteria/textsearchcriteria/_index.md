---
title: "TextSearchCriteria"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет критерии, позволяющие фильтровать по тексту водяного знака."
type: docs
weight: 2750
url: /ru/net/groupdocs.watermark.search.searchcriteria/textsearchcriteria/
---
## TextSearchCriteria class

Представляет критерии, позволяющие фильтровать по тексту водяного знака.

```csharp
public class TextSearchCriteria : PageSearchCriteria
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextSearchCriteria](textsearchcriteria#constructor_2)(Regex) | Создает новый экземпляр класса [`TextSearchCriteria`](../textsearchcriteria) с указанным регулярным выражением. |
| [TextSearchCriteria](textsearchcriteria#constructor)(string) | Создает новый экземпляр класса [`TextSearchCriteria`](../textsearchcriteria) со строкой поиска. |
| [TextSearchCriteria](textsearchcriteria#constructor_1)(string, bool) | Создает новый экземпляр класса [`TextSearchCriteria`](../textsearchcriteria) со строкой поиска и флагом сравнения. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | Получает или задает список конкретных номеров страниц |
| [Pattern](../../groupdocs.watermark.search.searchcriteria/textsearchcriteria/pattern) { get; } | Возвращает шаблон поиска. |
| [SkipUnreadableCharacters](../../groupdocs.watermark.search.searchcriteria/textsearchcriteria/skipunreadablecharacters) { get; set; } | Получает или задает значение, указывающее, что нечитаемые символы будут пропускаться при сравнении строк. |

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

* class [PageSearchCriteria](../pagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
