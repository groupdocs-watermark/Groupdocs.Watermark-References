---
title: "méthode add_attachment"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Ajoute une pièce jointe au SpreadsheetWorksheet."
type: docs
url: /fr/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/add_attachment/
is_root: false
weight: 1010
---


## add_attachment {#file_content-source_full_name-preview_image_content-x-y-width-height}

Ajoute une pièce jointe au SpreadsheetWorksheet.

```python
def add_attachment(self, file_content, source_full_name, preview_image_content, x, y, width, height):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_content | `list[int]` | octets contenant le contenu du fichier à joindre. |
| source_full_name | `str` | str nom complet du fichier joint (l'extension est utilisée pour déterminer l'application appropriée pour ouvrir le fichier). |
| preview_image_content | `list[int]` | octets image d'aperçu du fichier joint sous forme de tableau d'octets. |
| x | `float` | int coordonnée x du cadre de la pièce jointe (en points). |
| y | `float` | int coordonnée y du cadre de la pièce jointe (en points). |
| width | `float` | int largeur du cadre de la pièce jointe (en points). |
| height | `float` | int hauteur du cadre de la pièce jointe (en points). |

**Returns:** None.

### Exemple

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
        # Intégrer le fichier dans la première feuille de calcul, affiché comme son image d'aperçu
        # à x=50, y=20 avec un cadre de 100 x 120
        content.worksheets[0].attachments.add_attachment(data, "sample.docx", preview, 50, 20, 100, 120)
        watermarker.save("./output.xlsx")

if __name__ == "__main__":
    add_attachment()
```

### Voir aussi
* class [`SpreadsheetAttachmentCollection`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/)
