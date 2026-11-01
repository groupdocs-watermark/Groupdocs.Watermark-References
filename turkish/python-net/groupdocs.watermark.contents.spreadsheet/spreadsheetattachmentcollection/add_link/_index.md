---
title: "add_link yöntemi"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Bir bağlantı aracılığıyla ek ekler (belge ekli dosya içeriğini içermez)."
type: docs
url: /tr/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/add_link/
is_root: false
weight: 1050
---


## add_link {#source_full_name-preview_image_content-x-y-width-height}

Bir bağlantı aracılığıyla ek ekler (belge ekli dosya içeriğini içermez).

```python
def add_link(self, source_full_name, preview_image_content, x, y, width, height):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_full_name | `str` | Bağlantılı dosya yolu. |
| preview_image_content | `list[int]` | Ekli dosyanın önizleme görüntüsü bayt dizisi olarak. |
| x | `float` | Ek çerçevesinin x koordinatı (puan cinsinden). |
| y | `float` | Ek çerçevesinin y koordinatı (puan cinsinden). |
| width | `float` | Ek dosya çerçevesinin genişliği nokta cinsinden. |
| height | `float` | Ek dosya çerçevesinin yüksekliği nokta cinsinden. |

### Örnek

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

### Ayrıca Bakınız
* class [`SpreadsheetAttachmentCollection`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/)
