---
title: "RotateAngleSearchCriteria κλάση"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά κριτήρια που επιτρέπουν φιλτράρισμα κατά γωνία περιστροφής υδατογραφίας."
type: docs
url: /el/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/
is_root: false
weight: 120
---


## RotateAngleSearchCriteria class

Αναπαριστά κριτήρια που επιτρέπουν φιλτράρισμα κατά γωνία περιστροφής υδατογραφίας.

Μάθετε περισσότερα:
- Searching watermarks (https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

Ο τύπος RotateAngleSearchCriteria εκθέτει τα παρακάτω μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/__init__/#min_angle-max_angle) | Αρχικοποιεί ένα νέο RotateAngleSearchCriteria με γωνία έναρξης και γωνία λήξης. |

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
| [maximum_angle](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/maximum_angle/) | Η γωνία λήξης σε μοίρες. |
| [minimum_angle](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/minimum_angle/) | Η γωνία έναρξης σε μοίρες. |

### Παράδειγμα

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
Οδηγοί εργασιών που χρησιμοποιούν `RotateAngleSearchCriteria`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Δείτε επίσης
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
