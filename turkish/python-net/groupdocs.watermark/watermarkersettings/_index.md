---
title: "WatermarkerSettings sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Watermarker davranışını özelleştirmek için ayarları tanımlar."
type: docs
url: /tr/python-net/groupdocs.watermark/watermarkersettings/
is_root: false
weight: 70
---


## WatermarkerSettings class

Watermarker davranışını özelleştirmek için ayarları tanımlar.

WatermarkerSettings türü aşağıdaki üyeleri ortaya koyar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarkersettings/__init__/) | WatermarkerSettings'in yeni bir örneğini başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [logger](/watermark/python-net/groupdocs.watermark/watermarkersettings/logger/) | Filigranlama sırasında olayları ve hataları kaydetmek için kullanılan logger. |
| [searchable_objects](/watermark/python-net/groupdocs.watermark/watermarkersettings/searchable_objects/) | Filigran aramasına dahil edilecek aranabilir nesneler. |

### Alanlar
| Alan | Açıklama |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark/watermarkersettings/default/) | Sınıf için varsayılan değeri alır. |

### Örnek

```python
from groupdocs.watermark import Watermarker, WatermarkerSettings
from groupdocs.watermark.search.objects import (
    SearchableObjects, WordProcessingSearchableObjects, PdfSearchableObjects,
)

settings = WatermarkerSettings()
settings.searchable_objects = SearchableObjects(
    word_processing_searchable_objects=WordProcessingSearchableObjects.HYPERLINKS
    | WordProcessingSearchableObjects.TEXT,
    pdf_searchable_objects=PdfSearchableObjects.ALL,
)

with Watermarker("./document.pdf", settings) as watermarker:
    possible = watermarker.search()
    print("Found", len(possible), "possible watermark(s)")
```

### Guides
`WatermarkerSettings` kullanan görev kılavuzları:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Ayrıca Bakınız
* module [`groupdocs.watermark`](/watermark/python-net/groupdocs.watermark/)
