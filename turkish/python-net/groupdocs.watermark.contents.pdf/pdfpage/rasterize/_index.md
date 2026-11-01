---
title: "rasterize yöntemi"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Sayfa içeriğini bir görüntüye dönüştürür."
type: docs
url: /tr/python-net/groupdocs.watermark.contents.pdf/pdfpage/rasterize/
is_root: false
weight: 1010
---


## rasterize {#horizontal_resolution-vertical_resolution-image_format}

Sayfa içeriğini bir görüntüye dönüştürür.

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
from groupdocs.watermark.options.pdf import PdfLoadOptions
from groupdocs.watermark.contents.pdf import PdfImageConversionFormat

with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
    content = watermarker.get_content()
    # İlk sayfayı 100 DPI'de PNG görüntüsüne rasterleştir.
    content.pages[0].rasterize(100, 100, PdfImageConversionFormat.PNG)
    watermarker.save("./output.pdf")
```

### Ayrıca Bakınız
* class [`PdfPage`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfpage/)
