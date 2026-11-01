---
title: "PdfXObjectWatermarkOptions sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Bir PDF belgesine XObject filigranı eklerken filigran ekleme seçeneklerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/
is_root: false
weight: 70
---


## PdfXObjectWatermarkOptions class

Bir PDF belgesine XObject filigranı eklerken filigran ekleme seçeneklerini temsil eder.

Daha fazla bilgi edinin:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents

PdfXObjectWatermarkOptions türü aşağıdaki üyeleri ortaya çıkarır:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/__init__/) | Yeni bir [`PdfXObjectWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/) sınıfı örneği başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [page_index](/watermark/python-net/groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/page_index/) | Filigranın ekleneceği sayfa indeksi. |

### Alanlar
| Alan | Açıklama |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Sınıf için varsayılan değeri alır. ([`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/) sınıfından devralınmıştır) |

### Örnek

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions, PdfXObjectWatermarkOptions
from groupdocs.watermark.watermarks import ImageWatermark

load_options = PdfLoadOptions()
with Watermarker("./document.pdf", load_options) as watermarker:
    with ImageWatermark("./logo.png") as watermark:
        options = PdfXObjectWatermarkOptions()
        options.page_index = 0  # apply to the first page
        watermarker.add(watermark, options)
    watermarker.save("./output.pdf")
```

### Ayrıca Bakınız
* module [`groupdocs.watermark.options.pdf`](/watermark/python-net/groupdocs.watermark.options.pdf/)
