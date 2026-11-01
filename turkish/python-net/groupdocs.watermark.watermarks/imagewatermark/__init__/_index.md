---
title: "__init__ yapıcı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Belirtilen dosya yolu ile yeni bir ImageWatermark örneği başlatır."
type: docs
url: /tr/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Belirtilen dosya yolu ile yeni bir ImageWatermark örneği başlatır.

```python
def __init__(self, file_path):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | `str` | Filigran olarak kullanılacak görüntünün yolu. |

### Örnek

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.watermarks import ImageWatermark

    with Watermarker("document.docx") as watermarker:
        watermark = ImageWatermark("logo.png")
        watermarker.add(watermark)
        watermarker.save("watermarked.docx")
    ```

## __init__ {#stream}

Sağlanan görüntü akışıyla yeni bir ImageWatermark başlatır.

```python
def __init__(self, stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | `io.RawIOBase` | Filigran olarak kullanılacak görüntüyü içeren akış. |

### Örnek

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

### Ayrıca Bakınız
* class [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/)
