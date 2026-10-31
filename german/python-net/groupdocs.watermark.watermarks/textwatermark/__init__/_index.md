---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Initialisiert ein neues TextWatermark mit dem angegebenen Text und der Schriftart."
type: docs
url: /de/python-net/groupdocs.watermark.watermarks/textwatermark/__init__/
is_root: false
weight: 10
---


## __init__ {#text-font}

Initialisiert ein neues TextWatermark mit dem angegebenen Text und der Schriftart.

```python
def __init__(self, text, font):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| text | `str` | Der Text, der als Wasserzeichen verwendet wird. |
| font | `Font` | Die Schriftart des Textes. |

### Beispiel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### Siehe auch
* class [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/)
