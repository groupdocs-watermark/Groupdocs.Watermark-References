---
title: "Класс RotateAngleSearchCriteria"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Представляет критерии, позволяющие фильтровать по углу поворота водяного знака."
type: docs
url: /ru/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/
is_root: false
weight: 120
---


## RotateAngleSearchCriteria class

Представляет критерии, позволяющие фильтровать по углу поворота водяного знака.

Узнать больше:
- Searching watermarks (https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

Тип RotateAngleSearchCriteria раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/__init__/#min_angle-max_angle) | Инициализирует новый RotateAngleSearchCriteria с начальным и конечным углом. |

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
| [maximum_angle](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/maximum_angle/) | Конечный угол в градусах. |
| [minimum_angle](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/minimum_angle/) | Начальный угол в градусах. |

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import RotateAngleSearchCriteria

def search_by_angle():
    with Watermarker("./document.pdf") as watermarker:
        angle_criteria = RotateAngleSearchCriteria(30, 60)
        possible = watermarker.search(angle_criteria)
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_angle()
```

### Guides
Руководства задач, использующие `RotateAngleSearchCriteria`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### См. также
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
