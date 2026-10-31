---
title: "PresentationContent κλάση"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει ένα έγγραφο PowerPoint όπου μπορεί να τοποθετηθεί υδατογράφημα."
type: docs
url: /el/python-net/groupdocs.watermark.contents.presentation/presentationcontent/
is_root: false
weight: 60
---


## PresentationContent class

Αντιπροσωπεύει ένα έγγραφο PowerPoint όπου μπορεί να τοποθετηθεί υδατογράφημα.

Μάθετε περισσότερα:
- Add watermarks to presentation documents: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents
- Working with slide backgrounds: https://docs.groupdocs.com/display/watermarknet/Working+with+slide+backgrounds

Ο τύπος PresentationContent εκθέτει τα παρακάτω μέλη:

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [decrypt](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/decrypt/) | Αποκρυπτογραφεί το έγγραφο. |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/encrypt/#password) | Κρυπτογραφεί το έγγραφο. |
| [encrypt_file](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/encrypt_file/) |  |
| [encrypt_string](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/encrypt_string/) |  |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | Αποδεσμεύει την τρέχουσα παρουσία. (κληρονομείται από το [`Content`](/watermark/python-net/groupdocs.watermark.contents/content/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Βρίσκει εικόνες σύμφωνα με τα καθορισμένα κριτήρια αναζήτησης. Η αναζήτηση πραγματοποιείται στα αντικείμενα που ορίζονται στο [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (κληρονομείται από το [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (κληρονομείται από το [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Βρίσκει πιθανά υδατογραφήματα σύμφωνα με τα καθορισμένα κριτήρια αναζήτησης. Η αναζήτηση εκτελείται στα αντικείμενα που αναφέρονται στο [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (κληρονομείται από το [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (κληρονομείται από το [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [layout_slides](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/layout_slides/) | Η συλλογή όλων των διαφανειών διάταξης αυτού του [`PresentationContent`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/). |
| [master_handout_slide](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/master_handout_slide/) | Η κύρια διαφάνεια φυλλάδιου αυτού του [`PresentationContent`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/). |
| [master_notes_slide](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/master_notes_slide/) | Η κύρια διαφάνεια για όλες τις διαφάνειες σημειώσεων αυτού του [`PresentationContent`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/). |
| [master_slides](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/master_slides/) | Η συλλογή όλων των κύριων διαφανειών αυτού του PresentationContent. |
| [notes_slide_height](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/notes_slide_height/) | Το ύψος μιας διαφάνειας σημειώσεων σε σημεία. |
| [notes_slide_width](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/notes_slide_width/) | Το πλάτος μιας διαφάνειας σημειώσεων σε μονάδες σημείου. |
| [slide_height](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/slide_height/) | Το ύψος μιας διαφάνειας σε μονάδες σημείου. |
| [slide_width](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/slide_width/) | Το πλάτος μιας διαφάνειας σε μονάδες σημείου. |
| [slides](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/slides/) | Η συλλογή όλων των διαφανειών αυτού του [`PresentationContent`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/). |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.presentation import PresentationLoadOptions

load_options = PresentationLoadOptions()
with Watermarker(r"D:\input.ppt", load_options) as watermarker:
    # Χρησιμοποιήστε τη μέθοδο add για να προσθέσετε ένα υδατογράφημα σε μια συγκεκριμένη διαφάνεια ή σε όλες τις διαφάνειες.
    watermarker.save(r"D:\output.ppt")
```

### Δείτε επίσης
* module [`groupdocs.watermark.contents.presentation`](/watermark/python-net/groupdocs.watermark.contents.presentation/)
