---
title: "Classe TextFormattingSearchCriteria"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Rappresenta i criteri che consentono il filtraggio per formattazione del testo."
type: docs
url: /it/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/
is_root: false
weight: 150
---


## TextFormattingSearchCriteria class

Rappresenta i criteri che consentono il filtraggio per formattazione del testo.

Per saperne di più:
- Searching watermarks (https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

Il tipo TextFormattingSearchCriteria espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/__init__/) | Inizializza una nuova istanza di [`TextFormattingSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/). |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [and_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/) | Combina questo SearchCriteria con altri criteri usando l'operatore logico AND. (eredita da [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [and_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_search_criteria/) | (eredita da [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [not_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/) | Negare questo SearchCriteria. (eredita da [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [or_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/) | Combina questo SearchCriteria con altri criteri usando l'operatore logico OR. (eredita da [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [or_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_search_criteria/) | (eredita da [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [background_color_range](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/background_color_range/) | L'intervallo di colori utilizzato per filtrare i watermark in base al colore di sfondo del testo. |
| [font_bold](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/font_bold/) | Il carattere usato nella formattazione del testo del watermark è in grassetto. |
| [font_italic](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/font_italic/) | La proprietà font_italic indica se il carattere del testo del watermark è in corsivo. |
| [font_name](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/font_name/) | Il nome del carattere usato nella possibile formattazione del testo del watermark. |
| [font_strikeout](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/font_strikeout/) | Il flag di barrato del carattere per la formattazione del testo del watermark. |
| [font_underline](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/font_underline/) | Il flag di sottolineatura del carattere che indica se il testo del watermark utilizza una sottolineatura. |
| [foreground_color_range](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/foreground_color_range/) | L'intervallo di colori usato per filtrare i watermark per colore di primo piano del testo. |
| [max_font_size](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/max_font_size/) | Il valore finale della dimensione del carattere. |
| [min_font_size](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/min_font_size/) | Il valore iniziale della dimensione del carattere. |

### Esempio

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextFormattingSearchCriteria, ColorRange

def search_by_formatting():
    with Watermarker("./document.pdf") as watermarker:
        criteria = TextFormattingSearchCriteria()
        criteria.foreground_color_range = ColorRange()
        criteria.foreground_color_range.min_hue = -15
        criteria.foreground_color_range.max_hue = 15
        criteria.foreground_color_range.min_brightness = 0.01
        criteria.foreground_color_range.max_brightness = 0.99
        criteria.min_font_size = 19
        criteria.max_font_size = 42

        possible = watermarker.search(criteria)
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_formatting()
```

### Guides
Guide operative che utilizzano `TextFormattingSearchCriteria`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Vedi anche
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
