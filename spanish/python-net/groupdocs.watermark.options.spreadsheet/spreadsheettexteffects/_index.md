---
title: "Clase SpreadsheetTextEffects"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa efectos que pueden aplicarse a una marca de agua de texto para un documento Excel."
type: docs
url: /es/python-net/groupdocs.watermark.options.spreadsheet/spreadsheettexteffects/
is_root: false
weight: 80
---


## SpreadsheetTextEffects class

Representa efectos que pueden aplicarse a una marca de agua de texto para un documento Excel.

El tipo SpreadsheetTextEffects expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheettexteffects/__init__/) | Inicializa una nueva instancia de la clase [`SpreadsheetTextEffects`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheettexteffects/). |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [line_format](/watermark/python-net/groupdocs.watermark.contents/officetexteffects/line_format/) | La configuración del formato de línea, representada por una instancia de [`OfficeLineFormat`](/watermark/python-net/groupdocs.watermark.contents/officelineformat/). (heredada de [`OfficeTextEffects`](/watermark/python-net/groupdocs.watermark.contents/officetexteffects/)) |

### Ejemplo

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.spreadsheet as gwo_xls
import groupdocs.watermark.common as gwc
from groupdocs.watermark.contents import OfficeDashStyle, OfficeLineStyle

load_options = gwo_xls.SpreadsheetLoadOptions()
with gw.Watermarker("spreadsheet.xlsx", load_options) as watermarker:
    watermark = gww.TextWatermark("Test watermark", gww.Font("Segoe UI", 19.0))
    effects = gwo_xls.SpreadsheetTextEffects()
    effects.line_format.enabled = True
    effects.line_format.color = gww.Color.red
    effects.line_format.dash_style = OfficeDashStyle.DASH_DOT_DOT
    effects.line_format.line_style = OfficeLineStyle.TRIPLE
    effects.line_format.weight = 1
    options = gwo_xls.SpreadsheetWatermarkShapeOptions()
    options.effects = effects
    watermarker.add(watermark, options)
    watermarker.save("output.xlsx")
```

### Ver también
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
