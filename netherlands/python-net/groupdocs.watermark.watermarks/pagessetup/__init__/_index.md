---
title: "__init__ constructor"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Initialiseert een nieuw exemplaar van de PagesSetup-klasse."
type: docs
url: /nl/python-net/groupdocs.watermark.watermarks/pagessetup/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een nieuw exemplaar van de [`PagesSetup`](/watermark/python-net/groupdocs.watermark.watermarks/pagessetup/) klasse.

```python
def __init__(self):
    ...
```

## __init__ {#all_pages-first_page-last_page-odd_pages-even_pages-pages-page_number}

Initialiseert een nieuw PagesSetup-exemplaar met opgegeven parameters.

```python
def __init__(self, all_pages, first_page, last_page, odd_pages, even_pages, pages, page_number):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| all_pages | `bool` | Of alle pagina's moeten worden opgenomen. |
| first_page | `bool` | Of de eerste pagina moet worden opgenomen. |
| last_page | `bool` | Of de laatste pagina moet worden opgenomen. |
| odd_pages | `bool` | Of oneven pagina's moeten worden opgenomen. |
| even_pages | `bool` | Of even pagina's moeten worden opgenomen. |
| pages | `List[int]` | De lijst met specifieke paginanummers die moeten worden opgenomen. |
| page_number | `Optional[int]` | De index van de huidige pagina. |

### Zie ook
* class [`PagesSetup`](/watermark/python-net/groupdocs.watermark.watermarks/pagessetup/)
