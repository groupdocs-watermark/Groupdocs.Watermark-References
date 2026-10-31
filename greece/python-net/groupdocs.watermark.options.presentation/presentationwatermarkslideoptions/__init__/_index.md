---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PresentationWatermarkSlideOptions."
type: docs
url: /el/python-net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/__init__/
is_root: false
weight: 10
---


## __init__

Δημιουργεί ένα νέο αντικείμενο της κλάσης [`PresentationWatermarkSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/) class.

```python
def __init__(self):
    ...
```

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment
from groupdocs.watermark.options.presentation import (
    PresentationLoadOptions,
    PresentationWatermarkSlideOptions,
)

with Watermarker("./presentation.pptx", PresentationLoadOptions()) as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 19.0))
    watermark.foreground_color = Color.red
    watermark.horizontal_alignment = HorizontalAlignment.CENTER
    watermark.vertical_alignment = VerticalAlignment.CENTER

    options = PresentationWatermarkSlideOptions()
    options.slide_index = 0
    watermarker.add(watermark, options)
    watermarker.save("./output.pptx")
```

### Δείτε επίσης
* class [`PresentationWatermarkSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/)
