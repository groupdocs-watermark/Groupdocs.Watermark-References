---
title: "Klassen TextWatermark"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Representerar en textvattenstämpel."
type: docs
url: /sv/python-net/groupdocs.watermark.watermarks/textwatermark/
is_root: false
weight: 110
---


## TextWatermark class

Representerar en textvattenstämpel.

Läs mer:
- Adding text watermarks: https://docs.groupdocs.com/display/watermarknet/Adding+text+watermarks

TextWatermark-typen visar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/__init__/#text-font) | Initierar en ny TextWatermark med den angivna texten och teckensnittet. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [background_color](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/background_color/) | Bakgrundsfärgen på texten. |
| [font](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/font/) | Typsnittet för texten. |
| [foreground_color](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/foreground_color/) | Förgrundsfärgen på texten. |
| [padding](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/padding/) | Padding‑inställningarna för denna TextWatermark, tillämpliga endast på bildfiler. |
| [text](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/text/) | Texten som ska användas som vattenstämpel. |
| [text_alignment](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/text_alignment/) | Justeringen av vattenstämpeltexten. |
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
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermark.opacity = 0.5
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### Guides
Uppgiftsguider som använder `TextWatermark`:

* [Hello, World!](/watermark/python-net/guides/hello-world/)
* [Add text watermarks](/watermark/python-net/guides/add-text/)
* [Customize watermarks](/watermark/python-net/guides/customize/)
* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### Se även
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
