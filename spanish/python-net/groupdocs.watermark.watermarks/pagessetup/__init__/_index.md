---
title: "__init__ constructor"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Inicializa una nueva instancia de la clase PagesSetup."
type: docs
url: /es/python-net/groupdocs.watermark.watermarks/pagessetup/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una nueva instancia de la clase [`PagesSetup`](/watermark/python-net/groupdocs.watermark.watermarks/pagessetup/).

```python
def __init__(self):
    ...
```

## __init__ {#all_pages-first_page-last_page-odd_pages-even_pages-pages-page_number}

Inicializa una nueva instancia de PagesSetup con los parámetros especificados.

```python
def __init__(self, all_pages, first_page, last_page, odd_pages, even_pages, pages, page_number):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| all_pages | `bool` | Indica si se incluyen todas las páginas. |
| first_page | `bool` | Indica si se incluye la primera página. |
| last_page | `bool` | Indica si se incluye la última página. |
| odd_pages | `bool` | Indica si se incluyen las páginas impares. |
| even_pages | `bool` | Indica si se incluyen las páginas pares. |
| pages | `List[int]` | La lista de números de página específicos a incluir. |
| page_number | `Optional[int]` | El índice de la página actual. |

### Ver también
* class [`PagesSetup`](/watermark/python-net/groupdocs.watermark.watermarks/pagessetup/)
