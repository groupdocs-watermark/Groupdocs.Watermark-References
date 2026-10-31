---
title: "PresentationWatermarkableImage κλάση"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει μια εικόνα μέσα σε ένα έγγραφο PowerPoint."
type: docs
url: /el/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/
is_root: false
weight: 250
---


## PresentationWatermarkableImage class

Αντιπροσωπεύει μια εικόνα μέσα σε ένα έγγραφο PowerPoint.

Ο τύπος PresentationWatermarkableImage εκθέτει τα παρακάτω μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/__init__/#image_data) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/) χρησιμοποιώντας τα καθορισμένα δεδομένα εικόνας. |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [add](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add/) | Προσθέτει ένα υδατογράφημα σε αυτήν τη [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/). Αυτή η μέθοδος υποθέτει ότι η μετατόπιση και το μέγεθος του υδατογραφήματος μετρώνται σε εικονοστοιχεία (αν έχουν οριστεί). (κληρονομείται από τη [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [add_watermark](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add_watermark/) | (κληρονομείται από τη [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Βρίσκει εικόνες σύμφωνα με τα καθορισμένα κριτήρια αναζήτησης. Η αναζήτηση πραγματοποιείται στα αντικείμενα που ορίζονται στο [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (κληρονομείται από το [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (κληρονομείται από το [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [get_bytes](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/get_bytes/) | Λαμβάνει την εικόνα ως πίνακα byte. (κληρονομείται από τη [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Βρίσκει πιθανά υδατογραφήματα σύμφωνα με τα καθορισμένα κριτήρια αναζήτησης. Η αναζήτηση εκτελείται στα αντικείμενα που αναφέρονται στο [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (κληρονομείται από το [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (κληρονομείται από το [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/height/) | Το ύψος αυτής της [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) σε εικονοστοιχεία. (κληρονομείται από τη [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [width](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/width/) | Το πλάτος αυτής της WatermarkableImage σε εικονοστοιχεία. (κληρονομείται από τη [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |

### Παράδειγμα

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.presentation as gwc_ppt

with open("image.png", "rb") as f:
    img = gwc_ppt.PresentationWatermarkableImage(f.read())
```

### Δείτε επίσης
* module [`groupdocs.watermark.contents.presentation`](/watermark/python-net/groupdocs.watermark.contents.presentation/)
