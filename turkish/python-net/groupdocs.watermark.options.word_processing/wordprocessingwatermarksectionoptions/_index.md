---
title: "WordProcessingWatermarkSectionOptions sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Filigranı bir Word belge bölümüne şekil olarak eklerken seçenekleri temsil eder."
type: docs
url: /tr/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarksectionoptions/
is_root: false
weight: 120
---


## WordProcessingWatermarkSectionOptions class

Filigranı bir Word belge bölümüne şekil olarak eklerken seçenekleri temsil eder.

Daha fazla bilgi edinin:
- Add watermarks to word processing documents: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents

WordProcessingWatermarkSectionOptions türü aşağıdaki üyeleri gösterir:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarksectionoptions/__init__/) | Yeni bir [`WordProcessingWatermarkSectionOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarksectionoptions/) sınıfının bir örneğini başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [section_index](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarksectionoptions/section_index/) | Filigranın ekleneceği bölümün indeksi. |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/alternative_text/) | Bir şekille ilişkilendirilecek açıklayıcı (alternatif) metin. ([`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/) sınıfından devralınmıştır) |
| [effects](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/effects/) | Filigrana uygulanacak etkiler, bir [`WordProcessingImageEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/) veya [`WordProcessingTextEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/) örneği olarak belirtilir. ([`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/) sınıfından devralınmıştır) |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/is_locked/) | Bu özellik, Word'de şeklin düzenlenmesinin yasak olup olmadığını gösterir. ([`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/) sınıfından devralınmıştır) |
| [lock_type](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/lock_type/) | Filigran kilit türü. ([`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/) sınıfından devralınmıştır) |
| [name](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/name/) | Şeklin adı. ([`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/) sınıfından devralınmıştır) |
| [password](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/password/) | Filigranı kilitlemek için kullanılan şifre. ([`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/) sınıfından devralınmıştır) |

### Alanlar
| Alan | Açıklama |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Sınıf için varsayılan değeri alır. ([`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/) sınıfından devralınmıştır) |

### Örnek

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment
from groupdocs.watermark.options.word_processing import (
    WordProcessingLoadOptions, WordProcessingWatermarkSectionOptions,
)

with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
    watermark = TextWatermark("Test watermark", Font("Arial", 36.0))
    watermark.horizontal_alignment = HorizontalAlignment.CENTER
    watermark.vertical_alignment = VerticalAlignment.CENTER
    watermark.foreground_color = Color.red

    options = WordProcessingWatermarkSectionOptions()
    options.section_index = 0

    watermarker.add(watermark, options)
    watermarker.save("./output.docx")
```

### Ayrıca Bakınız
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
