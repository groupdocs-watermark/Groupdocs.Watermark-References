---
title: "__init__ constructeur"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Initialise une nouvelle instance de la classe PagesSetup."
type: docs
url: /fr/python-net/groupdocs.watermark.watermarks/pagessetup/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une nouvelle instance de la classe [`PagesSetup`](/watermark/python-net/groupdocs.watermark.watermarks/pagessetup/).

```python
def __init__(self):
    ...
```

## __init__ {#all_pages-first_page-last_page-odd_pages-even_pages-pages-page_number}

Initialise une nouvelle instance de PagesSetup avec les paramètres spécifiés.

```python
def __init__(self, all_pages, first_page, last_page, odd_pages, even_pages, pages, page_number):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| all_pages | `bool` | Indique s'il faut inclure toutes les pages. |
| first_page | `bool` | Indique s'il faut inclure la première page. |
| last_page | `bool` | Indique s'il faut inclure la dernière page. |
| odd_pages | `bool` | Indique s'il faut inclure les pages impaires. |
| even_pages | `bool` | Indique s'il faut inclure les pages paires |
| pages | `List[int]` | La liste des numéros de pages spécifiques à inclure. |
| page_number | `Optional[int]` | L'index de la page actuelle. |

### Voir aussi
* class [`PagesSetup`](/watermark/python-net/groupdocs.watermark.watermarks/pagessetup/)
