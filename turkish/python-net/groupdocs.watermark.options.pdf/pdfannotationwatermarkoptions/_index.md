---
title: "PdfAnnotationWatermarkOptions sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Bir PDF belgesine açıklama filigranı eklerken filigran ekleme seçeneklerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/
is_root: false
weight: 10
---


## PdfAnnotationWatermarkOptions class

Bir PDF belgesine açıklama filigranı eklerken filigran ekleme seçeneklerini temsil eder.

Daha fazla bilgi edinin:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents

PdfAnnotationWatermarkOptions türü aşağıdaki üyeleri ortaya çıkarır:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/__init__/) | Yeni bir [`PdfAnnotationWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/) sınıfı örneği başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [page_index](/watermark/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/page_index/) | Filigranın ekleneceği sayfa indeksi. |
| [print_only](/watermark/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/print_only/) | Ek açıklamanın bir PDF görüntüleme uygulamasında yazdırılacağını ancak gösterilmeyeceğini belirten değer. |

### Alanlar
| Alan | Açıklama |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Sınıf için varsayılan değeri alır. ([`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/) sınıfından devralınmıştır) |

### Örnek

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark
from groupdocs.watermark.options.pdf import PdfLoadOptions, PdfAnnotationWatermarkOptions

def add_annotation_image_watermark():
    load_options = PdfLoadOptions()
    with Watermarker("./test.pdf", load_options) as watermarker:
        with ImageWatermark("./icon.png") as watermark:
            options = PdfAnnotationWatermarkOptions()
            # PageIndex = -1, filigranı tüm sayfalara uygular (varsayılan).
            watermarker.add(watermark, options)
        watermarker.save("./output.pdf")
```

### Ayrıca Bakınız
* module [`groupdocs.watermark.options.pdf`](/watermark/python-net/groupdocs.watermark.options.pdf/)
