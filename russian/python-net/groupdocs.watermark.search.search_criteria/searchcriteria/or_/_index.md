---
title: "or_ метод"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Объединяет этот SearchCriteria с другими критериями с помощью логического оператора ИЛИ (OR)."
type: docs
url: /ru/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/
is_root: false
weight: 1040
---


## or_ {#other}

Объединяет этот SearchCriteria с другими критериями с помощью логического оператора ИЛИ (OR).

```python
def or_(self, other):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| other | `SearchCriteria` | Критерий поиска для комбинирования. |

**Returns:** SearchCriteria: Combined search criteria.

### Пример

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.search.search_criteria import (
        ImageDctHashSearchCriteria,
        TextSearchCriteria,
    )

    with Watermarker("./document.pdf") as watermarker:
        image_criteria = ImageDctHashSearchCriteria("./logo.png")
        text_criteria = TextSearchCriteria("CONFIDENTIAL")
        combined = image_criteria.or_(text_criteria)
        results = watermarker.search(combined)
        print(f"Found {len(results)} possible watermark(s)")
    ```

### См. также
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
