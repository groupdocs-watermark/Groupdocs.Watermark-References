---
title: "فئة PdfArtifactWatermarkOptions"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية قطعة أثرية إلى مستند PDF."
type: docs
url: /ar/python-net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/
is_root: false
weight: 20
---


## PdfArtifactWatermarkOptions class

يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية قطعة أثرية إلى مستند PDF.

اعرف المزيد:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents

يُظهر نوع PdfArtifactWatermarkOptions الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/__init__/) | يقوم بتهيئة نسخة جديدة من الفئة [`PdfArtifactWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/). |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [page_index](/watermark/python-net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/page_index/) | فهرس الصفحة التي سيُضاف إليها العلامة المائية. |

### الحقول
| حقل | الوصف |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | يحصل على القيمة الافتراضية للفئة. (موروثة من [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment
from groupdocs.watermark.options.pdf import PdfLoadOptions, PdfArtifactWatermarkOptions

with Watermarker("./test.pdf", PdfLoadOptions()) as watermarker:
    with ImageWatermark("./icon.png") as watermark:
        watermark.horizontal_alignment = HorizontalAlignment.RIGHT
        watermark.vertical_alignment = VerticalAlignment.BOTTOM
        options = PdfArtifactWatermarkOptions()
        options.page_index = -1  # default: all pages
        watermarker.add(watermark, options)
        watermarker.save()
```

### انظر أيضًا
* module [`groupdocs.watermark.options.pdf`](/watermark/python-net/groupdocs.watermark.options.pdf/)
