---
title: "__init__ constructor"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Inicializa una nueva instancia de la clase PresentationWatermarkSlideOptions."
type: docs
url: /es/python-net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una nueva instancia de la clase [`PresentationWatermarkSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/).

```python
def __init__(self):
    ...
```

### Ejemplo

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

### Ver también
* class [`PresentationWatermarkSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/)
