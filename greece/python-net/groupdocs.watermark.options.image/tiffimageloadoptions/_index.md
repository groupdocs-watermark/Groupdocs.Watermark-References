---
title: "TiffImageLoadOptions κλάση"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά επιλογές φόρτωσης εικόνας για μια εικόνα TIFF."
type: docs
url: /el/python-net/groupdocs.watermark.options.image/tiffimageloadoptions/
is_root: false
weight: 80
---


## TiffImageLoadOptions class

Αναπαριστά επιλογές φόρτωσης εικόνας για μια εικόνα TIFF.

Ο τύπος TiffImageLoadOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/tiffimageloadoptions/__init__/) | Αρχικοποιεί μια νέα παρουσία της κλάσης TiffImageLoadOptions. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Ο τύπος του αρχείου, που υποδεικνύει τη μορφή του (π.χ., docx, pdf, xlsx κ.λπ.). (κληρονομείται από την κλάση [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | Η οικογένεια μορφής του εγγράφου, που υποδεικνύει τον τύπο του (π.χ., Image, Pdf, Spreadsheet κ.λπ.). (κληρονομείται από την κλάση [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | Ο κωδικός πρόσβασης για το άνοιγμα ενός κρυπτογραφημένου εγγράφου. (κληρονομείται από την κλάση [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Πεδία
| Πεδίο | Περιγραφή |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.image/tiffimageloadoptions/default/) | Λαμβάνει την προεπιλεγμένη τιμή για την κλάση. |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment
from groupdocs.watermark.options.image import TiffImageLoadOptions, TiffImageWatermarkOptions

with Watermarker("./image.tiff", TiffImageLoadOptions()) as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 19.0))
    watermark.foreground_color = Color.red
    watermark.horizontal_alignment = HorizontalAlignment.CENTER
    watermark.vertical_alignment = VerticalAlignment.CENTER

    options = TiffImageWatermarkOptions()
    options.frame_index = 0
    watermarker.add(watermark, options)

    watermarker.save("./output.tiff")
```

### Δείτε επίσης
* module [`groupdocs.watermark.options.image`](/watermark/python-net/groupdocs.watermark.options.image/)
