---
title: "add_attachment yöntemi"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Bir eki SpreadsheetWorksheet'e ekler."
type: docs
url: /tr/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/add_attachment/
is_root: false
weight: 1010
---


## add_attachment {#file_content-source_full_name-preview_image_content-x-y-width-height}

Bir eki SpreadsheetWorksheet'e ekler.

```python
def add_attachment(self, file_content, source_full_name, preview_image_content, x, y, width, height):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_content | `list[int]` | Eklenecek dosyanın içeriğini içeren baytlar. |
| source_full_name | `str` | Ekli dosyanın tam adı (uzantı, dosyayı açmak için uygun uygulamayı belirlemek amacıyla kullanılır). |
| preview_image_content | `list[int]` | Ekli dosyanın önizleme resmi, bayt dizisi olarak. |
| x | `float` | int x‑koordinatı ek çerçevesinin (puan cinsinden). |
| y | `float` | int y‑koordinatı ek çerçevesinin (puan cinsinden). |
| width | `float` | int ek çerçevesinin genişliği (puan cinsinden). |
| height | `float` | int ek çerçevesinin yüksekliği (puan cinsinden). |

**Returns:** None.

### Örnek

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
        # Dosyayı ilk çalışma sayfasına göm, önizleme resmi olarak gösterilir
        # x=50, y=20 konumunda, 100 x 120 çerçeve ile
        content.worksheets[0].attachments.add_attachment(data, "sample.docx", preview, 50, 20, 100, 120)
        watermarker.save("./output.xlsx")

if __name__ == "__main__":
    add_attachment()
```

### Ayrıca Bakınız
* class [`SpreadsheetAttachmentCollection`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/)
