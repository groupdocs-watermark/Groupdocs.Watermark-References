---
title: "SpreadsheetWatermarkShapeOptions κλάση"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά τις επιλογές κατά την προσθήκη υδατογραφήματος σχήματος σε ένα φύλλο εργασίας Spreadsheet."
type: docs
url: /el/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/
is_root: false
weight: 120
---


## SpreadsheetWatermarkShapeOptions class

Αναπαριστά τις επιλογές κατά την προσθήκη υδατογραφήματος σχήματος σε ένα φύλλο εργασίας Spreadsheet.

Μάθετε περισσότερα:
- Add watermarks to spreadsheet documents (https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)

Ο τύπος SpreadsheetWatermarkShapeOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/__init__/) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης SpreadsheetWatermarkShapeOptions. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [effects](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/effects/) | Τα εφέ που εφαρμόζονται στο υδατογράφημα, καθορισμένα ως ένα αντικείμενο [`SpreadsheetImageEffects`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetimageeffects/) ή [`SpreadsheetTextEffects`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheettexteffects/). |
| [worksheet_index](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/worksheet_index/) | Ο δείκτης του φύλλου εργασίας στο οποίο θα προστεθεί το υδατογράφημα. |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/alternative_text/) | Το περιγραφικό (εναλλακτικό) κείμενο που θα συσχετιστεί με ένα σχήμα. (κληρονομείται από το [`SpreadsheetWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/)) |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/is_locked/) | Η ιδιότητα υποδεικνύει αν η επεξεργασία του σχήματος στο Excel απαγορεύεται. (κληρονομείται από το [`SpreadsheetWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/)) |
| [name](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/name/) | Το όνομα του σχήματος. (κληρονομείται από το [`SpreadsheetWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/)) |

### Πεδία
| Πεδίο | Περιγραφή |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Λαμβάνει την προεπιλεγμένη τιμή για την κλάση. (κληρονομείται από [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment
from groupdocs.watermark.options.spreadsheet import (
    SpreadsheetLoadOptions, SpreadsheetWatermarkShapeOptions,
)

def add_watermark_to_worksheet():
    with Watermarker("./spreadsheet.xlsx", SpreadsheetLoadOptions()) as watermarker:
        watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 19.0))
        watermark.foreground_color = Color.red
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER

        options = SpreadsheetWatermarkShapeOptions()
        options.worksheet_index = 0
        watermarker.add(watermark, options)

        watermarker.save("./output.xlsx")
```

### Δείτε επίσης
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
