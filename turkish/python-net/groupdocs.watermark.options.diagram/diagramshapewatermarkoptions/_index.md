---
title: "DiagramShapeWatermarkOptions sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Visio belgesine şekil filigranı eklerken filigran ekleme seçeneklerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/
is_root: false
weight: 50
---


## DiagramShapeWatermarkOptions class

Visio belgesine şekil filigranı eklerken filigran ekleme seçeneklerini temsil eder.

- Add watermarks to diagram documents (https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents)

DiagramShapeWatermarkOptions türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/__init__/) | [`DiagramShapeWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/) sınıfının yeni bir örneğini başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [placement_type](/watermark/python-net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/placement_type/) | Bir filigranın hangi sayfalara eklenmesi gerektiğini belirten değer. |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.diagram/diagramwatermarkoptions/is_locked/) | Bu özellik, Visio'da şeklin düzenlenmesinin yasak olup olmadığını gösterir. ([`DiagramWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagramwatermarkoptions/) sınıfından kalıtılmıştır.) |

### Alanlar
| Alan | Açıklama |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Sınıf için varsayılan değeri alır. ([`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/) sınıfından devralınmıştır) |

### Örnek

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

### Ayrıca Bakınız
* module [`groupdocs.watermark.options.diagram`](/watermark/python-net/groupdocs.watermark.options.diagram/)
