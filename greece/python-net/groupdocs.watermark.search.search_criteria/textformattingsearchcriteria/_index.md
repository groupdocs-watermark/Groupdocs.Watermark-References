---
title: "TextFormattingSearchCriteria κλάση"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά κριτήρια που επιτρέπουν φιλτράρισμα κατά μορφοποίηση κειμένου."
type: docs
url: /el/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/
is_root: false
weight: 150
---


## TextFormattingSearchCriteria class

Αναπαριστά κριτήρια που επιτρέπουν φιλτράρισμα κατά μορφοποίηση κειμένου.

Μάθετε περισσότερα:
- Searching watermarks (https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

Ο τύπος TextFormattingSearchCriteria εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/__init__/) | Αρχικοποιεί μια νέα παρουσία του [`TextFormattingSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/). |

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
| [background_color_range](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/background_color_range/) | Η περιοχή χρωμάτων που χρησιμοποιείται για το φιλτράρισμα των υδατογραφημάτων με βάση το χρώμα φόντου κειμένου. |
| [font_bold](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/font_bold/) | Η γραμματοσειρά που χρησιμοποιείται στη μορφοποίηση κειμένου υδατογράφησης είναι έντονη. |
| [font_italic](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/font_italic/) | Η ιδιότητα font_italic υποδεικνύει εάν η γραμματοσειρά κειμένου υδατογράφησης είναι πλάγια. |
| [font_name](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/font_name/) | Το όνομα της γραμματοσειράς που χρησιμοποιείται σε πιθανή μορφοποίηση κειμένου υδατογράφησης. |
| [font_strikeout](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/font_strikeout/) | Η σημαία strikeout της γραμματοσειράς για τη μορφοποίηση κειμένου υδατογράφησης. |
| [font_underline](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/font_underline/) | Η σημαία underline της γραμματοσειράς που υποδεικνύει εάν το κείμενο υδατογράφησης χρησιμοποιεί υπογράμμιση. |
| [foreground_color_range](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/foreground_color_range/) | Η περιοχή χρωμάτων που χρησιμοποιείται για το φιλτράρισμα υδατογραφιών κατά χρώμα προσκηνίου κειμένου. |
| [max_font_size](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/max_font_size/) | Η τελική τιμή του μεγέθους γραμματοσειράς. |
| [min_font_size](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/min_font_size/) | Η αρχική τιμή του μεγέθους γραμματοσειράς. |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextFormattingSearchCriteria, ColorRange

def search_by_formatting():
    with Watermarker("./document.pdf") as watermarker:
        criteria = TextFormattingSearchCriteria()
        criteria.foreground_color_range = ColorRange()
        criteria.foreground_color_range.min_hue = -15
        criteria.foreground_color_range.max_hue = 15
        criteria.foreground_color_range.min_brightness = 0.01
        criteria.foreground_color_range.max_brightness = 0.99
        criteria.min_font_size = 19
        criteria.max_font_size = 42

        possible = watermarker.search(criteria)
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_formatting()
```

### Guides
Οδηγοί εργασιών που χρησιμοποιούν `TextFormattingSearchCriteria`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Δείτε επίσης
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
