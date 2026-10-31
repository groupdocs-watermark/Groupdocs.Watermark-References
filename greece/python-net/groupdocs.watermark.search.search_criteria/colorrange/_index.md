---
title: "κλάση ColorRange"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει μια γκάμα χρωμάτων χρησιμοποιώντας την αναπαράσταση HSB του χρώματος RGB."
type: docs
url: /el/python-net/groupdocs.watermark.search.search_criteria/colorrange/
is_root: false
weight: 20
---


## ColorRange class

Αντιπροσωπεύει μια γκάμα χρωμάτων χρησιμοποιώντας την αναπαράσταση HSB του χρώματος RGB.

Ο τύπος ColorRange εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/) | Αρχικοποιεί μια νέα παρουσία της [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) κλάσης. |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/#exact_color) | Αρχικοποιεί μια νέα παρουσία της [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) με ένα καθορισμένο ακριβές χρώμα. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [is_empty](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/is_empty/) | Η σημαία που υποδεικνύει εάν μόνο το κενό χρώμα είναι στην περιοχή. |
| [max_brightness](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_brightness/) | Η τελική τιμή φωτεινότητας, κυμαινόμενη από 0.0 (μαύρο) έως 1.0 (άσπρο). |
| [max_hue](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_hue/) | Η τελική τιμή απόχρωσης, σε μοίρες. |
| [max_saturation](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/max_saturation/) | Η τελική τιμή κορεσμού. |
| [min_brightness](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_brightness/) | Η αρχική τιμή φωτεινότητας, κυμαινόμενη από 0.0 (μαύρο) έως 1.0 (άσπρο). |
| [min_hue](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_hue/) | Η αρχική τιμή απόχρωσης, σε μοίρες. |
| [min_saturation](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/min_saturation/) | Η αρχική τιμή κορεσμού. |

### Παράδειγμα

```python
from groupdocs.watermark.search.search_criteria import ColorRange

# Δημιουργήστε μια περιοχή χρώματος για αντιστοίχιση χρώματος προσκηνίου
color_range = ColorRange()
color_range.min_hue = -15
color_range.max_hue = 15
color_range.min_brightness = 0.01
color_range.max_brightness = 0.99
```

### Guides
Οδηγοί εργασιών που χρησιμοποιούν `ColorRange`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Δείτε επίσης
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
