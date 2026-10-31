---
title: "فئة PdfAnnotationWatermarkOptions"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية توضيحية إلى مستند PDF."
type: docs
url: /ar/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/
is_root: false
weight: 10
---


## PdfAnnotationWatermarkOptions class

يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية توضيحية إلى مستند PDF.

اعرف المزيد:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents

يُظهر نوع PdfAnnotationWatermarkOptions الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/__init__/) | يقوم بتهيئة نسخة جديدة من الفئة [`PdfAnnotationWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/). |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [page_index](/watermark/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/page_index/) | فهرس الصفحة التي سيُضاف إليها العلامة المائية. |
| [print_only](/watermark/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/print_only/) | القيمة التي تشير إلى ما إذا كان سيتم طباعة التعليق التوضيحي دون عرضه في تطبيق عرض ملفات PDF. |

### الحقول
| حقل | الوصف |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | يحصل على القيمة الافتراضية للفئة. (موروثة من [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark
from groupdocs.watermark.options.pdf import PdfLoadOptions, PdfAnnotationWatermarkOptions

def add_annotation_image_watermark():
    load_options = PdfLoadOptions()
    with Watermarker("./test.pdf", load_options) as watermarker:
        with ImageWatermark("./icon.png") as watermark:
            options = PdfAnnotationWatermarkOptions()
            # PageIndex = -1 يطبق العلامة المائية على جميع الصفحات (الافتراضي).
            watermarker.add(watermark, options)
        watermarker.save("./output.pdf")
```

### انظر أيضًا
* module [`groupdocs.watermark.options.pdf`](/watermark/python-net/groupdocs.watermark.options.pdf/)
