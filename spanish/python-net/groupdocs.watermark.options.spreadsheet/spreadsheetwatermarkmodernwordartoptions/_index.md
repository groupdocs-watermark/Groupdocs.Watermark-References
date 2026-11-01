---
title: "Clase SpreadsheetWatermarkModernWordArtOptions"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa las opciones al agregar una marca de agua de arte de Word moderna a una hoja de cálculo Spreadsheet."
type: docs
url: /es/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/
is_root: false
weight: 110
---


## SpreadsheetWatermarkModernWordArtOptions class

Representa las opciones al agregar una marca de agua de arte de Word moderna a una hoja de cálculo Spreadsheet.

Aprende más:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents

El tipo SpreadsheetWatermarkModernWordArtOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/__init__/) | Inicializa una nueva instancia de la clase [`SpreadsheetWatermarkModernWordArtOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/). |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [worksheet_index](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/worksheet_index/) | El índice de la hoja de cálculo donde se añadirá la marca de agua. |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/alternative_text/) | El texto descriptivo (alternativo) que se asociará a una forma. (heredado de [`SpreadsheetWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/)) |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/is_locked/) | La propiedad indica si la edición de la forma en Excel está prohibida. (heredado de [`SpreadsheetWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/)) |
| [name](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/name/) | El nombre de la forma. (heredado de [`SpreadsheetWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/)) |

### Campos
| Campo | Descripción |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Obtiene el valor predeterminado para la clase. (heredado de [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions, SpreadsheetWatermarkModernWordArtOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

load_options = SpreadsheetLoadOptions()
with Watermarker("./spreadsheet.xlsx", load_options) as watermarker:
    watermark = TextWatermark("Test watermark", Font("Arial", 36.0))
    options = SpreadsheetWatermarkModernWordArtOptions()
    options.worksheet_index = 0
    options.is_locked = False
    watermarker.add(watermark, options)
    watermarker.save("./output.xlsx")
```

### Ver también
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
