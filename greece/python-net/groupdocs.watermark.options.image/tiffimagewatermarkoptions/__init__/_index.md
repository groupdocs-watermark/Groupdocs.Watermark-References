---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια νέα παρουσία της κλάσης TiffImageWatermarkOptions."
type: docs
url: /el/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/__init__/
is_root: false
weight: 10
---


## __init__

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [`TiffImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/).

```python
def __init__(self):
    ...
```

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment
from groupdocs.watermark.options.image import TiffImageLoadOptions, TiffImageWatermarkOptions

def add_watermark_to_image():
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

## __init__ {#frame_index}

Αρχικοποιεί ένα νέο στιγμιότυπο του [`TiffImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/) με έναν καθορισμένο δείκτη πλαισίου.

```python
def __init__(self, frame_index):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| frame_index | `int` | Ο δείκτης του frame για προσθήκη του υδατογραφήματος. |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment
from groupdocs.watermark.options.image import TiffImageLoadOptions, TiffImageWatermarkOptions

def add_watermark_to_image():
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
* class [`TiffImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/)
