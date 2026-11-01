---
title: "Метод add_link"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Добавляет вложение по ссылке (документ не будет содержать содержимое прикреплённого файла)."
type: docs
url: /ru/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/add_link/
is_root: false
weight: 1050
---


## add_link {#source_full_name-preview_image_content-x-y-width-height}

Добавляет вложение по ссылке (документ не будет содержать содержимое прикреплённого файла).

```python
def add_link(self, source_full_name, preview_image_content, x, y, width, height):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_full_name | `str` | Путь к связанному файлу. |
| preview_image_content | `list[int]` | Изображение предварительного просмотра прикреплённого файла в виде массива байтов. |
| x | `float` | Координата x рамки вложения (в пунктах). |
| y | `float` | Координата y рамки вложения (в пунктах). |
| width | `float` | Ширина рамки вложения в пунктах. |
| height | `float` | Высота рамки вложения в пунктах. |

### Пример

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

### См. также
* class [`SpreadsheetAttachmentCollection`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/)
