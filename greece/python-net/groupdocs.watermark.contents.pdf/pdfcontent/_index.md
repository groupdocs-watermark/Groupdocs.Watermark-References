---
title: "PdfContent κλάση"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει ένα PDF έγγραφο όπου μπορεί να τοποθετηθεί υδατογράφημα."
type: docs
url: /el/python-net/groupdocs.watermark.contents.pdf/pdfcontent/
is_root: false
weight: 100
---


## PdfContent class

Αντιπροσωπεύει ένα PDF έγγραφο όπου μπορεί να τοποθετηθεί υδατογράφημα.

Μάθετε περισσότερα:
- [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)
- [Existing objects in PDF document](https://docs.groupdocs.com/display/watermarknet/Existing+objects+in+PDF+document)
- [Rasterize document or page](https://docs.groupdocs.com/display/watermarknet/Rasterize+document+or+page)
- [Watermarks in PDF document](https://docs.groupdocs.com/display/watermarknet/Watermarks+in+PDF+document)

Ο τύπος PdfContent εκθέτει τα ακόλουθα μέλη:

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [decrypt](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/decrypt/) | Αποκρυπτογραφεί το περιεχόμενο. |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/#password) | Κρυπτογραφεί το έγγραφο χρησιμοποιώντας τον ίδιο κωδικό πρόσβασης ως κωδικό χρήστη και κωδικό ιδιοκτήτη. |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/#user_password-owner_password-permissions-crypto_algorithm) | Κρυπτογραφεί το περιεχόμενο. |
| [encrypt_file](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt_file/) |  |
| [encrypt_string](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt_string/) |  |
| [rasterize](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/rasterize/#horizontal_resolution-vertical_resolution-image_format) | Μετατρέπει όλες τις σελίδες περιεχομένου σε εικόνες. |
| [rasterize_int32](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/rasterize_int32/) |  |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | Αποδεσμεύει την τρέχουσα παρουσία. (κληρονομείται από το [`Content`](/watermark/python-net/groupdocs.watermark.contents/content/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Βρίσκει εικόνες σύμφωνα με τα καθορισμένα κριτήρια αναζήτησης. Η αναζήτηση πραγματοποιείται στα αντικείμενα που ορίζονται στο [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (κληρονομείται από το [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (κληρονομείται από το [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Βρίσκει πιθανά υδατογραφήματα σύμφωνα με τα καθορισμένα κριτήρια αναζήτησης. Η αναζήτηση εκτελείται στα αντικείμενα που αναφέρονται στο [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (κληρονομείται από το [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (κληρονομείται από το [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [attachments](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/attachments/) | Η συλλογή όλων των συνημμένων αυτού του [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/). |
| [page_margin_type](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/page_margin_type/) | Τα περιθώρια σελίδας pdf που θα χρησιμοποιηθούν κατά την προσθήκη υδατογράφησης. |
| [pages](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/pages/) | Η συλλογή όλων των σελίδων αυτού του [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/). |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker

# Φόρτωση αρχείου PDF
watermarker = Watermarker("sample.pdf")

# Ανάκτηση του δέντρου περιεχομένου PDF
pdf_content = watermarker.get_content()

# Επανάληψη στις σελίδες και εκτύπωση των μεγεθών τους
for page in pdf_content.pages:
    print(page.width, page.height)
```

### Δείτε επίσης
* module [`groupdocs.watermark.contents.pdf`](/watermark/python-net/groupdocs.watermark.contents.pdf/)
