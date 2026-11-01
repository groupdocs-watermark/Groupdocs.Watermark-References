---
title: "HyperlinkPossibleWatermark sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "PowerPoint içeriğinde olası hiperlink filigranını temsil eder."
type: docs
url: /tr/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/
is_root: false
weight: 60
---


## HyperlinkPossibleWatermark class

PowerPoint içeriğinde olası hiperlink filigranını temsil eder.

HyperlinkPossibleWatermark türü aşağıdaki üyeleri sunar:

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/height/) | Bu HyperlinkPossibleWatermark'ın yüksekliği. |
| [parent](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/parent/) | Bu HyperlinkPossibleWatermark'ın üst nesnesi. |
| [rotate_angle](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/rotate_angle/) | Bu HyperlinkPossibleWatermark'ın derece cinsinden döndürme açısı. |
| [text](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/text/) | Bu HyperlinkPossibleWatermark'ın URL'si. |
| [unit_of_measurement](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/unit_of_measurement/) | Bu [`HyperlinkPossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/) ölçüm birimi. |
| [width](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/width/) | Bu HyperlinkPossibleWatermark'ın genişliği. |
| [x](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/x/) | Bu HyperlinkPossibleWatermark'ın x koordinatı. |
| [y](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/y/) | Bu [`HyperlinkPossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/) y koordinatı. |
| [formatted_text_fragments](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/formatted_text_fragments/) | Bu [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) öğesinin biçimlendirilmiş metin parçacıklarının koleksiyonu. ([`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) üzerinden miras alınmıştır) |
| [image_data](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/image_data/) | Bu [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) öğesinin görüntüsü veya watermark'ın görüntüsü yoksa None. ([`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) üzerinden miras alınmıştır) |
| [page_number](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/page_number/) | Watermark'ın yerleştirildiği sayfa numarası. ([`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) üzerinden miras alınmıştır) |

### Örnek

```python
import re
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search import HyperlinkPossibleWatermark
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    possible = watermarker.search(TextSearchCriteria(re.compile(r"someurl\.com")))
    for i in range(len(possible) - 1, -1, -1):
        if isinstance(possible[i], HyperlinkPossibleWatermark):
            print(possible[i].text)
            watermarker.remove(possible[i])
    watermarker.save("./output.pdf")
```

### Ayrıca Bakınız
* module [`groupdocs.watermark.search`](/watermark/python-net/groupdocs.watermark.search/)
