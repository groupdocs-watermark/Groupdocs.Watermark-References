---
title: "PresentationWatermarkLayoutSlideOptions sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Bir Presentation belgesinin düzen slaytına filigran eklerken seçenekleri temsil eder."
type: docs
url: /tr/python-net/groupdocs.watermark.options.presentation/presentationwatermarklayoutslideoptions/
is_root: false
weight: 80
---


## PresentationWatermarkLayoutSlideOptions class

Bir Presentation belgesinin düzen slaytına filigran eklerken seçenekleri temsil eder.

Daha fazla bilgi edinin:

- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents

Kullanım örneklerini [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/) içinde görün.

PresentationWatermarkLayoutSlideOptions türü aşağıdaki üyeleri gösterir:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarklayoutslideoptions/__init__/) | Yeni bir [`PresentationWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkoptions/) sınıfının örneğini başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [layout_slide_index](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarklayoutslideoptions/layout_slide_index/) | Filigranı eklemek için düzen slaytının dizini. |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/alternative_text/) | Bir şekille ilişkilendirilecek açıklayıcı (alternatif) metin. ([`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/) sınıfından miras alınmıştır) |
| [effects](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/effects/) | Filigrana uygulanacak etkiler, bir [`PresentationImageEffects`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationimageeffects/) veya [`PresentationTextEffects`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationtexteffects/) örneği olarak belirtilir. ([`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/) sınıfından miras alınmıştır) |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/is_locked/) | Bu özellik, PowerPoint'te şeklin düzenlenmesinin yasak olup olmadığını gösterir. ([`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/) sınıfından miras alınmıştır) |
| [name](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/name/) | Şeklin adı. ([`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/) sınıfından miras alınmıştır) |
| [protect_with_unreadable_characters](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/protect_with_unreadable_characters/) | Metin filigranı karakterlerinin okunamayan karakterlerle karıştırılıp karıştırılmadığını gösteren özellik. ([`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/) sınıfından miras alınmıştır) |

### Alanlar
| Alan | Açıklama |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Sınıf için varsayılan değeri alır. ([`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/) sınıfından devralınmıştır) |

### Örnek

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.presentation as gwo_ppt
import groupdocs.watermark.contents.presentation as gwc_ppt

load_options = gwo_ppt.PresentationLoadOptions()
with gw.Watermarker("presentation.pptx", load_options) as watermarker:
    watermark = gww.TextWatermark("Test watermark", gww.Font("Arial", 8.0))
    layout_opts = gwo_ppt.PresentationWatermarkLayoutSlideOptions()
    layout_opts.layout_slide_index = -1  # apply to all layout slides
    watermarker.add(watermark, layout_opts)
```

### Ayrıca Bakınız
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
