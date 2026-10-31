---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يقوم بإنشاء نسخة جديدة من الفئة TiffImageWatermarkOptions."
type: docs
url: /ar/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/__init__/
is_root: false
weight: 10
---


## __init__

يُنشئ مثيلاً جديدًا للفئة [`TiffImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/).

```python
def __init__(self):
    ...
```

### مثال

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

يُنشئ مثيلاً جديدًا من [`TiffImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/) مع فهرس إطار محدد.

```python
def __init__(self, frame_index):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| frame_index | `int` | فهرس الإطار لإضافة العلامة المائية. |

### مثال

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

### انظر أيضًا
* class [`TiffImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/)
