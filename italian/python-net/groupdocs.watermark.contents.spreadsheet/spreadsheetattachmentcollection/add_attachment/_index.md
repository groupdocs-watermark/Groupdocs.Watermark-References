---
title: "Metodo add_attachment"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Aggiunge un allegato al SpreadsheetWorksheet."
type: docs
url: /it/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/add_attachment/
is_root: false
weight: 1010
---


## add_attachment {#file_content-source_full_name-preview_image_content-x-y-width-height}

Aggiunge un allegato al SpreadsheetWorksheet.

```python
def add_attachment(self, file_content, source_full_name, preview_image_content, x, y, width, height):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_content | `list[int]` | byte che contengono il contenuto del file da allegare. |
| source_full_name | `str` | stringa con il nome completo del file allegato (l'estensione è usata per determinare l'applicazione appropriata per aprire il file). |
| preview_image_content | `list[int]` | byte dell'immagine di anteprima del file allegato come array di byte. |
| x | `float` | intero coordinata x del riquadro dell'allegato (in punti). |
| y | `float` | intero coordinata y del riquadro dell'allegato (in punti). |
| width | `float` | intero larghezza del riquadro dell'allegato (in punti). |
| height | `float` | intero altezza del riquadro dell'allegato (in punti). |

**Returns:** None.

### Esempio

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions

def add_attachment():
    with Watermarker("./sample.xlsx", SpreadsheetLoadOptions()) as watermarker:
        content = watermarker.get_content()
        with open("./sample.docx", "rb") as f:
            data = f.read()
        with open("./preview.png", "rb") as f:
            preview = f.read()
        # Incorpora il file nel primo foglio di lavoro, mostrato come la sua immagine di anteprima
        # a x=50, y=20 con un riquadro 100 x 120
        content.worksheets[0].attachments.add_attachment(data, "sample.docx", preview, 50, 20, 100, 120)
        watermarker.save("./output.xlsx")

if __name__ == "__main__":
    add_attachment()
```

### Vedi anche
* class [`SpreadsheetAttachmentCollection`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/)
