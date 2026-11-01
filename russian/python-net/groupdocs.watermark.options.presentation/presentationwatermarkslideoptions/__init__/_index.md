---
title: "__init__ конструктор"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Инициализирует новый экземпляр класса PresentationWatermarkSlideOptions."
type: docs
url: /ru/python-net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует новый экземпляр класса [`PresentationWatermarkSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/).

```python
def __init__(self):
    ...
```

### Пример

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

### См. также
* class [`PresentationWatermarkSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/)
