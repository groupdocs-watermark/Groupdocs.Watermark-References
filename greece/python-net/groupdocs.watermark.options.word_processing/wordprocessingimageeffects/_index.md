---
title: "WordProcessingImageEffects κλάση"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά τα εφέ που μπορούν να εφαρμοστούν σε μια εικόνα υδατογράφημα για ένα έγγραφο Word."
type: docs
url: /el/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/
is_root: false
weight: 30
---


## WordProcessingImageEffects class

Αναπαριστά τα εφέ που μπορούν να εφαρμοστούν σε μια εικόνα υδατογράφημα για ένα έγγραφο Word.

Ο τύπος WordProcessingImageEffects εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/__init__/) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`WordProcessingImageEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/). |

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
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark, Color
from groupdocs.watermark.options.word_processing import (
    WordProcessingLoadOptions, WordProcessingWatermarkSectionOptions, WordProcessingImageEffects,
)

def add_watermark_with_effects():
    with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
        with ImageWatermark("./logo.png") as watermark:
            effects = WordProcessingImageEffects()
            effects.brightness = 0.7
            effects.contrast = 0.6
            effects.chroma_key = Color.red

            options = WordProcessingWatermarkSectionOptions()
            options.name = "Shape 1"
            options.alternative_text = "Company logo watermark"
            options.effects = effects
            watermarker.add(watermark, options)

        watermarker.save("./output.docx")

if __name__ == "__main__":
    add_watermark_with_effects()
```

### Δείτε επίσης
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
