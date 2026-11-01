---
title: "Clase HyperlinkPossibleWatermark"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa una posible marca de agua de hipervínculo en un contenido de PowerPoint."
type: docs
url: /es/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/
is_root: false
weight: 60
---


## HyperlinkPossibleWatermark class

Representa una posible marca de agua de hipervínculo en un contenido de PowerPoint.

El tipo HyperlinkPossibleWatermark expone los siguientes miembros:

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/height/) | La altura de este HyperlinkPossibleWatermark. |
| [parent](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/parent/) | El padre de este HyperlinkPossibleWatermark. |
| [rotate_angle](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/rotate_angle/) | El ángulo de rotación de este HyperlinkPossibleWatermark en grados. |
| [text](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/text/) | La URL de este HyperlinkPossibleWatermark. |
| [unit_of_measurement](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/unit_of_measurement/) | La unidad de medida de este [`HyperlinkPossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/). |
| [width](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/width/) | El ancho de este HyperlinkPossibleWatermark. |
| [x](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/x/) | La coordenada x de este HyperlinkPossibleWatermark. |
| [y](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/y/) | La coordenada y de este [`HyperlinkPossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/). |
| [formatted_text_fragments](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/formatted_text_fragments/) | La colección de fragmentos de texto formateado de este [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/). (heredado de [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [image_data](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/image_data/) | La imagen de este [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) o None si la marca de agua no tiene imagen. (heredado de [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [page_number](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/page_number/) | El número de página donde se coloca la marca de agua. (heredado de [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |

### Ejemplo

```python
import re
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search import HyperlinkPossibleWatermark
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    possible = watermarker.search(TextSearchCriteria(re.compile(r"someurl\.com")))
    for i in range(len(possible) - 1, -1, -1):
        if isinstance(possible[i], HyperlinkPossibleWatermark):
            print(possible[i].text)
            watermarker.remove(possible[i])
    watermarker.save("./output.pdf")
```

### Ver también
* module [`groupdocs.watermark.search`](/watermark/python-net/groupdocs.watermark.search/)
