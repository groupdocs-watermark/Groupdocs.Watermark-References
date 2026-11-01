---
title: "MeasureValue sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Belirli bir tip ve sayısal değerle bir ölçüm değerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.watermark.watermarks/measurevalue/
is_root: false
weight: 70
---


## MeasureValue class

Belirli bir tip ve sayısal değerle bir ölçüm değerini temsil eder.

MeasureValue türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/__init__/) |  |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [measure_type](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/measure_type/) | Ölçüm türü. |
| [value](/watermark/python-net/groupdocs.watermark.watermarks/measurevalue/value/) | Ölçümün sayısal değeri; 0'dan büyük olmalıdır. |

### Örnek

```python
from groupdocs.watermark.watermarks import MeasureValue, TileMeasureType

# Sayfanın yüzdesi olarak ifade edilen bir ölçüm oluşturun
spacing = MeasureValue()
spacing.measure_type = TileMeasureType.PERCENT
spacing.value = 12.0
```

### Guides
`MeasureValue` kullanan görev kılavuzları:

* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### Ayrıca Bakınız
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
