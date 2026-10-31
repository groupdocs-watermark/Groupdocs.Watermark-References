---
title: "ImageWatermark Klasse"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Stellt ein Bildwasserzeichen dar."
type: docs
url: /de/python-net/groupdocs.watermark.watermarks/imagewatermark/
is_root: false
weight: 40
---


## ImageWatermark class

Stellt ein Bildwasserzeichen dar.

Mehr erfahren:
- Adding image watermarks: https://docs.groupdocs.com/display/watermarknet/Adding+image+watermarks

Der Typ ImageWatermark stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/#file_path) | Initialisiert eine neue ImageWatermark-Instanz mit einem angegebenen Dateipfad. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/#stream) | Initialisiert ein neues ImageWatermark mit dem bereitgestellten Bildstrom. |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [dispose](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/dispose/) | Gibt die aktuelle Instanz frei. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [consider_parent_margins](/watermark/python-net/groupdocs.watermark/watermark/consider_parent_margins/) | Die Eigenschaft, die angibt, ob die Größe und Koordinaten des Wasserzeichens unter Berücksichtigung der übergeordneten Ränder berechnet werden. Wenn sie auf True gesetzt ist, berücksichtigen die Berechnungen die übergeordneten Ränder; standardmäßig ist der Wert False und die übergeordneten Ränder werden ignoriert. (geerbt von [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [height](/watermark/python-net/groupdocs.watermark/watermark/height/) | Die gewünschte Höhe dieses [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (geerbt von [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [horizontal_alignment](/watermark/python-net/groupdocs.watermark/watermark/horizontal_alignment/) | Die horizontale Ausrichtung dieses Wasserzeichens. (geerbt von [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [is_background](/watermark/python-net/groupdocs.watermark/watermark/is_background/) | Die Eigenschaft, die angibt, ob das Wasserzeichen im Hintergrund platziert werden soll. Wenn true, wird das Wasserzeichen unten platziert; andernfalls wird es oben platziert (Standard ist False). (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [margins](/watermark/python-net/groupdocs.watermark/watermark/margins/) | Die Rand-Einstellungen dieses Wasserzeichens. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [opacity](/watermark/python-net/groupdocs.watermark/watermark/opacity/) | Die Deckkraft dieses [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [pages_setup](/watermark/python-net/groupdocs.watermark/watermark/pages_setup/) | Die Seiten-Einrichtungs-Einstellungen dieses Wasserzeichens. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [rotate_angle](/watermark/python-net/groupdocs.watermark/watermark/rotate_angle/) | Der Rotationswinkel dieses [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) in Grad. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [save_result_in_metadata](/watermark/python-net/groupdocs.watermark/watermark/save_result_in_metadata/) | Die Eigenschaft gibt an, ob Informationen über hinzugefügte Wasserzeichen in den Dokumentmetadaten gespeichert werden sollen. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [scale_factor](/watermark/python-net/groupdocs.watermark/watermark/scale_factor/) | Der Skalierungsfaktor dieses [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/), der definiert, wie die Größe des Wasserzeichens von der übergeordneten Größe abhängt. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [sizing_type](/watermark/python-net/groupdocs.watermark/watermark/sizing_type/) | Der Größen-Typ des Wasserzeichens. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [tile_options](/watermark/python-net/groupdocs.watermark/watermark/tile_options/) | Die Optionen, um ein wiederholtes Wasserzeichen zu definieren. (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [vertical_alignment](/watermark/python-net/groupdocs.watermark/watermark/vertical_alignment/) | Die vertikale Ausrichtung dieses [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [width](/watermark/python-net/groupdocs.watermark/watermark/width/) | Die gewünschte Breite dieses [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [x](/watermark/python-net/groupdocs.watermark/watermark/x/) | Die x‑Koordinate dieses [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [y](/watermark/python-net/groupdocs.watermark/watermark/y/) | Die y‑Koordinate dieses [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (inherited from [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |

### Beispiel

```python
import io
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark

def add_image_watermark_from_stream():
    # Bilddaten in einen Stream laden
    with open("./logo.png", "rb") as f:
        image_data = f.read()

    # Öffne das Dokument und füge das Bildwasserzeichen hinzu
    with Watermarker("./sample.docx") as watermarker:
        with ImageWatermark(stream=io.BytesIO(image_data)) as watermark:
            watermarker.add(watermark)
        watermarker.save("./output.docx")
```

### Guides
Aufgabenleitfäden, die `ImageWatermark` verwenden:

* [Add image watermarks](/watermark/python-net/guides/add-image/)
* [Customize watermarks](/watermark/python-net/guides/customize/)

### Siehe auch
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
