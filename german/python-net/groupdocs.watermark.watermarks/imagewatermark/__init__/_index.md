---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Initialisiert eine neue ImageWatermark-Instanz mit einem angegebenen Dateipfad."
type: docs
url: /de/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Initialisiert eine neue ImageWatermark-Instanz mit einem angegebenen Dateipfad.

```python
def __init__(self, file_path):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | `str` | Der Pfad zum Bild, das als Wasserzeichen verwendet wird. |

### Beispiel

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.watermarks import ImageWatermark

    with Watermarker("document.docx") as watermarker:
        watermark = ImageWatermark("logo.png")
        watermarker.add(watermark)
        watermarker.save("watermarked.docx")
    ```

## __init__ {#stream}

Initialisiert ein neues ImageWatermark mit dem bereitgestellten Bildstrom.

```python
def __init__(self, stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | `io.RawIOBase` | Der Stream, der das Bild enthält, das als Wasserzeichen verwendet wird. |

### Beispiel

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

### Siehe auch
* class [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/)
