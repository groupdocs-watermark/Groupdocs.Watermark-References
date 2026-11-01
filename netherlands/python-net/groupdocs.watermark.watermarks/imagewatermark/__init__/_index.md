---
title: "__init__ constructor"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Initialiseert een nieuw ImageWatermark-exemplaar met een opgegeven bestandspad."
type: docs
url: /nl/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Initialiseert een nieuw ImageWatermark-exemplaar met een opgegeven bestandspad.

```python
def __init__(self, file_path):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | `str` | Het pad naar de afbeelding die als watermerk zal worden gebruikt. |

### Voorbeeld

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.watermarks import ImageWatermark

    with Watermarker("document.docx") as watermarker:
        watermark = ImageWatermark("logo.png")
        watermarker.add(watermark)
        watermarker.save("watermarked.docx")
    ```

## __init__ {#stream}

Initialiseert een nieuw ImageWatermark met de meegeleverde afbeeldingstroom.

```python
def __init__(self, stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | `io.RawIOBase` | De stream die de afbeelding bevat die als watermerk zal worden gebruikt. |

### Voorbeeld

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

### Zie ook
* class [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/)
