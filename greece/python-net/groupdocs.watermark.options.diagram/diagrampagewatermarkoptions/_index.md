---
title: "DiagramPageWatermarkOptions κλάση"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει τις επιλογές προσθήκης υδατογραφήματος όταν προστίθεται υδατογράφημα σχήματος σε συγκεκριμένη σελίδα ενός εγγράφου Visio."
type: docs
url: /el/python-net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/
is_root: false
weight: 20
---


## DiagramPageWatermarkOptions class

Αντιπροσωπεύει τις επιλογές προσθήκης υδατογραφήματος όταν προστίθεται υδατογράφημα σχήματος σε συγκεκριμένη σελίδα ενός εγγράφου Visio.

Μάθετε περισσότερα:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents

Ο τύπος DiagramPageWatermarkOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/__init__/) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`DiagramPageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/). |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [page_index](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/page_index/) | Ο δείκτης σελίδας στο οποίο θα προστεθεί το υδατογράφημα. |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.diagram/diagramwatermarkoptions/is_locked/) | Η ιδιότητα υποδεικνύει εάν η επεξεργασία του σχήματος στο Visio απαγορεύεται. (κληρονομείται από το [`DiagramWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagramwatermarkoptions/)) |

### Πεδία
| Πεδίο | Περιγραφή |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Λαμβάνει την προεπιλεγμένη τιμή για την κλάση. (κληρονομείται από [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.diagram import DiagramPageWatermarkOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

with Watermarker("./diagram.vsdx") as watermarker:
    watermark = TextWatermark("watermark test", Font("Arial", 42.0))

    options = DiagramPageWatermarkOptions()
    options.is_locked = True
    options.page_index = 0

    watermarker.add(watermark, options)
    watermarker.save("./output.vsdx")
```

### Δείτε επίσης
* module [`groupdocs.watermark.options.diagram`](/watermark/python-net/groupdocs.watermark.options.diagram/)
