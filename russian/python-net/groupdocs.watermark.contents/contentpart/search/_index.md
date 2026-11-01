---
title: "метод search"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Находит возможные водяные знаки в соответствии с указанными критериями поиска."
type: docs
url: /ru/python-net/groupdocs.watermark.contents/contentpart/search/
is_root: false
weight: 1030
---


## search {#search_criteria}

Находит возможные водяные знаки согласно указанным критериям поиска. Поиск выполняется по объектам, перечисленным в [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/).

```python
def search(self, search_criteria):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| search_criteria | `SearchCriteria` | Критерии поиска для использования. |

**Returns:** The collection of the possible watermarks.

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
    print("Found", len(possible), "possible watermark(s)")
```

## search

Находит все возможные водяные знаки в содержимом.

Поиск выполняется в объектах, указанных в [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

```python
def search(self):
    ...
```

**Returns:** Iterable[Watermark]: The collection of the possible watermarks.

### См. также
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)
