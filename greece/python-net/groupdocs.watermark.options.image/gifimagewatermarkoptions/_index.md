---
title: "GifImageWatermarkOptions κλάση"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά επιλογές προσθήκης υδατογραφήματος κατά την προσθήκη υδατογραφήματος σε μια εικόνα GIF."
type: docs
url: /el/python-net/groupdocs.watermark.options.image/gifimagewatermarkoptions/
is_root: false
weight: 30
---


## GifImageWatermarkOptions class

Αναπαριστά επιλογές προσθήκης υδατογραφήματος κατά την προσθήκη υδατογραφήματος σε μια εικόνα GIF.

Μάθετε περισσότερα:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images

Ο τύπος GifImageWatermarkOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/gifimagewatermarkoptions/__init__/) | Αρχικοποιεί ένα νέο παράδειγμα της κλάσης [`GifImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/gifimagewatermarkoptions/) |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/gifimagewatermarkoptions/__init__/#frame_index) | Αρχικοποιεί ένα νέο παράδειγμα της κλάσης [`GifImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/gifimagewatermarkoptions/) με καθορισμένο δείκτη πλαισίου. |

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
from groupdocs.watermark.options.image import GifImageLoadOptions, GifImageWatermarkOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

load_options = GifImageLoadOptions()
with Watermarker(r"C:\test.gif", load_options) as watermarker:
    watermark = TextWatermark("Test", Font("Arial", 12))

    options = GifImageWatermarkOptions()
    options.frame_index = 0

    watermarker.add(watermark, options)
    watermarker.save()
```

### Δείτε επίσης
* module [`groupdocs.watermark.options.image`](/watermark/python-net/groupdocs.watermark.options.image/)
