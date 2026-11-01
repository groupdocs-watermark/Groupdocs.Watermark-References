---
title: "ColorRange sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "RGB renginin HSB temsili kullanılarak bir renk aralığını temsil eder."
type: docs
url: /tr/python-net/groupdocs.watermark.search.search_criteria/colorrange/
is_root: false
weight: 20
---


## ColorRange class

RGB renginin HSB temsili kullanılarak bir renk aralığını temsil eder.

ColorRange türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/) | `[`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/)` sınıfının yeni bir örneğini başlatır. |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/#exact_color) | `[`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/)` sınıfının belirtilen kesin renk ile yeni bir örneğini başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [is_empty](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/is_empty/) | Sadece boş rengin aralıkta olup olmadığını gösteren bayrak. |
| [max_brightness](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_brightness/) | Bitiş parlaklık değeri, 0.0 (siyah) ile 1.0 (beyaz) arasında. |
| [max_hue](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_hue/) | Bitiş renk tonu değeri, derece cinsinden. |
| [max_saturation](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_saturation/) | Bitiş doygunluk değeri. |
| [min_brightness](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_brightness/) | Başlangıç parlaklık değeri, 0.0 (siyah) ile 1.0 (beyaz) arasında. |
| [min_hue](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_hue/) | Başlangıç renk tonu değeri, derece cinsinden. |
| [min_saturation](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_saturation/) | Başlangıç doygunluk değeri. |

### Örnek

```python
from groupdocs.watermark.search.search_criteria import ColorRange

# Ön plan rengi eşleştirme için bir renk aralığı oluştur
color_range = ColorRange()
color_range.min_hue = -15
color_range.max_hue = 15
color_range.min_brightness = 0.01
color_range.max_brightness = 0.99
```

### Guides
`ColorRange` kullanan görev kılavuzları:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Ayrıca Bakınız
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
