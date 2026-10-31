---
title: "SizeSearchCriteria κλάση"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά κριτήρια που επιτρέπουν φιλτράρισμα κατά μέγεθος υδατογραφίας."
type: docs
url: /el/python-net/groupdocs.watermark.search.search_criteria/sizesearchcriteria/
is_root: false
weight: 140
---


## SizeSearchCriteria class

Αναπαριστά κριτήρια που επιτρέπουν φιλτράρισμα κατά μέγεθος υδατογραφίας.

Μάθετε περισσότερα:
- https://docs.groupdocs.com/display/watermarknet/Searching+watermarks

Ο τύπος SizeSearchCriteria εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/sizesearchcriteria/__init__/#dimension-min-max) | Αρχικοποιεί μια νέα παρουσία της κλάσης SizeSearchCriteria με καθορισμένη διάσταση, μια αρχική τιμή και μια τελική τιμή. |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [and_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/) | Συνδυάζει αυτό το SearchCriteria με άλλα κριτήρια χρησιμοποιώντας τον λογικό τελεστή AND. (κληρονομείται από [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [and_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_search_criteria/) | (κληρονομείται από [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [not_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/) | Αντιστρέφει αυτό το SearchCriteria. (κληρονομείται από [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [or_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/) | Συνδυάζει αυτό το SearchCriteria με άλλα κριτήρια χρησιμοποιώντας τον λογικό τελεστή OR. (κληρονομείται από [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [or_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_search_criteria/) | (κληρονομείται από [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [dimension](/watermark/python-net/groupdocs.watermark.search.search_criteria/sizesearchcriteria/dimension/) | Η διάσταση του υδατογραφήματος για αναζήτηση. |
| [maximum](/watermark/python-net/groupdocs.watermark.search.search_criteria/sizesearchcriteria/maximum/) | Η τελική τιμή. |
| [minimum](/watermark/python-net/groupdocs.watermark.search.search_criteria/sizesearchcriteria/minimum/) | Η αρχική τιμή. |

### Παράδειγμα

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

### Δείτε επίσης
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
