---
title: "Classe SpreadsheetContent"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Rappresenta un documento Excel dove è possibile posizionare una filigrana."
type: docs
url: /it/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/
is_root: false
weight: 80
---


## SpreadsheetContent class

Rappresenta un documento Excel dove è possibile posizionare una filigrana.

Per saperne di più:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents
- https://docs.groupdocs.com/display/watermarknet/Shapes+in+spreadsheet+document
- https://docs.groupdocs.com/display/watermarknet/Working+with+spreadsheet+document+attachments
- https://docs.groupdocs.com/display/watermarknet/Working+with+worksheet+backgrounds
- https://docs.groupdocs.com/display/watermarknet/Working+with+worksheet+headers+and+footers

Il tipo SpreadsheetContent espone i seguenti membri:

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [decrypt](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/decrypt/) | Decripta il documento. |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/encrypt/#password) | Cifra il contenuto. |
| [encrypt_file](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/encrypt_file/) |  |
| [encrypt_string](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/encrypt_string/) |  |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | Elimina l'istanza corrente. (eredita da [`Content`](/watermark/python-net/groupdocs.watermark.contents/content/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Trova le immagini in base ai criteri di ricerca specificati. La ricerca viene eseguita negli oggetti specificati in [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (eredita da [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (eredita da [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Trova i possibili watermark in base ai criteri di ricerca specificati. La ricerca viene eseguita sugli oggetti elencati in [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (eredita da [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (eredita da [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [worksheets](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/worksheets/) | La raccolta di tutti i fogli di lavoro di questo [`SpreadsheetContent`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/). |

### Esempio

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions

load_options = SpreadsheetLoadOptions()
with Watermarker(r"D:\input.xls", load_options) as watermarker:
    # Utilizza il metodo add per aggiungere la filigrana a un foglio specifico o a tutti i fogli.
    watermarker.save(r"D:\output.xls")
```

### Vedi anche
* module [`groupdocs.watermark.contents.spreadsheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/)
