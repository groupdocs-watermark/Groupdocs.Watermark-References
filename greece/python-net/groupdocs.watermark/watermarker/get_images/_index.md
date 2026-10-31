---
title: "get_images μέθοδος"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Βρίσκει εικόνες σύμφωνα με τα καθορισμένα κριτήρια αναζήτησης."
type: docs
url: /el/python-net/groupdocs.watermark/watermarker/get_images/
is_root: false
weight: 1080
---


## get_images {#search_criteria}

Βρίσκει εικόνες σύμφωνα με τα καθορισμένα κριτήρια αναζήτησης.

Η αναζήτηση πραγματοποιείται σε αντικείμενα που καθορίζονται στο [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

Μάθετε περισσότερα για την αναζήτηση υδατοσημάτων https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def get_images(self, search_criteria):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| search_criteria | `ImageSearchCriteria` | Τα κριτήρια αναζήτησης προς χρήση. |

**Returns:** WatermarkableImageCollection: The collection of found images.

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color, SizingType

with Watermarker("./document.pdf") as watermarker:
    watermark = TextWatermark("PROTECTED", Font("Arial", 8.0))
    watermark.foreground_color = Color.red
    watermark.sizing_type = SizingType.SCALE_TO_PARENT_DIMENSIONS

    for image in watermarker.get_images():
        if image.width > 100 and image.height > 100:
            image.add(watermark)

    watermarker.save("./output.pdf")
```

## get_images

Βρίσκει όλες τις εικόνες στο έγγραφο.

Η αναζήτηση πραγματοποιείται σε αντικείμενα που καθορίζονται στο [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

Μάθετε περισσότερα για την αναζήτηση υδατοσημάτων στο https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def get_images(self):
    ...
```

**Returns:** The collection of found images.

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color, SizingType
from groupdocs.watermark.options.pdf import PdfLoadOptions

def watermark_images_inside():
    with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
        watermark = TextWatermark("PROTECTED", Font("Arial", 8.0))
        watermark.foreground_color = Color.red
        watermark.sizing_type = SizingType.SCALE_TO_PARENT_DIMENSIONS
        watermark.scale_factor = 1.0

        # Κάθε ραστερική εικόνα ενσωματωμένη στο έγγραφο
        for image in watermarker.get_images():
            # Παραλείψτε μικρές εικόνες όπως εικονίδια ή κουκίδες
            if image.width > 100 and image.height > 100:
                image.add(watermark)

        watermarker.save("./output.pdf")
```

### Δείτε επίσης
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
