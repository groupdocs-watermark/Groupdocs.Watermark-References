---
title: "__init__ конструктор"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Инициализирует новый экземпляр класса PagesSetup."
type: docs
url: /ru/python-net/groupdocs.watermark.watermarks/pagessetup/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует новый экземпляр класса [`PagesSetup`](/watermark/python-net/groupdocs.watermark.watermarks/pagessetup/).

```python
def __init__(self):
    ...
```

## __init__ {#all_pages-first_page-last_page-odd_pages-even_pages-pages-page_number}

Инициализирует новый экземпляр PagesSetup с указанными параметрами.

```python
def __init__(self, all_pages, first_page, last_page, odd_pages, even_pages, pages, page_number):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| all_pages | `bool` | Включать ли все страницы. |
| first_page | `bool` | Включать ли первую страницу. |
| last_page | `bool` | Включать ли последнюю страницу. |
| odd_pages | `bool` | Включать ли нечётные страницы. |
| even_pages | `bool` | Включать ли чётные страницы. |
| pages | `List[int]` | Список конкретных номеров страниц для включения. |
| page_number | `Optional[int]` | Индекс текущей страницы. |

### См. также
* class [`PagesSetup`](/watermark/python-net/groupdocs.watermark.watermarks/pagessetup/)
