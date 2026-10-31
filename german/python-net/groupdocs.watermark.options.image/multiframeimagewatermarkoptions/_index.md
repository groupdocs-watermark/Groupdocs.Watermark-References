---
title: "Klasse MultiframeImageWatermarkOptions"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Stellt Optionen zum Hinzufügen eines Wasserzeichens zu einem mehrrahmigen Bild dar."
type: docs
url: /de/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/
is_root: false
weight: 70
---


## MultiframeImageWatermarkOptions class

Stellt Optionen zum Hinzufügen eines Wasserzeichens zu einem mehrrahmigen Bild dar.

Mehr erfahren: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images

Der Typ MultiframeImageWatermarkOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/__init__/) | Initialisiert eine neue Instanz der Klasse [`MultiframeImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/). |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/__init__/#frame_index) | Initialisiert eine neue Instanz der Klasse [`MultiframeImageWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/) mit einem angegebenen Index des Frames. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [frame_index](/watermark/python-net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frame_index/) | Der Index des Frames, dem ein Wasserzeichen hinzugefügt werden soll. |

### Felder
| Feld | Beschreibung |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Ermittelt den Standardwert für die Klasse. (geerbt von [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Beispiel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.image import ImageLoadOptions, MultiframeImageWatermarkOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

load_options = ImageLoadOptions()
with Watermarker(r"C:\test.gif", load_options) as watermarker:
    watermark = TextWatermark("Test", Font("Arial", 12))
    options = MultiframeImageWatermarkOptions()
    options.frame_index = 0
    watermarker.add(watermark, options)
    watermarker.save()
```

### Siehe auch
* module [`groupdocs.watermark.options.image`](/watermark/python-net/groupdocs.watermark.options.image/)
