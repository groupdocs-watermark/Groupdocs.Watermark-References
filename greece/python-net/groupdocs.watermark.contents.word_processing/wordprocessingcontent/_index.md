---
title: "Κλάση WordProcessingContent"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει ένα έγγραφο Word (doc, docx, κ.λπ.) όπου μπορεί να τοποθετηθεί υδατογράφημα."
type: docs
url: /el/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/
is_root: false
weight: 10
---


## WordProcessingContent class

Αντιπροσωπεύει ένα έγγραφο Word (doc, docx, κ.λπ.) όπου μπορεί να τοποθετηθεί υδατογράφημα.

Μάθετε περισσότερα:
- Add watermarks to word processing documents: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents
- Existing objects in word processing document: https://docs.groupdocs.com/display/watermarknet/Existing+objects+in+word+processing+document
- Locking watermark in word processing document: https://docs.groupdocs.com/display/watermarknet/Locking+watermark+in+word+processing+document
- Protecting word processing documents: https://docs.groupdocs.com/display/watermarknet/Protecting+word+processing+documents
- Watermarks in word processing document: https://docs.groupdocs.com/display/watermarknet/Watermarks+in+word+processing+document

Ο τύπος WordProcessingContent εκθέτει τα ακόλουθα μέλη:

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [decrypt](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/decrypt/) | Αποκρυπτογραφεί το έγγραφο. |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/encrypt/#password) | Κρυπτογραφεί το έγγραφο. |
| [encrypt_file](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/encrypt_file/) |  |
| [encrypt_string](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/encrypt_string/) |  |
| [protect](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect/#protection_type-password) | Προστατεύει το έγγραφο από αλλαγές και ορίζει κωδικό προστασίας. |
| [protect_file](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect_file/) |  |
| [protect_string](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect_string/) |  |
| [protect_word_processing_protection_type](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect_word_processing_protection_type/) |  |
| [unprotect](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/unprotect/) | Αφαιρεί την προστασία από το έγγραφο ανεξάρτητα από τον κωδικό. |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | Αποδεσμεύει την τρέχουσα παρουσία. (κληρονομείται από το [`Content`](/watermark/python-net/groupdocs.watermark.contents/content/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Βρίσκει εικόνες σύμφωνα με τα καθορισμένα κριτήρια αναζήτησης. Η αναζήτηση πραγματοποιείται στα αντικείμενα που ορίζονται στο [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (κληρονομείται από το [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (κληρονομείται από το [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Βρίσκει πιθανά υδατογραφήματα σύμφωνα με τα καθορισμένα κριτήρια αναζήτησης. Η αναζήτηση εκτελείται στα αντικείμενα που αναφέρονται στο [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (κληρονομείται από το [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (κληρονομείται από το [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [page_count](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/page_count/) | Ο αριθμός των σελίδων στο έγγραφο. |
| [sections](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/sections/) | Η συλλογή όλων των ενοτήτων αυτού του [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/). |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

load_options = WordProcessingLoadOptions()
with Watermarker("input.docx", load_options) as watermarker:
    # Προσθέστε υδατογράφημα σε μια συγκεκριμένη ή σε όλες τις ενότητες εδώ, εάν χρειάζεται.
    watermarker.save("output.docx")
```

### Δείτε επίσης
* module [`groupdocs.watermark.contents.word_processing`](/watermark/python-net/groupdocs.watermark.contents.word_processing/)
