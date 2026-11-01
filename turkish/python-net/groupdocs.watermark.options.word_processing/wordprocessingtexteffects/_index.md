---
title: "WordProcessingTextEffects sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Word belgesi için bir metin filigranına uygulanabilecek efektleri temsil eder."
type: docs
url: /tr/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/
is_root: false
weight: 80
---


## WordProcessingTextEffects class

Word belgesi için bir metin filigranına uygulanabilecek efektleri temsil eder.

WordProcessingTextEffects türü aşağıdaki üyeleri gösterir:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/__init__/) | Yeni bir [`WordProcessingTextEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/) sınıfı örneği başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [flip_orientation](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/flip_orientation/) | Bir şeklin yönelimi. |
| [line_format](/watermark/python-net/groupdocs.watermark.contents/officetexteffects/line_format/) | Bir [`OfficeLineFormat`](/watermark/python-net/groupdocs.watermark.contents/officelineformat/) örneğiyle temsil edilen satır biçim ayarları. ([`OfficeTextEffects`](/watermark/python-net/groupdocs.watermark.contents/officetexteffects/) sınıfından devralınmıştır.) |

### Alanlar
| Alan | Açıklama |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/default/) | Sınıf için varsayılan değeri alır. |

### Örnek

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.word_processing as gwo_wp
import groupdocs.watermark.common as gwc
from groupdocs.watermark.contents import OfficeDashStyle, OfficeLineStyle

load_options = gwo_wp.WordProcessingLoadOptions()
with gw.Watermarker("document.docx", load_options) as watermarker:
    watermark = gww.TextWatermark("Test watermark", gww.Font("Arial", 19.0))

    effects = gwo_wp.WordProcessingTextEffects()
    effects.line_format.enabled = True
    effects.line_format.color = gww.Color.red
    effects.line_format.dash_style = OfficeDashStyle.DASH_DOT_DOT
    effects.line_format.line_style = OfficeLineStyle.TRIPLE
    effects.line_format.weight = 1

    options = gwo_wp.WordProcessingWatermarkSectionOptions()
    options.effects = effects

    watermarker.add(watermark, options)
    watermarker.save("output.docx")
```

### Ayrıca Bakınız
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
