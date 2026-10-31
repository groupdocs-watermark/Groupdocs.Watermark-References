---
title: "فئة PdfXObjectWatermarkOptions"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية XObject إلى مستند PDF."
type: docs
url: /ar/python-net/groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/
is_root: false
weight: 70
---


## PdfXObjectWatermarkOptions class

يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية XObject إلى مستند PDF.

اعرف المزيد:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents

يُظهر نوع PdfXObjectWatermarkOptions الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/__init__/) | يقوم بتهيئة نسخة جديدة من الفئة [`PdfXObjectWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/). |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [page_index](/watermark/python-net/groupdocs.watermark.options.pdf/pdfxobjectwatermarkoptions/page_index/) | فهرس الصفحة التي سيُضاف إليها العلامة المائية. |

### الحقول
| حقل | الوصف |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | يحصل على القيمة الافتراضية للفئة. (موروثة من [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### مثال

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

### انظر أيضًا
* module [`groupdocs.watermark.options.pdf`](/watermark/python-net/groupdocs.watermark.options.pdf/)
