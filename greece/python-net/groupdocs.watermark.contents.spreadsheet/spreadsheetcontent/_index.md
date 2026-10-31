---
title: "Κλάση SpreadsheetContent"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει ένα έγγραφο Excel όπου μπορεί να τοποθετηθεί υδατογράφημα."
type: docs
url: /el/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/
is_root: false
weight: 80
---


## SpreadsheetContent class

Αντιπροσωπεύει ένα έγγραφο Excel όπου μπορεί να τοποθετηθεί υδατογράφημα.

Μάθετε περισσότερα:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents
- https://docs.groupdocs.com/display/watermarknet/Shapes+in+spreadsheet+document
- https://docs.groupdocs.com/display/watermarknet/Working+with+spreadsheet+document+attachments
- https://docs.groupdocs.com/display/watermarknet/Working+with+worksheet+backgrounds
- https://docs.groupdocs.com/display/watermarknet/Working+with+worksheet+headers+and+footers

Ο τύπος SpreadsheetContent εκθέτει τα ακόλουθα μέλη:

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [decrypt](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/decrypt/) | Αποκρυπτογραφεί το έγγραφο. |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/encrypt/#password) | Κρυπτογραφεί το περιεχόμενο. |
| [encrypt_file](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/encrypt_file/) |  |
| [encrypt_string](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/encrypt_string/) |  |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | Αποδεσμεύει την τρέχουσα παρουσία. (κληρονομείται από το [`Content`](/watermark/python-net/groupdocs.watermark.contents/content/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Βρίσκει εικόνες σύμφωνα με τα καθορισμένα κριτήρια αναζήτησης. Η αναζήτηση πραγματοποιείται στα αντικείμενα που ορίζονται στο [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (κληρονομείται από το [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (κληρονομείται από το [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Βρίσκει πιθανά υδατογραφήματα σύμφωνα με τα καθορισμένα κριτήρια αναζήτησης. Η αναζήτηση εκτελείται στα αντικείμενα που αναφέρονται στο [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (κληρονομείται από το [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (κληρονομείται από το [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [worksheets](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/worksheets/) | Η συλλογή όλων των φύλλων εργασίας αυτού του [`SpreadsheetContent`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/). |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions

load_options = SpreadsheetLoadOptions()
with Watermarker(r"D:\input.xls", load_options) as watermarker:
    # Χρησιμοποιήστε τη μέθοδο add για να προσθέσετε υδατογράφημα σε ένα συγκεκριμένο ή σε όλα τα φύλλα εργασίας.
    watermarker.save(r"D:\output.xls")
```

### Δείτε επίσης
* module [`groupdocs.watermark.contents.spreadsheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/)
