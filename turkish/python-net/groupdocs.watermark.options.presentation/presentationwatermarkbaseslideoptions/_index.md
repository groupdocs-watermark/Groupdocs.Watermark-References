---
title: "PresentationWatermarkBaseSlideOptions sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Bir Presentation belgesine filigran ekleme seçenekleri için temel sınıf."
type: docs
url: /tr/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/
is_root: false
weight: 70
---


## PresentationWatermarkBaseSlideOptions class

Bir Presentation belgesine filigran ekleme seçenekleri için temel sınıf.

Daha fazla bilgi edinin:
- Add watermarks to presentation documents: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents

PresentationWatermarkBaseSlideOptions türü aşağıdaki üyeleri sunar:

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/alternative_text/) | Şekille ilişkilendirilecek açıklayıcı (alternatif) metin. |
| [effects](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/effects/) | Filigrana uygulanacak etkiler, bir [`PresentationImageEffects`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationimageeffects/) veya [`PresentationTextEffects`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationtexteffects/) örneği olarak belirtilir. |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/is_locked/) | Bu özellik, PowerPoint'te şeklin düzenlenmesinin yasak olup olmadığını gösterir. |
| [name](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/name/) | Şeklin adı. |
| [protect_with_unreadable_characters](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/protect_with_unreadable_characters/) | Metin filigranı karakterlerinin okunamayan karakterlerle karıştırılıp karıştırılmadığını gösteren özellik. |

### Alanlar
| Alan | Açıklama |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Sınıf için varsayılan değeri alır. ([`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/) sınıfından devralınmıştır) |

### Örnek

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.presentation import PresentationWatermarkMasterSlideOptions
from groupdocs.watermark.options.presentation import PresentationWatermarkLayoutSlideOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

with Watermarker("./presentation.pptx") as watermarker:
    watermark = TextWatermark("Test watermark", Font("Arial", 8.0))

    master_options = PresentationWatermarkMasterSlideOptions()
    master_options.master_slide_index = 0
    watermarker.add(watermark, master_options)

    layout_options = PresentationWatermarkLayoutSlideOptions()
    layout_options.layout_slide_index = 0
    watermarker.add(watermark, layout_options)

    watermarker.save("./output.pptx")
```

### Ayrıca Bakınız
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
