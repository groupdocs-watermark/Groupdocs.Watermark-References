---
title: "Metodo add_link"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Aggiunge un allegato tramite un collegamento (il documento non conterrà il contenuto del file allegato)."
type: docs
url: /it/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/add_link/
is_root: false
weight: 1050
---


## add_link {#source_full_name-preview_image_content-x-y-width-height}

Aggiunge un allegato tramite un collegamento (il documento non conterrà il contenuto del file allegato).

```python
def add_link(self, source_full_name, preview_image_content, x, y, width, height):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_full_name | `str` | Il percorso del file collegato. |
| preview_image_content | `list[int]` | L'immagine di anteprima del file allegato come array di byte. |
| x | `float` | La coordinata x del riquadro dell'allegato (in punti). |
| y | `float` | La coordinata y del riquadro dell'allegato (in punti). |
| width | `float` | La larghezza del riquadro dell'allegato in punti. |
| height | `float` | L'altezza del riquadro dell'allegato in punti. |

### Esempio

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions
import groupdocs.watermark.contents.spreadsheet as gwc_xls

load_options = SpreadsheetLoadOptions()
with gw.Watermarker("spreadsheet.xlsx", load_options) as watermarker:
    content = watermarker.get_content()
    worksheet = content.worksheets[0]
    with open("document_preview.png", "rb") as f_prev:
        worksheet.attachments.add_link(
            "document.docx",
            f_prev.read(),
            50,
            100,
            200,
            400,
        )
    watermarker.save("output.xlsx")
```

### Vedi anche
* class [`SpreadsheetAttachmentCollection`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/)
