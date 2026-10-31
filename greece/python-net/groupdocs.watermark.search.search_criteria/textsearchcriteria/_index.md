---
title: "TextSearchCriteria κλάση"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά κριτήρια που επιτρέπουν φιλτράρισμα κατά κείμενο υδατογραφίας."
type: docs
url: /el/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/
is_root: false
weight: 160
---


## TextSearchCriteria class

Αναπαριστά κριτήρια που επιτρέπουν φιλτράρισμα κατά κείμενο υδατογραφίας.

Μάθετε περισσότερα:
- [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

Ο τύπος TextSearchCriteria εκθέτει τα παρακάτω μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/#pattern) | Αρχικοποιεί ένα νέο TextSearchCriteria με καθορισμένη κανονική έκφραση. |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/#search_string-is_match_case) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) με μια συμβολοσειρά αναζήτησης και μια σημαία για σύγκριση με διάκριση πεζών-κεφαλαίων. |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/#search_string) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) με μια συμβολοσειρά αναζήτησης. |

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
| [pattern](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/pattern/) | Το πρότυπο κανονικής έκφρασης για αντιστοίχιση. |
| [skip_unreadable_characters](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/skip_unreadable_characters/) | Η ιδιότητα που υποδεικνύει εάν οι μη αναγνώσιμα χαρακτήρες παραλείπονται κατά τη σύγκριση συμβολοσειρών. |
| [pages](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/pages/) | Η λίστα των συγκεκριμένων αριθμών σελίδων. (κληρονομείται από [`PageSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/pagesearchcriteria/)) |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def search_by_text():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_text()
```

### Guides
Οδηγοί εργασιών που χρησιμοποιούν `TextSearchCriteria`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)
* [Update watermarks](/watermark/python-net/guides/update/)
* [Clear watermarks](/watermark/python-net/guides/clear/)

### Δείτε επίσης
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
