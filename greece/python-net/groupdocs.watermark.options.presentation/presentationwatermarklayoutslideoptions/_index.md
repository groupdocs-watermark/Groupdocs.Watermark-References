---
title: "Κλάση PresentationWatermarkLayoutSlideOptions"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά τις επιλογές κατά την προσθήκη υδατογραφήματος σε διαφάνεια διάταξης εγγράφου Presentation."
type: docs
url: /el/python-net/groupdocs.watermark.options.presentation/presentationwatermarklayoutslideoptions/
is_root: false
weight: 80
---


## PresentationWatermarkLayoutSlideOptions class

Αναπαριστά τις επιλογές κατά την προσθήκη υδατογραφήματος σε διαφάνεια διάταξης εγγράφου Presentation.

Μάθετε περισσότερα:

- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents

Δείτε τα παραδείγματα χρήσης στο [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/).

Ο τύπος PresentationWatermarkLayoutSlideOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarklayoutslideoptions/__init__/) | Δημιουργεί ένα νέο αντικείμενο της κλάσης [`PresentationWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkoptions/) class. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [layout_slide_index](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarklayoutslideoptions/layout_slide_index/) | Ο δείκτης της διαφάνειας διάταξης στην οποία θα προστεθεί το υδατογράφημα. |
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
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.presentation as gwo_ppt
import groupdocs.watermark.contents.presentation as gwc_ppt

load_options = gwo_ppt.PresentationLoadOptions()
with gw.Watermarker("presentation.pptx", load_options) as watermarker:
    watermark = gww.TextWatermark("Test watermark", gww.Font("Arial", 8.0))
    layout_opts = gwo_ppt.PresentationWatermarkLayoutSlideOptions()
    layout_opts.layout_slide_index = -1  # apply to all layout slides
    watermarker.add(watermark, layout_opts)
```

### Δείτε επίσης
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
