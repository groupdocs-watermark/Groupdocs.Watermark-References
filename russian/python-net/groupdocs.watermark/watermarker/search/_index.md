---
title: "метод search"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Ищет все возможные водяные знаки в документе."
type: docs
url: /ru/python-net/groupdocs.watermark/watermarker/search/
is_root: false
weight: 1190
---


## search

Ищет все возможные водяные знаки в документе.

Поиск выполняется в объектах, указанных в [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

Узнайте больше о поиске водяных знаков https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def search(self):
    ...
```

**Returns:** The collection of possible watermarks.

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def search_by_text():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_text()
```

## search {#search_criteria}

Ищет возможные водяные знаки в соответствии с указанными критериями поиска.

Поиск выполняется в объектах, указанных в [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

Узнайте больше о поиске водяных знаков: https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def search(self, search_criteria):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| search_criteria | `SearchCriteria` | Критерии поиска для использования. |

**Returns:** The collection of possible watermarks.

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def search_by_text():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_text()
```

### См. также
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
