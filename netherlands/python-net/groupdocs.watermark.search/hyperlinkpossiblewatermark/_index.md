---
title: "HyperlinkPossibleWatermark klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Stelt een mogelijke hyperlink-watermark voor in een PowerPoint-inhoud."
type: docs
url: /nl/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/
is_root: false
weight: 60
---


## HyperlinkPossibleWatermark class

Stelt een mogelijke hyperlink-watermark voor in een PowerPoint-inhoud.

Het HyperlinkPossibleWatermark-type exposeert de volgende leden:

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/height/) | De hoogte van deze HyperlinkPossibleWatermark. |
| [parent](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/parent/) | De ouder van deze HyperlinkPossibleWatermark. |
| [rotate_angle](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/rotate_angle/) | De rotatiehoek van deze HyperlinkPossibleWatermark in graden. |
| [text](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/text/) | De URL van deze HyperlinkPossibleWatermark. |
| [unit_of_measurement](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/unit_of_measurement/) | De meeteenheid van deze [`HyperlinkPossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/). |
| [width](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/width/) | De breedte van deze HyperlinkPossibleWatermark. |
| [x](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/x/) | De x-coördinaat van deze HyperlinkPossibleWatermark. |
| [y](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/y/) | De y-coördinaat van deze [`HyperlinkPossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/). |
| [formatted_text_fragments](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/formatted_text_fragments/) | De verzameling van geformatteerde tekstfragmenten van deze [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/). (geërfd van [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [image_data](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/image_data/) | De afbeelding van deze [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) of None als het watermerk geen afbeelding heeft. (geërfd van [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [page_number](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/page_number/) | Het paginanummer waarop het watermerk is geplaatst. (geërfd van [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |

### Voorbeeld

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

### Zie ook
* module [`groupdocs.watermark.search`](/watermark/python-net/groupdocs.watermark.search/)
