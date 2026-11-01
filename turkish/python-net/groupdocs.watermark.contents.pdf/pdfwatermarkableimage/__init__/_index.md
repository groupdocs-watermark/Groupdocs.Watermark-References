---
title: "__init__ yapıcı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Belirtilen görüntü verilerini kullanarak PdfWatermarkableImage sınıfının yeni bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Belirtilen görüntü verilerini kullanarak [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/) sınıfının yeni bir örneğini başlatır.

```python
def __init__(self, image_data):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image_data | `list[int]` | `PdfWatermarkableImage` oluşturmak için kullanılacak işaretsiz bayt dizisi. |

### Örnek

```python
import groupdocs.watermark.contents.pdf as gwc_pdf

with open("test.png", "rb") as f:
    img = gwc_pdf.PdfWatermarkableImage(f.read())
```

### Ayrıca Bakınız
* class [`PdfWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/)
