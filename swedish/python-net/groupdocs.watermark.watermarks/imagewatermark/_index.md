---
title: "ImageWatermark-klass"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Representerar en bildvattenstämpel."
type: docs
url: /sv/python-net/groupdocs.watermark.watermarks/imagewatermark/
is_root: false
weight: 40
---


## ImageWatermark class

Representerar en bildvattenstämpel.

Läs mer:
- Adding image watermarks: https://docs.groupdocs.com/display/watermarknet/Adding+image+watermarks

ImageWatermark-typen visar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/#file_path) | Initierar en ny ImageWatermark-instans med en angiven filsökväg. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/#stream) | Initierar en ny ImageWatermark med den tillhandahållna bildströmmen. |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [dispose](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/dispose/) | Avslutar den aktuella instansen. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [consider_parent_margins](/watermark/python-net/groupdocs.watermark/watermark/consider_parent_margins/) | Egenskapen som anger om vattenstämpelns storlek och koordinater beräknas med hänsyn till föräldramarginaler. Om den är satt till True beaktas föräldramarginaler i beräkningarna; som standard är värdet False och föräldramarginaler ignoreras. (ärvd från [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [height](/watermark/python-net/groupdocs.watermark/watermark/height/) | Den önskade höjden för denna [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (ärvd från [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [horizontal_alignment](/watermark/python-net/groupdocs.watermark/watermark/horizontal_alignment/) | Den horisontella justeringen för denna Watermark. (ärvd från [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [is_background](/watermark/python-net/groupdocs.watermark/watermark/is_background/) | Egenskapen som anger om vattenstämpeln ska placeras i bakgrunden. Om true placeras vattenstämpeln längst ner; annars placeras den högst upp (standard är False). (ärvd från [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [margins](/watermark/python-net/groupdocs.watermark/watermark/margins/) | Marginalinställningarna för denna Watermark. (ärvd från [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [opacity](/watermark/python-net/groupdocs.watermark/watermark/opacity/) | Opaciteten för denna [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (ärvd från [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [pages_setup](/watermark/python-net/groupdocs.watermark/watermark/pages_setup/) | Sidinställningarna för denna Watermark. (ärvd från [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [rotate_angle](/watermark/python-net/groupdocs.watermark/watermark/rotate_angle/) | Rotationsvinkeln för denna [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) i grader. (ärvd från [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [save_result_in_metadata](/watermark/python-net/groupdocs.watermark/watermark/save_result_in_metadata/) | Egenskapen indikerar om information om tillagda vattenstämplar ska sparas i dokumentets metadata. (ärvd från [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [scale_factor](/watermark/python-net/groupdocs.watermark/watermark/scale_factor/) | Skalfaktorn för denna [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/), som definierar hur vattenstämpelns storlek beror på förälderns storlek. (ärvd från [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [sizing_type](/watermark/python-net/groupdocs.watermark/watermark/sizing_type/) | Storlekstypen för vattenstämpeln. (ärvd från [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [tile_options](/watermark/python-net/groupdocs.watermark/watermark/tile_options/) | Alternativen för att definiera en upprepad vattenstämpel. (ärvd från [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [vertical_alignment](/watermark/python-net/groupdocs.watermark/watermark/vertical_alignment/) | Den vertikala justeringen av denna [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (ärvd från [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [width](/watermark/python-net/groupdocs.watermark/watermark/width/) | Den önskade bredden för denna [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (ärvd från [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [x](/watermark/python-net/groupdocs.watermark/watermark/x/) | X-koordinaten för denna [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (ärvd från [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [y](/watermark/python-net/groupdocs.watermark/watermark/y/) | Y-koordinaten för denna [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (ärvd från [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |

### Exempel

```python
import io
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark

def add_image_watermark_from_stream():
    # Läs in bilddata i en ström
    with open("./logo.png", "rb") as f:
        image_data = f.read()

    # Öppna dokumentet och lägg till bildvattenstämpeln
    with Watermarker("./sample.docx") as watermarker:
        with ImageWatermark(stream=io.BytesIO(image_data)) as watermark:
            watermarker.add(watermark)
        watermarker.save("./output.docx")
```

### Guides
Uppgiftsguider som använder `ImageWatermark`:

* [Add image watermarks](/watermark/python-net/guides/add-image/)
* [Customize watermarks](/watermark/python-net/guides/customize/)

### Se även
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
