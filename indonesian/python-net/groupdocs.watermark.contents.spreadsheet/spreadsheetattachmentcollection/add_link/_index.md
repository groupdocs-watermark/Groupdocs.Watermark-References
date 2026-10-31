---
title: "metode add_link"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Menambahkan lampiran melalui tautan (dokumen tidak akan berisi konten file yang dilampirkan)."
type: docs
url: /id/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/add_link/
is_root: false
weight: 1050
---


## add_link {#source_full_name-preview_image_content-x-y-width-height}

Menambahkan lampiran melalui tautan (dokumen tidak akan berisi konten file yang dilampirkan).

```python
def add_link(self, source_full_name, preview_image_content, x, y, width, height):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_full_name | `str` | Jalur file yang ditautkan. |
| preview_image_content | `list[int]` | Gambar pratinjau file yang dilampirkan sebagai array byte. |
| x | `float` | Koordinat x dari bingkai lampiran (dalam poin). |
| y | `float` | Koordinat y dari bingkai lampiran (dalam poin). |
| width | `float` | Lebar bingkai lampiran dalam poin. |
| height | `float` | Tinggi bingkai lampiran dalam poin. |

### Contoh

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

### Lihat Juga
* class [`SpreadsheetAttachmentCollection`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/)
