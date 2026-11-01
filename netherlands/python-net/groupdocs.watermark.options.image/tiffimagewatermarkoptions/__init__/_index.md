---
title: "__init__ constructor"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Initialiseert een nieuw exemplaar van de TiffImageWatermarkOptions-klasse."
type: docs
url: /nl/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een nieuw exemplaar van de [`TiffImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/) klasse.

```python
def __init__(self):
    ...
```

### Voorbeeld

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

Initialiseert een nieuw [`TiffImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/) exemplaar met een opgegeven frame‑index.

```python
def __init__(self, frame_index):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| frame_index | `int` | De index van het frame om het watermerk toe te voegen. |

### Voorbeeld

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

### Zie ook
* class [`TiffImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/)
