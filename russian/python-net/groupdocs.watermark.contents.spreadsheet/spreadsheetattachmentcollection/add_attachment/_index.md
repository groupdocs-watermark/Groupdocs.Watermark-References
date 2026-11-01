---
title: "Метод add_attachment"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Добавляет вложение в SpreadsheetWorksheet."
type: docs
url: /ru/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/add_attachment/
is_root: false
weight: 1010
---


## add_attachment {#file_content-source_full_name-preview_image_content-x-y-width-height}

Добавляет вложение в SpreadsheetWorksheet.

```python
def add_attachment(self, file_content, source_full_name, preview_image_content, x, y, width, height):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_content | `list[int]` | Массив байтов, содержащий содержимое файла для вложения. |
| source_full_name | `str` | Полное имя вложенного файла типа str (расширение используется для определения подходящего приложения для открытия файла). |
| preview_image_content | `list[int]` | Изображение‑предпросмотр вложенного файла в виде массива байтов. |
| x | `float` | Координата x рамки вложения типа int (в пунктах). |
| y | `float` | Координата y рамки вложения типа int (в пунктах). |
| width | `float` | Ширина рамки вложения типа int (в пунктах). |
| height | `float` | Высота рамки вложения типа int (в пунктах). |

**Returns:** None.

### Пример

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
        # Встроить файл в первый лист, отображаемый как его изображение‑предпросмотр
        # при x=50, y=20 с рамкой 100 x 120
        content.worksheets[0].attachments.add_attachment(data, "sample.docx", preview, 50, 20, 100, 120)
        watermarker.save("./output.xlsx")

if __name__ == "__main__":
    add_attachment()
```

### См. также
* class [`SpreadsheetAttachmentCollection`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/)
