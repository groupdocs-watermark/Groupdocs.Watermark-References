---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz der PagesSetup-Klasse."
type: docs
url: /de/python-net/groupdocs.watermark.watermarks/pagessetup/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine neue Instanz der [`PagesSetup`](/watermark/python-net/groupdocs.watermark.watermarks/pagessetup/) Klasse.

```python
def __init__(self):
    ...
```

## __init__ {#all_pages-first_page-last_page-odd_pages-even_pages-pages-page_number}

Initialisiert eine neue PagesSetup-Instanz mit angegebenen Parametern.

```python
def __init__(self, all_pages, first_page, last_page, odd_pages, even_pages, pages, page_number):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| all_pages | `bool` | Ob alle Seiten einbezogen werden sollen. |
| first_page | `bool` | Ob die erste Seite einbezogen werden soll. |
| last_page | `bool` | Ob die letzte Seite einbezogen werden soll. |
| odd_pages | `bool` | Ob ungerade Seiten einbezogen werden sollen. |
| even_pages | `bool` | Ob gerade Seiten einbezogen werden sollen. |
| pages | `List[int]` | Die Liste der einzuschließenden spezifischen Seitennummern. |
| page_number | `Optional[int]` | Der Index der aktuellen Seite. |

### Siehe auch
* class [`PagesSetup`](/watermark/python-net/groupdocs.watermark.watermarks/pagessetup/)
