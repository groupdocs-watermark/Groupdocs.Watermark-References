---
title: "RotateAngleSearchCriteria sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Filigran döndürme açısına göre filtrelemeye izin veren kriterleri temsil eder."
type: docs
url: /tr/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/
is_root: false
weight: 120
---


## RotateAngleSearchCriteria class

Filigran döndürme açısına göre filtrelemeye izin veren kriterleri temsil eder.

Daha fazla bilgi edinin:
- Searching watermarks (https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

RotateAngleSearchCriteria türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/__init__/#min_angle-max_angle) | Başlangıç açısı ve bitiş açısı ile yeni bir RotateAngleSearchCriteria başlatır. |

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
| [maximum_angle](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/maximum_angle/) | Bitiş açısı derece cinsinden. |
| [minimum_angle](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/minimum_angle/) | Başlangıç açısı derece cinsinden. |

### Örnek

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import RotateAngleSearchCriteria

def search_by_angle():
    with Watermarker("./document.pdf") as watermarker:
        angle_criteria = RotateAngleSearchCriteria(30, 60)
        possible = watermarker.search(angle_criteria)
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_angle()
```

### Guides
`RotateAngleSearchCriteria` kullanan görev kılavuzları:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Ayrıca Bakınız
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
