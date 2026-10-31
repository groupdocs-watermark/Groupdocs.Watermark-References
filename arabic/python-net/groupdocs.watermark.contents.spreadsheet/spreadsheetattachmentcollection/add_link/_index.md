---
title: "طريقة add_link"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يضيف مرفقًا عبر رابط (لن يحتوي المستند على محتوى الملف المرفق)."
type: docs
url: /ar/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/add_link/
is_root: false
weight: 1050
---


## add_link {#source_full_name-preview_image_content-x-y-width-height}

يضيف مرفقًا عبر رابط (لن يحتوي المستند على محتوى الملف المرفق).

```python
def add_link(self, source_full_name, preview_image_content, x, y, width, height):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| source_full_name | `str` | مسار الملف المرتبط. |
| preview_image_content | `list[int]` | صورة معاينة الملف المرفق كمصفوفة بايت. |
| x | `float` | الإحداثي السيني لإطار المرفق (بالنقاط). |
| y | `float` | الإحداثي الصادي لإطار المرفق (بالنقاط). |
| width | `float` | عرض إطار المرفق بالنقاط. |
| height | `float` | ارتفاع إطار المرفق بالنقاط. |

### مثال

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

### انظر أيضًا
* class [`SpreadsheetAttachmentCollection`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/)
