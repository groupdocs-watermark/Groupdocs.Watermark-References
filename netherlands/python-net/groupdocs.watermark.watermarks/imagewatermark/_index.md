---
title: "ImageWatermark-klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Stelt een afbeeldingwatermerk voor."
type: docs
url: /nl/python-net/groupdocs.watermark.watermarks/imagewatermark/
is_root: false
weight: 40
---


## ImageWatermark class

Stelt een afbeeldingwatermerk voor.

Meer informatie:
- Adding image watermarks: https://docs.groupdocs.com/display/watermarknet/Adding+image+watermarks

Het type ImageWatermark bevat de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/#file_path) | Initialiseert een nieuw ImageWatermark-exemplaar met een opgegeven bestandspad. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/#stream) | Initialiseert een nieuw ImageWatermark met de meegeleverde afbeeldingstroom. |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [dispose](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/dispose/) | Verwijdert de huidige instantie. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
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
import io
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark

def add_image_watermark_from_stream():
    # Laad afbeeldingsgegevens in een stroom
    with open("./logo.png", "rb") as f:
        image_data = f.read()

    # Open het document en voeg de afbeeldingwatermark toe
    with Watermarker("./sample.docx") as watermarker:
        with ImageWatermark(stream=io.BytesIO(image_data)) as watermark:
            watermarker.add(watermark)
        watermarker.save("./output.docx")
```

### Guides
Taakgidsen die `ImageWatermark` gebruiken:

* [Add image watermarks](/watermark/python-net/guides/add-image/)
* [Customize watermarks](/watermark/python-net/guides/customize/)

### Zie ook
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
