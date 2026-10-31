---
title: "فئة DiagramPageWatermarkOptions"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية على شكل إلى صفحة معينة من مستند Visio."
type: docs
url: /ar/python-net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/
is_root: false
weight: 20
---


## DiagramPageWatermarkOptions class

يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية على شكل إلى صفحة معينة من مستند Visio.

اعرف المزيد:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents

نوع DiagramPageWatermarkOptions يعرض الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/__init__/) | يُنشئ مثيلًا جديدًا للفئة [`DiagramPageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/). |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [page_index](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/page_index/) | فهرس الصفحة التي سيُضاف إليها العلامة المائية. |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.diagram/diagramwatermarkoptions/is_locked/) | الخاصية تشير إلى ما إذا كان تحرير الشكل في Visio محظوراً. (موروثة من [`DiagramWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagramwatermarkoptions/)) |

### الحقول
| حقل | الوصف |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | يحصل على القيمة الافتراضية للفئة. (موروثة من [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.diagram import DiagramPageWatermarkOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

with Watermarker("./diagram.vsdx") as watermarker:
    watermark = TextWatermark("watermark test", Font("Arial", 42.0))

    options = DiagramPageWatermarkOptions()
    options.is_locked = True
    options.page_index = 0

    watermarker.add(watermark, options)
    watermarker.save("./output.vsdx")
```

### انظر أيضًا
* module [`groupdocs.watermark.options.diagram`](/watermark/python-net/groupdocs.watermark.options.diagram/)
