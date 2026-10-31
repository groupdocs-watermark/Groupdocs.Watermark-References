---
title: "add_link Methode"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Fügt einen Anhang über einen Link hinzu (das Dokument enthält nicht den Inhalt der angehängten Datei)."
type: docs
url: /de/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/add_link/
is_root: false
weight: 1050
---


## add_link {#source_full_name-preview_image_content-x-y-width-height}

Fügt einen Anhang über einen Link hinzu (das Dokument enthält nicht den Inhalt der angehängten Datei).

```python
def add_link(self, source_full_name, preview_image_content, x, y, width, height):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_full_name | `str` | Der Pfad der verknüpften Datei. |
| preview_image_content | `list[int]` | Das Vorschaubild der angehängten Datei als Byte-Array. |
| x | `float` | Die x-Koordinate des Anhangrahmens (in Punkten). |
| y | `float` | Die y-Koordinate des Anhangrahmens (in Punkten). |
| width | `float` | Die Breite des Anhangrahmens in Punkten. |
| height | `float` | Die Höhe des Anhangrahmens in Punkten. |

### Beispiel

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

### Siehe auch
* class [`SpreadsheetAttachmentCollection`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/)
