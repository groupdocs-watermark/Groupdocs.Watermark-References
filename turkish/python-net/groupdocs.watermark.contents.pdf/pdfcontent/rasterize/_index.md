---
title: "rasterize yöntemi"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Tüm içerik sayfalarını görüntülere dönüştürür."
type: docs
url: /tr/python-net/groupdocs.watermark.contents.pdf/pdfcontent/rasterize/
is_root: false
weight: 1050
---


## rasterize {#horizontal_resolution-vertical_resolution-image_format}

Tüm içerik sayfalarını görüntülere dönüştürür.

```python
def rasterize(self, horizontal_resolution, vertical_resolution, image_format):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| horizontal_resolution | `int` | Yatay görüntü çözünürlüğü. |
| vertical_resolution | `int` | Dikey görüntü çözünürlüğü. |
| image_format | `PdfImageConversionFormat` | Görüntü formatı. |

### Örnek

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.contents.pdf import PdfImageConversionFormat
from groupdocs.watermark.options.pdf import PdfLoadOptions

def rasterize_document():
    with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
        # Bir filigran ekle (isteğe bağlı)
        # watermarker.add(TextWatermark("CONFIDENTIAL", Font("Arial", 19.0)))

        # Her sayfayı 100x100 DPI'de PNG görüntülere rasterleştir
        content = watermarker.get_content()
        content.rasterize(100, 100, PdfImageConversionFormat.PNG)

        watermarker.save("./output.pdf")
```

### Ayrıca Bakınız
* class [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/)
