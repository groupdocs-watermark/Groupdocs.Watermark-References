---
title: "MultiframeImageWatermarkOptions κλάση"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά επιλογές προσθήκης υδατογραφήματος κατά την προσθήκη υδατογραφήματος σε μια εικόνα πολλαπλών πλαισίων."
type: docs
url: /el/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/
is_root: false
weight: 70
---


## MultiframeImageWatermarkOptions class

Αναπαριστά επιλογές προσθήκης υδατογραφήματος κατά την προσθήκη υδατογραφήματος σε μια εικόνα πολλαπλών πλαισίων.

Μάθετε περισσότερα: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images

Ο τύπος MultiframeImageWatermarkOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/__init__/) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`MultiframeImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/). |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/__init__/#frame_index) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`MultiframeImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/) με συγκεκριμένο δείκτη του πλαισίου. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [frame_index](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frame_index/) | Ο δείκτης του πλαισίου για την προσθήκη υδατογραφήματος. |

### Πεδία
| Πεδίο | Περιγραφή |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Λαμβάνει την προεπιλεγμένη τιμή για την κλάση. (κληρονομείται από [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.image import ImageLoadOptions, MultiframeImageWatermarkOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

load_options = ImageLoadOptions()
with Watermarker(r"C:\test.gif", load_options) as watermarker:
    watermark = TextWatermark("Test", Font("Arial", 12))
    options = MultiframeImageWatermarkOptions()
    options.frame_index = 0
    watermarker.add(watermark, options)
    watermarker.save()
```

### Δείτε επίσης
* module [`groupdocs.watermark.options.image`](/watermark/python-net/groupdocs.watermark.options.image/)
