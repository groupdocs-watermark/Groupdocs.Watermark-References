---
title: "WordProcessingImageEffects sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Word belgesi için bir resim filigranına uygulanabilecek efektleri temsil eder."
type: docs
url: /tr/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/
is_root: false
weight: 30
---


## WordProcessingImageEffects class

Word belgesi için bir resim filigranına uygulanabilecek efektleri temsil eder.

WordProcessingImageEffects türü aşağıdaki üyeleri gösterir:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/__init__/) | Yeni bir [`WordProcessingImageEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/) sınıfı örneği başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [border_line_format](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/border_line_format/) | Görüntü kenarlığının çizgi biçim ayarları. ([`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/) sınıfından devralınmıştır) |
| [brightness](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/brightness/) | Resmin parlaklığı. 0.0 (en karanlık) ile 1.0 (en parlak) arasında bir ondalık sayı olmalıdır. Varsayılan değer 0.5'tir. ([`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/) sınıfından devralınmıştır) |
| [chroma_key](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/chroma_key/) | Şeffaf olarak işlenecek görüntünün renk değeri. Varsayılan değer tamamen şeffaf bir renktir. ([`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/) sınıfından devralınmıştır) |
| [contrast](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/contrast/) | Belirtilen resmin kontrastı. 0.0 (en düşük kontrast) ile 1.0 (en yüksek kontrast) arasında bir ondalık sayı olmalıdır. Varsayılan değer 0.5'tir. ([`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/) sınıfından devralınmıştır) |
| [gray_scale](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/gray_scale/) | Bu özellik, bir resmin gri tonlamalı modda gösterilip gösterilmeyeceğini belirtir. ([`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/) sınıfından devralınmıştır) |

### Örnek

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark, Color
from groupdocs.watermark.options.word_processing import (
    WordProcessingLoadOptions, WordProcessingWatermarkSectionOptions, WordProcessingImageEffects,
)

def add_watermark_with_effects():
    with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
        with ImageWatermark("./logo.png") as watermark:
            effects = WordProcessingImageEffects()
            effects.brightness = 0.7
            effects.contrast = 0.6
            effects.chroma_key = Color.red

            options = WordProcessingWatermarkSectionOptions()
            options.name = "Shape 1"
            options.alternative_text = "Company logo watermark"
            options.effects = effects
            watermarker.add(watermark, options)

        watermarker.save("./output.docx")

if __name__ == "__main__":
    add_watermark_with_effects()
```

### Ayrıca Bakınız
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
