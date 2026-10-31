---
title: "méthode add_link"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Ajoute une pièce jointe via un lien (le document ne contiendra pas le contenu du fichier joint)."
type: docs
url: /fr/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/add_link/
is_root: false
weight: 1050
---


## add_link {#source_full_name-preview_image_content-x-y-width-height}

Ajoute une pièce jointe via un lien (le document ne contiendra pas le contenu du fichier joint).

```python
def add_link(self, source_full_name, preview_image_content, x, y, width, height):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| source_full_name | `str` | Le chemin du fichier lié. |
| preview_image_content | `list[int]` | L'image d'aperçu du fichier joint sous forme de tableau d'octets. |
| x | `float` | La coordonnée x du cadre de la pièce jointe (en points). |
| y | `float` | La coordonnée y du cadre de la pièce jointe (en points). |
| width | `float` | La largeur du cadre de la pièce jointe en points. |
| height | `float` | La hauteur du cadre de la pièce jointe en points. |

### Exemple

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

### Voir aussi
* class [`SpreadsheetAttachmentCollection`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/)
