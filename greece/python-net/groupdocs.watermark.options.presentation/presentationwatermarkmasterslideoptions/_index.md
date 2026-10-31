---
title: "PresentationWatermarkMasterSlideOptions κλάση"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά τις επιλογές κατά την προσθήκη υδατογραφήματος σε κύρια διαφάνεια εγγράφου Presentation."
type: docs
url: /el/python-net/groupdocs.watermark.options.presentation/presentationwatermarkmasterslideoptions/
is_root: false
weight: 110
---


## PresentationWatermarkMasterSlideOptions class

Αναπαριστά τις επιλογές κατά την προσθήκη υδατογραφήματος σε κύρια διαφάνεια εγγράφου Presentation.

Μάθετε περισσότερα:
- [Add watermarks to presentation documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents)

Δείτε τα παραδείγματα χρήσης στο [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/).

Ο τύπος PresentationWatermarkMasterSlideOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkmasterslideoptions/__init__/) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`PresentationWatermarkMasterSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkmasterslideoptions/) |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [master_slide_index](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkmasterslideoptions/master_slide_index/) | Ο δείκτης της κύριας διαφάνειας στην οποία θα προστεθεί το υδατογράφημα. |
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

watermarker = gw.Watermarker("presentation.pptx")
watermark = gww.TextWatermark("Test watermark", gww.Font("Arial", 8.0))

master_opts = gwo_ppt.PresentationWatermarkMasterSlideOptions()
master_opts.master_slide_index = -1
watermarker.add(watermark, master_opts)
```

### Δείτε επίσης
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
