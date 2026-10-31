---
title: "PresentationWatermarkBaseSlideOptions κλάση"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Βασική κλάση για τις επιλογές προσθήκης υδατογραφήματος σε ένα έγγραφο Presentation."
type: docs
url: /el/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/
is_root: false
weight: 70
---


## PresentationWatermarkBaseSlideOptions class

Βασική κλάση για τις επιλογές προσθήκης υδατογραφήματος σε ένα έγγραφο Presentation.

Μάθετε περισσότερα:
- Add watermarks to presentation documents: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents

Ο τύπος PresentationWatermarkBaseSlideOptions εκθέτει τα ακόλουθα μέλη:

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/alternative_text/) | Το περιγραφικό (εναλλακτικό) κείμενο που θα συσχετιστεί με ένα σχήμα. |
| [effects](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/effects/) | Τα εφέ που θα εφαρμοστούν στο υδατογράφημα, καθορισμένα ως ένα αντικείμενο [`PresentationImageEffects`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationimageeffects/) ή [`PresentationTextEffects`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationtexteffects/). |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/is_locked/) | Η ιδιότητα υποδεικνύει εάν η επεξεργασία του σχήματος στο PowerPoint απαγορεύεται. |
| [name](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/name/) | Το όνομα του σχήματος. |
| [protect_with_unreadable_characters](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/protect_with_unreadable_characters/) | Η ιδιότητα που υποδεικνύει εάν οι χαρακτήρες του κειμενικού υδατογραφήματος είναι αναμεμιγμένοι με μη αναγνώσιμους χαρακτήρες. |

### Πεδία
| Πεδίο | Περιγραφή |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Λαμβάνει την προεπιλεγμένη τιμή για την κλάση. (κληρονομείται από [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.presentation import PresentationWatermarkMasterSlideOptions
from groupdocs.watermark.options.presentation import PresentationWatermarkLayoutSlideOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

with Watermarker("./presentation.pptx") as watermarker:
    watermark = TextWatermark("Test watermark", Font("Arial", 8.0))

    master_options = PresentationWatermarkMasterSlideOptions()
    master_options.master_slide_index = 0
    watermarker.add(watermark, master_options)

    layout_options = PresentationWatermarkLayoutSlideOptions()
    layout_options.layout_slide_index = 0
    watermarker.add(watermark, layout_options)

    watermarker.save("./output.pptx")
```

### Δείτε επίσης
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
