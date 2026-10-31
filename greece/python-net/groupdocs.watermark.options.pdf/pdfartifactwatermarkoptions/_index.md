---
title: "Κλάση PdfArtifactWatermarkOptions"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει επιλογές προσθήκης υδατογραφήματος κατά την προσθήκη ενός υδατογραφήματος αντικειμένου σε ένα έγγραφο PDF."
type: docs
url: /el/python-net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/
is_root: false
weight: 20
---


## PdfArtifactWatermarkOptions class

Αντιπροσωπεύει επιλογές προσθήκης υδατογραφήματος κατά την προσθήκη ενός υδατογραφήματος αντικειμένου σε ένα έγγραφο PDF.

Μάθετε περισσότερα:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents

Ο τύπος PdfArtifactWatermarkOptions εκθέτει τα παρακάτω μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/__init__/) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [`PdfArtifactWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/). |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [page_index](/watermark/python-net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/page_index/) | Ο δείκτης σελίδας στο οποίο θα προστεθεί το υδατογράφημα. |

### Πεδία
| Πεδίο | Περιγραφή |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Λαμβάνει την προεπιλεγμένη τιμή για την κλάση. (κληρονομείται από [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment
from groupdocs.watermark.options.pdf import PdfLoadOptions, PdfArtifactWatermarkOptions

with Watermarker("./test.pdf", PdfLoadOptions()) as watermarker:
    with ImageWatermark("./icon.png") as watermark:
        watermark.horizontal_alignment = HorizontalAlignment.RIGHT
        watermark.vertical_alignment = VerticalAlignment.BOTTOM
        options = PdfArtifactWatermarkOptions()
        options.page_index = -1  # default: all pages
        watermarker.add(watermark, options)
        watermarker.save()
```

### Δείτε επίσης
* module [`groupdocs.watermark.options.pdf`](/watermark/python-net/groupdocs.watermark.options.pdf/)
