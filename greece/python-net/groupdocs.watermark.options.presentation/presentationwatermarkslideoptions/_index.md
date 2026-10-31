---
title: "PresentationWatermarkSlideOptions κλάση"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά τις επιλογές κατά την προσθήκη υδατογραφήματος σε μια διαφάνεια εγγράφου Presentation."
type: docs
url: /el/python-net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/
is_root: false
weight: 140
---


## PresentationWatermarkSlideOptions class

Αναπαριστά τις επιλογές κατά την προσθήκη υδατογραφήματος σε μια διαφάνεια εγγράφου Presentation.

Μάθετε περισσότερα:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents

Ο τύπος PresentationWatermarkSlideOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/__init__/) | Δημιουργεί ένα νέο αντικείμενο της κλάσης [`PresentationWatermarkSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/) class. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [slide_index](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/slide_index/) | Ο δείκτης της διαφάνειας στην οποία θα προστεθεί το υδατογράφημα. |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/alternative_text/) | Το περιγραφικό (εναλλακτικό) κείμενο που θα συσχετιστεί με ένα σχήμα. (κληρονομείται από [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |
| [effects](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/effects/) | Τα εφέ που θα εφαρμοστούν στο υδατογράφημα, καθορισμένα ως μια παρουσία του [`PresentationImageEffects`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationimageeffects/) ή του [`PresentationTextEffects`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationtexteffects/). (κληρονομείται από [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/is_locked/) | Η ιδιότητα υποδεικνύει εάν η επεξεργασία του σχήματος στο PowerPoint απαγορεύεται. (κληρονομείται από [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |
| [name](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/name/) | Το όνομα του σχήματος. (κληρονομείται από [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |
| [protect_with_unreadable_characters](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/protect_with_unreadable_characters/) | Η ιδιότητα που υποδεικνύει εάν οι χαρακτήρες του κειμένου υδατογραφήματος αναμιγνύονται με μη αναγνώσιμους χαρακτήρες. (κληρονομείται από [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |

### Πεδία
| Πεδίο | Περιγραφή |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Λαμβάνει την προεπιλεγμένη τιμή για την κλάση. (κληρονομείται από [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment
from groupdocs.watermark.options.presentation import (
    PresentationLoadOptions, PresentationWatermarkSlideOptions,
)

def add_watermark_to_slide():
    with Watermarker("./presentation.pptx", PresentationLoadOptions()) as watermarker:
        watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 19.0))
        watermark.foreground_color = Color.red
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER

        options = PresentationWatermarkSlideOptions()
        options.slide_index = 0
        watermarker.add(watermark, options)

        watermarker.save("./output.pptx")
```

### Δείτε επίσης
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
