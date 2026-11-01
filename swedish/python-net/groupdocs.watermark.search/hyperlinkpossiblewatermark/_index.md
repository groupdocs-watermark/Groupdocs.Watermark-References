---
title: "HyperlinkPossibleWatermark-klass"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Representerar möjlig hyperlänkvattenstämpel i ett PowerPoint-innehåll."
type: docs
url: /sv/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/
is_root: false
weight: 60
---


## HyperlinkPossibleWatermark class

Representerar möjlig hyperlänkvattenstämpel i ett PowerPoint-innehåll.

Typen HyperlinkPossibleWatermark visar följande medlemmar:

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/height/) | Höjden på denna HyperlinkPossibleWatermark. |
| [parent](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/parent/) | Föräldern till denna HyperlinkPossibleWatermark. |
| [rotate_angle](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/rotate_angle/) | Rotationsvinkeln för denna HyperlinkPossibleWatermark i grader. |
| [text](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/text/) | URL:en för denna HyperlinkPossibleWatermark. |
| [unit_of_measurement](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/unit_of_measurement/) | Måttenheten för denna [`HyperlinkPossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/). |
| [width](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/width/) | Bredden på denna HyperlinkPossibleWatermark. |
| [x](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/x/) | X-koordinaten för denna HyperlinkPossibleWatermark. |
| [y](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/y/) | Y-koordinaten för denna [`HyperlinkPossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/). |
| [formatted_text_fragments](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/formatted_text_fragments/) | Samlingen av formaterade textfragment av detta [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/). (ärvd från [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [image_data](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/image_data/) | Bilden av detta [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) eller None om vattenstämpeln inte har någon bild. (ärvd från [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [page_number](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/page_number/) | Sidnumret där vattenstämpeln placeras. (ärvd från [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |

### Exempel

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

### Se även
* module [`groupdocs.watermark.search`](/watermark/python-net/groupdocs.watermark.search/)
