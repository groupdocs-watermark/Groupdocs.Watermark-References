---
title: "SearchableObjects sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Filigran aramasına dahil edilecek belge nesnelerini belirtir."
type: docs
url: /tr/python-net/groupdocs.watermark.search.objects/searchableobjects/
is_root: false
weight: 50
---


## SearchableObjects class

Filigran aramasına dahil edilecek belge nesnelerini belirtir.

Daha fazla bilgi edinin:
- https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

SearchableObjects türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/__init__/) | Yeni bir [`SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) sınıfının örneğini başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [diagram_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/diagram_searchable_objects/) | Bir Visio belgesindeki, filigran aramasına dahil edilecek nesneler. |
| [email_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/email_searchable_objects/) | Bir e-posta mesajındaki, filigran aramasına dahil edilecek nesneler. |
| [pdf_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/pdf_searchable_objects/) | Bir PDF belgesindeki, filigran aramasına dahil edilecek nesneler. |
| [presentation_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/presentation_searchable_objects/) | Bir PowerPoint belgesindeki, filigran aramasına dahil edilecek nesneler. |
| [spreadsheet_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/spreadsheet_searchable_objects/) | Bir Excel belgesindeki, filigran aramasına dahil edilecek nesneler. |
| [word_processing_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/word_processing_searchable_objects/) | Bir Word belgesindeki, filigran aramasına dahil edilecek nesneler. |

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
`SearchableObjects` kullanan görev kılavuzları:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Ayrıca Bakınız
* module [`groupdocs.watermark.search.objects`](/watermark/python-net/groupdocs.watermark.search.objects/)
