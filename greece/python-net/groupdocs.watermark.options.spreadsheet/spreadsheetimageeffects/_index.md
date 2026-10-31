---
title: "Κλάση SpreadsheetImageEffects"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά εφέ που μπορούν να εφαρμοστούν σε υδατογραφία εικόνας για έγγραφο Excel."
type: docs
url: /el/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetimageeffects/
is_root: false
weight: 30
---


## SpreadsheetImageEffects class

Αναπαριστά εφέ που μπορούν να εφαρμοστούν σε υδατογραφία εικόνας για έγγραφο Excel.

Ο τύπος SpreadsheetImageEffects εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetimageeffects/__init__/) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`SpreadsheetImageEffects`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetimageeffects/). |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [border_line_format](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/border_line_format/) | Οι ρυθμίσεις μορφής γραμμής για το περίγραμμα της εικόνας. (κληρονομείται από [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [brightness](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/brightness/) | Η φωτεινότητα της εικόνας. Πρέπει να είναι δεκαδικός αριθμός μεταξύ 0.0 (σκοτεινότερη) και 1.0 (φωτεινότερη). Η προεπιλεγμένη τιμή είναι 0.5. (κληρονομείται από [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [chroma_key](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/chroma_key/) | Η τιμή χρώματος της εικόνας που θα θεωρηθεί διαφανής. Η προεπιλεγμένη τιμή είναι ένα πλήρως διαφανές χρώμα. (κληρονομείται από [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [contrast](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/contrast/) | Η αντίθεση για την καθορισμένη εικόνα. Πρέπει να είναι δεκαδικός αριθμός μεταξύ 0.0 (ελάχιστη αντίθεση) και 1.0 (μέγιστη αντίθεση). Η προεπιλεγμένη τιμή είναι 0.5. (κληρονομείται από [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [gray_scale](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/gray_scale/) | Η ιδιότητα υποδεικνύει εάν μια εικόνα θα εμφανιστεί σε κατάσταση γκρι κλίμακας. (κληρονομείται από [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |

### Παράδειγμα

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.spreadsheet as gwo_xls

load_options = gwo_xls.SpreadsheetLoadOptions()
with gw.Watermarker("spreadsheet.xlsx", load_options) as watermarker:
    with gww.ImageWatermark("logo.png") as watermark:
        effects = gwo_xls.SpreadsheetImageEffects()
        effects.brightness = 0.7
        effects.contrast = 0.6
        effects.chroma_key = gww.Color.red
        effects.border_line_format.enabled = True
        effects.border_line_format.weight = 1
        options = gwo_xls.SpreadsheetWatermarkShapeOptions()
        options.effects = effects
        watermarker.add(watermark, options)
    watermarker.save("output.xlsx")
```

### Δείτε επίσης
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
