---
title: "__init__ costruttore"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Inizializza una nuova istanza della classe PresentationWatermarkSlideOptions."
type: docs
url: /it/python-net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una nuova istanza della classe [`PresentationWatermarkSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/).

```python
def __init__(self):
    ...
```

### Esempio

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

### Vedi anche
* class [`PresentationWatermarkSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/)
