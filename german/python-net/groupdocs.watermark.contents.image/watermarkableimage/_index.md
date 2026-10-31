---
title: "Klasse WatermarkableImage"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Stellt ein Bild innerhalb eines Dokuments dar."
type: docs
url: /de/python-net/groupdocs.watermark.contents.image/watermarkableimage/
is_root: false
weight: 90
---


## WatermarkableImage class

Stellt ein Bild innerhalb eines Dokuments dar.

Mehr erfahren:
- https://docs.groupdocs.com/display/watermarknet/Adding+watermark+to+images+inside+a+document

Der Typ WatermarkableImage stellt die folgenden Mitglieder bereit:

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [add](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add/#watermark) | Fügt diesem [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) ein Wasserzeichen hinzu. Diese Methode geht davon aus, dass Wasserzeichenversatz und -größe in Pixeln gemessen werden (falls sie zugewiesen wurden). |
| [add_watermark](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add_watermark/) |  |
| [get_bytes](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/get_bytes/) | Gibt das Bild als Byte-Array zurück. |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Findet Bilder gemäß den angegebenen Suchkriterien. Die Suche wird in den in [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) angegebenen Objekten durchgeführt. (geerbt von [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (geerbt von [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Findet mögliche Wasserzeichen gemäß den angegebenen Suchkriterien. Die Suche wird an den in [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) aufgeführten Objekten durchgeführt. (geerbt von [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (geerbt von [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/height/) | Die Höhe dieses [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) in Pixeln. |
| [width](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/width/) | Die Breite dieses WatermarkableImage in Pixeln. |

### Beispiel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font

with Watermarker(r"D:\input.doc") as watermarker:
    # Textwasserzeichen initialisieren.
    watermark = TextWatermark("DRAFT", Font("Arial", 19))

    # Alle Bilder im Dokument finden.
    images = watermarker.get_images()

    # Wasserzeichen zu jedem Bild hinzufügen.
    for img in images:
        img.add(watermark)

    # Änderungen speichern.
    watermarker.save(r"D:\output.doc")
```

### Siehe auch
* module [`groupdocs.watermark.contents.image`](/watermark/python-net/groupdocs.watermark.contents.image/)
