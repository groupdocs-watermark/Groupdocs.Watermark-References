---
title: "HyperlinkPossibleWatermark κλάση"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά πιθανό υδατογράφημα υπερσύνδεσμου σε περιεχόμενο PowerPoint."
type: docs
url: /el/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/
is_root: false
weight: 60
---


## HyperlinkPossibleWatermark class

Αναπαριστά πιθανό υδατογράφημα υπερσύνδεσμου σε περιεχόμενο PowerPoint.

Ο τύπος HyperlinkPossibleWatermark εκθέτει τα παρακάτω μέλη:

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/height/) | Το ύψος αυτού του HyperlinkPossibleWatermark. |
| [parent](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/parent/) | Ο γονέας αυτού του HyperlinkPossibleWatermark. |
| [rotate_angle](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/rotate_angle/) | Η γωνία περιστροφής αυτού του HyperlinkPossibleWatermark σε μοίρες. |
| [text](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/text/) | Το URL αυτού του HyperlinkPossibleWatermark. |
| [unit_of_measurement](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/unit_of_measurement/) | Η μονάδα μέτρησης αυτού του [`HyperlinkPossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/). |
| [width](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/width/) | Το πλάτος αυτού του HyperlinkPossibleWatermark. |
| [x](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/x/) | Η συντεταγμένη x αυτού του HyperlinkPossibleWatermark. |
| [y](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/y/) | Η συντεταγμένη y αυτού του [`HyperlinkPossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/). |
| [formatted_text_fragments](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/formatted_text_fragments/) | Η συλλογή μορφοποιημένων τμημάτων κειμένου αυτής της [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/). (κληρονομείται από [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [image_data](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/image_data/) | Η εικόνα αυτής της [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) ή None εάν η υδατογράφημα δεν έχει εικόνα. (κληρονομείται από [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [page_number](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/page_number/) | Ο αριθμός σελίδας όπου τοποθετείται η υδατογράφημα. (κληρονομείται από [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |

### Παράδειγμα

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

### Δείτε επίσης
* module [`groupdocs.watermark.search`](/watermark/python-net/groupdocs.watermark.search/)
