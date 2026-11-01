---
title: "TextWatermark klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Stelt een tekstwatermerk voor."
type: docs
url: /nl/python-net/groupdocs.watermark.watermarks/textwatermark/
is_root: false
weight: 110
---


## TextWatermark class

Stelt een tekstwatermerk voor.

Meer informatie:
- Adding text watermarks: https://docs.groupdocs.com/display/watermarknet/Adding+text+watermarks

Het TextWatermark‑type biedt de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/__init__/#text-font) | Initialiseert een nieuwe TextWatermark met de opgegeven tekst en lettertype. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [background_color](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/background_color/) | De achtergrondkleur van de tekst. |
| [font](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/font/) | Het lettertype van de tekst. |
| [foreground_color](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/foreground_color/) | De voorgrondkleur van de tekst. |
| [padding](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/padding/) | De opvulinstellingen van deze TextWatermark, alleen van toepassing op afbeeldingsbestanden. |
| [text](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/text/) | De tekst die als watermerk wordt gebruikt. |
| [text_alignment](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/text_alignment/) | De uitlijning van de watermerktekst. |
| [consider_parent_margins](/watermark/python-net/groupdocs.watermark/watermark/consider_parent_margins/) | De eigenschap die aangeeft of de grootte en coördinaten van het watermerk worden berekend met inachtneming van de marges van de bovenliggende container. Indien ingesteld op True, worden de berekeningen uitgevoerd met de bovenliggende marges; standaard is de waarde False en worden de bovenliggende marges genegeerd. (geërfd van [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [height](/watermark/python-net/groupdocs.watermark/watermark/height/) | De gewenste hoogte van deze [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (geërfd van [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [horizontal_alignment](/watermark/python-net/groupdocs.watermark/watermark/horizontal_alignment/) | De horizontale uitlijning van dit watermerk. (geërfd van [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [is_background](/watermark/python-net/groupdocs.watermark/watermark/is_background/) | De eigenschap die aangeeft of het watermerk op de achtergrond moet worden geplaatst. Indien true, wordt het watermerk onderaan geplaatst; anders wordt het bovenaan geplaatst (standaard is False). (geërfd van [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [margins](/watermark/python-net/groupdocs.watermark/watermark/margins/) | De marge‑instellingen van dit watermerk. (geërfd van [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [opacity](/watermark/python-net/groupdocs.watermark/watermark/opacity/) | De opaciteit van deze [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (geërfd van [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [pages_setup](/watermark/python-net/groupdocs.watermark/watermark/pages_setup/) | De pagina-instellingsinstellingen van deze Watermark. (geërfd van [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [rotate_angle](/watermark/python-net/groupdocs.watermark/watermark/rotate_angle/) | De rotatiehoek van deze [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) in graden. (geërfd van [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [save_result_in_metadata](/watermark/python-net/groupdocs.watermark/watermark/save_result_in_metadata/) | De eigenschap geeft aan of informatie over toegevoegde watermerken moet worden opgeslagen in de documentmetadata. (geërfd van [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [scale_factor](/watermark/python-net/groupdocs.watermark/watermark/scale_factor/) | De schaalfactor van deze [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/), die bepaalt hoe de watermerkgrootte afhangt van de grootte van het bovenliggende element. (geërfd van [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [sizing_type](/watermark/python-net/groupdocs.watermark/watermark/sizing_type/) | Het formaattype van het watermerk. (geërfd van [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [tile_options](/watermark/python-net/groupdocs.watermark/watermark/tile_options/) | De opties om een herhaald watermerk te definiëren. (geërfd van [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [vertical_alignment](/watermark/python-net/groupdocs.watermark/watermark/vertical_alignment/) | De verticale uitlijning van deze [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (geërfd van [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [width](/watermark/python-net/groupdocs.watermark/watermark/width/) | De gewenste breedte van deze [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (geërfd van [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [x](/watermark/python-net/groupdocs.watermark/watermark/x/) | De x-coördinaat van deze [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (geërfd van [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [y](/watermark/python-net/groupdocs.watermark/watermark/y/) | De y-coördinaat van deze [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (geërfd van [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |

### Voorbeeld

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
Taakgidsen die `TextWatermark` gebruiken:

* [Hello, World!](/watermark/python-net/guides/hello-world/)
* [Add text watermarks](/watermark/python-net/guides/add-text/)
* [Customize watermarks](/watermark/python-net/guides/customize/)
* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### Zie ook
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
