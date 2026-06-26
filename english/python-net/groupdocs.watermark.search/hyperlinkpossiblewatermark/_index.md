---
title: HyperlinkPossibleWatermark class
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Represents a possible hyperlink watermark in PowerPoint content."
type: docs
url: /python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/
is_root: false
weight: 60
---


## HyperlinkPossibleWatermark class

Represents a possible hyperlink watermark in PowerPoint content.

The HyperlinkPossibleWatermark type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/height/) | The height of this HyperlinkPossibleWatermark. |
| [parent](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/parent/) | The parent of this [`HyperlinkPossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/). |
| [rotate_angle](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/rotate_angle/) | The rotate angle of this [`HyperlinkPossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/) in degrees. |
| [text](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/text/) | The URL of this HyperlinkPossibleWatermark. |
| [unit_of_measurement](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/unit_of_measurement/) | The unit of measurement of this [`HyperlinkPossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/). |
| [width](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/width/) | The width of this [`HyperlinkPossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/). |
| [x](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/x/) | The x-coordinate of this HyperlinkPossibleWatermark. |
| [y](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/y/) | The y-coordinate of this [`HyperlinkPossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/). |
| [formatted_text_fragments](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/formatted_text_fragments/) | The collection of formatted text fragments of this [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/). (inherited from [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [image_data](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/image_data/) | The image of this [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/), or `None` if the watermark has no image. (inherited from [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [page_number](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/page_number/) | The page number where the watermark is placed. (inherited from [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |

### Example

```python
import re
import groupdocs.watermark as gw
import groupdocs.watermark.search.searchcriteria as gws_sc
import groupdocs.watermark.search as gws

with gw.Watermarker("document.pdf") as watermarker:
    possible = watermarker.search(gws_sc.TextSearchCriteria(re.compile(r"someurl\.com")))
    # iterate backwards when removing by index
    for i in range(possible.count - 1, -1, -1):
        if isinstance(possible[i], gws.HyperlinkPossibleWatermark):
            print(possible[i].text)
            possible.remove_at(i)

    watermarker.save("document.pdf")
```

### Guides
Task guides that use `HyperlinkPossibleWatermark`:

* [Removing found watermarks](/watermark/python-net/guides/removing-found-watermarks/)

### See Also
* module [`groupdocs.watermark.search`](/watermark/python-net/groupdocs.watermark.search/)
