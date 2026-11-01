---
title: "Класс VectorSearchCriteria"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Представляет критерии, позволяющие фильтровать по цвету водяного знака."
type: docs
url: /ru/python-net/groupdocs.watermark.search.search_criteria/vectorsearchcriteria/
is_root: false
weight: 170
---


## VectorSearchCriteria class

Представляет критерии, позволяющие фильтровать по цвету водяного знака.

Узнать больше:
- https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

Тип VectorSearchCriteria раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/vectorsearchcriteria/__init__/) | Инициализирует новый экземпляр [`VectorSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/vectorsearchcriteria/). |

### Методы
| Метод | Описание |
| :- | :- |
| [and_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/) | Объединяет этот SearchCriteria с другими критериями с помощью логического оператора И. (унаследовано от [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [and_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_search_criteria/) | (унаследовано от [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [not_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/) | Отрицает этот SearchCriteria. (унаследовано от [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [or_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/) | Объединяет этот SearchCriteria с другими критериями с помощью логического оператора ИЛИ. (унаследовано от [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [or_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_search_criteria/) | (унаследовано от [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |

### Свойства
| Свойство | Описание |
| :- | :- |
| [vector_color_range](/watermark/python-net/groupdocs.watermark.search.search_criteria/vectorsearchcriteria/vector_color_range/) | Диапазон цветов, используемых для фильтрации векторных водяных знаков по цвету переднего плана. |

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import VectorSearchCriteria, ColorRange
from groupdocs.watermark.watermarks import Color

with Watermarker("./document.pdf") as watermarker:
    search_criteria = VectorSearchCriteria()
    watermark_color = Color.from_argb(255, 169, 170, 174)  # #a9aaae
    color_range = ColorRange(watermark_color)
    color_range.min_brightness = 0.1
    color_range.max_brightness = 0.7
    search_criteria.vector_color_range = color_range

    possible_watermarks = watermarker.search(search_criteria)
    possible_watermarks.clear()
    watermarker.save("./output.pdf")
```

### См. также
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
