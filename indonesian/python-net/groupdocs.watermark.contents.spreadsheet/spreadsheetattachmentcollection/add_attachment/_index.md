---
title: "metode add_attachment"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Menambahkan lampiran ke SpreadsheetWorksheet."
type: docs
url: /id/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/add_attachment/
is_root: false
weight: 1010
---


## add_attachment {#file_content-source_full_name-preview_image_content-x-y-width-height}

Menambahkan lampiran ke SpreadsheetWorksheet.

```python
def add_attachment(self, file_content, source_full_name, preview_image_content, x, y, width, height):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_content | `list[int]` | byte yang berisi konten file yang akan dilampirkan. |
| source_full_name | `str` | str nama lengkap file yang dilampirkan (ekstensi digunakan untuk menentukan aplikasi yang tepat untuk membuka file). |
| preview_image_content | `list[int]` | byte gambar pratinjau file yang dilampirkan sebagai array byte. |
| x | `float` | int koordinat x dari bingkai lampiran (dalam poin). |
| y | `float` | int koordinat y dari bingkai lampiran (dalam poin). |
| width | `float` | int lebar bingkai lampiran (dalam poin). |
| height | `float` | int tinggi bingkai lampiran (dalam poin). |

**Returns:** None.

### Contoh

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
        # Sematkan file di lembar kerja pertama, ditampilkan sebagai gambar pratinjau-nya
        # pada x=50, y=20 dengan bingkai 100 x 120
        content.worksheets[0].attachments.add_attachment(data, "sample.docx", preview, 50, 20, 100, 120)
        watermarker.save("./output.xlsx")

if __name__ == "__main__":
    add_attachment()
```

### Lihat Juga
* class [`SpreadsheetAttachmentCollection`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/)
