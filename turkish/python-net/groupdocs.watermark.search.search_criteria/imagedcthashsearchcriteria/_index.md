---
title: "ImageDctHashSearchCriteria sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Belgedeki görüntüleri bulmak için bir arama kriterini temsil eder."
type: docs
url: /tr/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/
is_root: false
weight: 40
---


## ImageDctHashSearchCriteria class

Belgedeki görüntüleri bulmak için bir arama kriterini temsil eder.

Bu arama kriteri, görüntü benzerliğini hesaplamak için DCT tabanlı algısal görüntü karmasını kullanır. Daha fazla bilgi edinin: https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

ImageDctHashSearchCriteria türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/__init__/#file_path) | Belirtilen dosya yolu ile yeni bir ImageDctHashSearchCriteria örneği başlatır. |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/__init__/#stream) | Sağlanan görüntü akışı ile yeni bir ImageDctHashSearchCriteria örneği başlatır. |

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
| [max_difference](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagesearchcriteria/max_difference/) | Görüntüler arasındaki izin verilen maksimum fark. ([`ImageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagesearchcriteria/) üzerinden devralınmıştır) |
| [pages](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/pages/) | Belirli sayfa numaralarının listesi. ([`PageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/) üzerinden devralınmıştır) |

### Örnek

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

def clear_image_watermark():
    with Watermarker("./watermarked-document.docx") as watermarker:
        criteria = ImageDctHashSearchCriteria("./logo.png")
        criteria.max_difference = 0.9
        possible = watermarker.search(criteria)
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.docx")
```

### Guides
`ImageDctHashSearchCriteria` kullanan görev kılavuzları:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)
* [Update watermarks](/watermark/python-net/guides/update/)
* [Clear watermarks](/watermark/python-net/guides/clear/)

### Ayrıca Bakınız
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
