---
title: "فئة DiagramShapeWatermarkOptions"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية على شكل إلى مستند Visio."
type: docs
url: /ar/python-net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/
is_root: false
weight: 50
---


## DiagramShapeWatermarkOptions class

يمثل خيارات إضافة العلامة المائية عند إضافة علامة مائية على شكل إلى مستند Visio.

- Add watermarks to diagram documents (https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents)

نوع DiagramShapeWatermarkOptions يعرض الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/__init__/) | يُنشئ مثلاً جديداً من الفئة [`DiagramShapeWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/). |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [placement_type](/watermark/python-net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/placement_type/) | القيمة التي تحدد إلى أي صفحات يجب إضافة العلامة المائية. |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.diagram/diagramwatermarkoptions/is_locked/) | الخاصية تشير إلى ما إذا كان تحرير الشكل في Visio محظوراً. (موروثة من [`DiagramWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagramwatermarkoptions/)) |

### الحقول
| حقل | الوصف |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | يحصل على القيمة الافتراضية للفئة. (موروثة من [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment
from groupdocs.watermark.options.diagram import DiagramShapeWatermarkOptions
from groupdocs.watermark.contents.diagram import DiagramWatermarkPlacementType

def add_watermark_to_diagram():
    with Watermarker("./diagram.vsdx") as watermarker:
        watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 19.0))
        watermark.foreground_color = Color.red
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER

        options = DiagramShapeWatermarkOptions()
        options.placement_type = DiagramWatermarkPlacementType.BACKGROUND_PAGES
        watermarker.add(watermark, options)

        watermarker.save("./output.vsdx")
```

### انظر أيضًا
* module [`groupdocs.watermark.options.diagram`](/watermark/python-net/groupdocs.watermark.options.diagram/)
