---
title: "Κλάση PdfAnnotationWatermarkOptions"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει επιλογές προσθήκης υδατογραφήματος κατά την προσθήκη ενός υδατογραφήματος σχολίου σε ένα έγγραφο PDF."
type: docs
url: /el/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/
is_root: false
weight: 10
---


## PdfAnnotationWatermarkOptions class

Αντιπροσωπεύει επιλογές προσθήκης υδατογραφήματος κατά την προσθήκη ενός υδατογραφήματος σχολίου σε ένα έγγραφο PDF.

Μάθετε περισσότερα:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents

Ο τύπος PdfAnnotationWatermarkOptions εκθέτει τα παρακάτω μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/__init__/) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [`PdfAnnotationWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/). |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [page_index](/watermark/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/page_index/) | Ο δείκτης σελίδας στο οποίο θα προστεθεί το υδατογράφημα. |
| [print_only](/watermark/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/print_only/) | Η τιμή που υποδεικνύει αν η σημείωση θα εκτυπωθεί αλλά δεν θα εμφανιστεί σε εφαρμογή προβολής PDF. |

### Πεδία
| Πεδίο | Περιγραφή |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Λαμβάνει την προεπιλεγμένη τιμή για την κλάση. (κληρονομείται από [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark
from groupdocs.watermark.options.pdf import PdfLoadOptions, PdfAnnotationWatermarkOptions

def add_annotation_image_watermark():
    load_options = PdfLoadOptions()
    with Watermarker("./test.pdf", load_options) as watermarker:
        with ImageWatermark("./icon.png") as watermark:
            options = PdfAnnotationWatermarkOptions()
            # PageIndex = -1 εφαρμόζει το υδατογράφημα σε όλες τις σελίδες (προεπιλογή).
            watermarker.add(watermark, options)
        watermarker.save("./output.pdf")
```

### Δείτε επίσης
* module [`groupdocs.watermark.options.pdf`](/watermark/python-net/groupdocs.watermark.options.pdf/)
