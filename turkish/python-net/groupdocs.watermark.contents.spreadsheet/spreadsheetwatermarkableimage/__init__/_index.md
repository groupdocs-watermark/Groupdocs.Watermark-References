---
title: "__init__ yapıcı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Belirtilen görüntü verilerini kullanarak SpreadsheetWatermarkableImage sınıfının yeni bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Belirtilen görüntü verisini kullanarak [`SpreadsheetWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/) sınıfının yeni bir örneğini başlatır.

```python
def __init__(self, image_data):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image_data | `list[int]` | `SpreadsheetWatermarkableImage` oluşturulacak olan işaretsiz bayt dizisi. |

### Örnek

```python
import groupdocs.watermark.contents.spreadsheet as gwc_xls

with open("test.png", "rb") as f:
    image = gwc_xls.SpreadsheetWatermarkableImage(f.read())
```

### Ayrıca Bakınız
* class [`SpreadsheetWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetwatermarkableimage/)
