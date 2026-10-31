---
title: "طريقة add_attachment"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يضيف مرفقًا إلى SpreadsheetWorksheet."
type: docs
url: /ar/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/add_attachment/
is_root: false
weight: 1010
---


## add_attachment {#file_content-source_full_name-preview_image_content-x-y-width-height}

يضيف مرفقًا إلى SpreadsheetWorksheet.

```python
def add_attachment(self, file_content, source_full_name, preview_image_content, x, y, width, height):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_content | `list[int]` | بايتات تحتوي على محتوى الملف المراد إرفاقه. |
| source_full_name | `str` | اسم السلسلة الكامل للملف المرفق (يُستخدم الامتداد لتحديد التطبيق المناسب لفتح الملف). |
| preview_image_content | `list[int]` | صورة معاينة للملف المرفق على شكل مصفوفة بايت. |
| x | `float` | الإحداثي السيني لإطار المرفق (بالنقاط). |
| y | `float` | الإحداثي الصادي لإطار المرفق (بالنقاط). |
| width | `float` | عرض إطار المرفق (بالنقاط). |
| height | `float` | ارتفاع إطار المرفق (بالنقاط). |

**Returns:** None.

### مثال

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
        # تضمين الملف في ورقة العمل الأولى، يُعرض كصورة معاينة له
        # عند x=50، y=20 بإطار 100 × 120
        content.worksheets[0].attachments.add_attachment(data, "sample.docx", preview, 50, 20, 100, 120)
        watermarker.save("./output.xlsx")

if __name__ == "__main__":
    add_attachment()
```

### انظر أيضًا
* class [`SpreadsheetAttachmentCollection`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/)
