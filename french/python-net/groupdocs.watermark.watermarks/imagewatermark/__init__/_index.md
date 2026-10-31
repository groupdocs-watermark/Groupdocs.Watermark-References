---
title: "__init__ constructeur"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Initialise une nouvelle instance d'ImageWatermark avec un chemin de fichier spécifié."
type: docs
url: /fr/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Initialise une nouvelle instance d'ImageWatermark avec un chemin de fichier spécifié.

```python
def __init__(self, file_path):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | `str` | Le chemin vers l'image qui sera utilisée comme filigrane. |

### Exemple

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.watermarks import ImageWatermark

    with Watermarker("document.docx") as watermarker:
        watermark = ImageWatermark("logo.png")
        watermarker.add(watermark)
        watermarker.save("watermarked.docx")
    ```

## __init__ {#stream}

Initialise un nouvel ImageWatermark avec le flux d'image fourni.

```python
def __init__(self, stream):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| stream | `io.RawIOBase` | Le flux contenant l'image qui sera utilisée comme filigrane. |

### Exemple

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

### Voir aussi
* class [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/)
