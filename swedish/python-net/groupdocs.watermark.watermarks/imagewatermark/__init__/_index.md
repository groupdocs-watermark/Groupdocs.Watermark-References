---
title: "__init__ konstruktor"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Initierar en ny ImageWatermark-instans med en angiven filsökväg."
type: docs
url: /sv/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Initierar en ny ImageWatermark-instans med en angiven filsökväg.

```python
def __init__(self, file_path):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | `str` | Sökvägen till bilden som ska användas som vattenmärke. |

### Exempel

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.watermarks import ImageWatermark

    with Watermarker("document.docx") as watermarker:
        watermark = ImageWatermark("logo.png")
        watermarker.add(watermark)
        watermarker.save("watermarked.docx")
    ```

## __init__ {#stream}

Initierar en ny ImageWatermark med den tillhandahållna bildströmmen.

```python
def __init__(self, stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | `io.RawIOBase` | Strömmen som innehåller bilden som ska användas som vattenmärke. |

### Exempel

```python
import io
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark

with open("logo.png", "rb") as f:
    image_data = f.read()

with Watermarker("sample.docx") as watermarker:
    with ImageWatermark(stream=io.BytesIO(image_data)) as watermark:
        watermarker.add(watermark)
    watermarker.save("watermarked.docx")
```

### Se även
* class [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/)
