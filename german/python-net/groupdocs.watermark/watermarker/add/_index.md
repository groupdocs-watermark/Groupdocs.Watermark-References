---
title: "add Methode"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Fügt dem geladenen Dokument ein Wasserzeichen hinzu."
type: docs
url: /de/python-net/groupdocs.watermark/watermarker/add/
is_root: false
weight: 1010
---


## add {#watermark}

Fügt dem geladenen Dokument ein Wasserzeichen hinzu.

Erfahren Sie mehr über das Hinzufügen von Wasserzeichen in der GroupDocs-Dokumentation.

```python
def add(self, watermark):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| watermark | `Watermark` | Das Wasserzeichen, das dem Dokument hinzugefügt werden soll. |

### Beispiel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermark.opacity = 0.5
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

## add {#watermark-options}

Fügt dem geladenen Dokument ein Wasserzeichen mithilfe von Wasserzeichenoptionen hinzu.

Erfahren Sie mehr über das Hinzufügen von Wasserzeichen: https://docs.groupdocs.com/display/watermarknet/Adding+watermarks.

```python
def add(self, watermark, options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| watermark | `Watermark` | Das Wasserzeichen, das dem Dokument hinzugefügt werden soll. |
| options | `WatermarkOptions` | Zusätzliche Optionen, die beim Hinzufügen des Wasserzeichens verwendet werden können. |

**Returns:** None.

### Beispiel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermark.opacity = 0.5
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### Siehe auch
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
