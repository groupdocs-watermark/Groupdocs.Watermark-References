---
title: "add_attachment Methode"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Fügt dem SpreadsheetWorksheet einen Anhang hinzu."
type: docs
url: /de/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/add_attachment/
is_root: false
weight: 1010
---


## add_attachment {#file_content-source_full_name-preview_image_content-x-y-width-height}

Fügt dem SpreadsheetWorksheet einen Anhang hinzu.

```python
def add_attachment(self, file_content, source_full_name, preview_image_content, x, y, width, height):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_content | `list[int]` | Bytes, die den Inhalt der anzuhängenden Datei enthalten. |
| source_full_name | `str` | str voller Name der angehängten Datei (die Erweiterung wird verwendet, um die geeignete Anwendung zum Öffnen der Datei zu bestimmen). |
| preview_image_content | `list[int]` | Bytes-Vorschaubild der angehängten Datei als Byte-Array. |
| x | `float` | int x‑Koordinate des Anhangrahmens (in Punkten). |
| y | `float` | int y‑Koordinate des Anhangrahmens (in Punkten). |
| width | `float` | int Breite des Anhangrahmens (in Punkten). |
| height | `float` | int Höhe des Anhangrahmens (in Punkten). |

**Returns:** None.

### Beispiel

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
        # Betten Sie die Datei im ersten Arbeitsblatt ein, angezeigt als deren Vorschaubild
        # bei x=50, y=20 mit einem 100 x 120 Rahmen
        content.worksheets[0].attachments.add_attachment(data, "sample.docx", preview, 50, 20, 100, 120)
        watermarker.save("./output.xlsx")

if __name__ == "__main__":
    add_attachment()
```

### Siehe auch
* class [`SpreadsheetAttachmentCollection`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/)
