---
title: "SizeSearchCriteria sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Filigran boyutuna göre filtrelemeye izin veren kriterleri temsil eder."
type: docs
url: /tr/python-net/groupdocs.watermark.search.search_criteria/sizesearchcriteria/
is_root: false
weight: 140
---


## SizeSearchCriteria class

Filigran boyutuna göre filtrelemeye izin veren kriterleri temsil eder.

Daha fazla bilgi edinin:
- https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

SizeSearchCriteria türü aşağıdaki üyeleri gösterir:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/sizesearchcriteria/__init__/#dimension-min-max) | Belirtilen bir boyut, başlangıç değeri ve bitiş değeri ile yeni bir SizeSearchCriteria sınıfı örneği başlatır. |

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
| [dimension](/watermark/python-net/groupdocs.watermark.search.search_criteria/sizesearchcriteria/dimension/) | Aranacak filigranın boyutu. |
| [maximum](/watermark/python-net/groupdocs.watermark.search.search_criteria/sizesearchcriteria/maximum/) | Bitiş değeri. |
| [minimum](/watermark/python-net/groupdocs.watermark.search.search_criteria/sizesearchcriteria/minimum/) | Başlangıç değeri. |

### Örnek

```python
import re
from groupdocs.watermark import Watermarker
from groupdocs.watermark.common import Dimension
from groupdocs.watermark.search.search_criteria import SizeSearchCriteria, RotateAngleSearchCriteria, TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    width_range = SizeSearchCriteria(Dimension.WIDTH, 50, 100)
    rotate_angle = RotateAngleSearchCriteria(0, 45)
    text_criteria = TextSearchCriteria(re.compile(r"^Test watermark$"))
    watermarks = watermarker.search(text_criteria.and_(width_range.or_(rotate_angle)))
    watermarks.clear()
    watermarker.save("./output.pdf")
```

### Ayrıca Bakınız
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
