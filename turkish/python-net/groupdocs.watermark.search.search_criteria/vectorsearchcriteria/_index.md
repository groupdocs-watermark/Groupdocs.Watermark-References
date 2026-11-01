---
title: "VectorSearchCriteria sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Filigran rengine göre filtrelemeye izin veren kriterleri temsil eder."
type: docs
url: /tr/python-net/groupdocs.watermark.search.search_criteria/vectorsearchcriteria/
is_root: false
weight: 170
---


## VectorSearchCriteria class

Filigran rengine göre filtrelemeye izin veren kriterleri temsil eder.

Daha fazla bilgi edinin:
- https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

VectorSearchCriteria türü aşağıdaki üyeleri ortaya çıkarır:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/vectorsearchcriteria/__init__/) | Yeni bir [`VectorSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/vectorsearchcriteria/) örneğini başlatır. |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [and_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/) | Bu SearchCriteria'yi mantıksal VE operatörü kullanarak diğer kriterlerle birleştirir. ([`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/) sınıfından kalıtılmıştır) |
| [and_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_search_criteria/) | ([`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/) sınıfından kalıtılmıştır) |
| [not_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/) | Bu SearchCriteria'yi olumsuzlar. ([`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/) sınıfından kalıtılmıştır) |
| [or_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/) | Bu SearchCriteria'yi mantıksal VEYA operatörü kullanarak diğer kriterlerle birleştirir. ([`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/) sınıfından kalıtılmıştır) |
| [or_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_search_criteria/) | ([`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/) sınıfından kalıtılmıştır) |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [vector_color_range](/watermark/python-net/groupdocs.watermark.search.search_criteria/vectorsearchcriteria/vector_color_range/) | Ön plan rengine göre vektör filigranlarını filtrelemek için kullanılan renk aralığı. |

### Örnek

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import VectorSearchCriteria, ColorRange
from groupdocs.watermark.watermarks import Color

with Watermarker("./document.pdf") as watermarker:
    search_criteria = VectorSearchCriteria()
    watermark_color = Color.from_argb(255, 169, 170, 174)  # #a9aaae
    color_range = ColorRange(watermark_color)
    color_range.min_brightness = 0.1
    color_range.max_brightness = 0.7
    search_criteria.vector_color_range = color_range

    possible_watermarks = watermarker.search(search_criteria)
    possible_watermarks.clear()
    watermarker.save("./output.pdf")
```

### Ayrıca Bakınız
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
