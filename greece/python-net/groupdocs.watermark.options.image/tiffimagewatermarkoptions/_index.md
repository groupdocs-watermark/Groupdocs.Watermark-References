---
title: "TiffImageWatermarkOptions κλάση"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά επιλογές προσθήκης υδατογραφήματος κατά την προσθήκη υδατογραφήματος σε μια εικόνα TIFF."
type: docs
url: /el/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/
is_root: false
weight: 100
---


## TiffImageWatermarkOptions class

Αναπαριστά επιλογές προσθήκης υδατογραφήματος κατά την προσθήκη υδατογραφήματος σε μια εικόνα TIFF.

Μάθετε περισσότερα:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images

Ο τύπος TiffImageWatermarkOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/__init__/) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [`TiffImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/). |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/__init__/#frame_index) | Αρχικοποιεί ένα νέο στιγμιότυπο του [`TiffImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/) με έναν καθορισμένο δείκτη πλαισίου. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [frame_index](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frame_index/) | Ο δείκτης του πλαισίου για την προσθήκη υδατογραφήματος. (κληρονομείται από [`MultiframeImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/)) |

### Πεδία
| Πεδίο | Περιγραφή |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Λαμβάνει την προεπιλεγμένη τιμή για την κλάση. (κληρονομείται από [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

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
