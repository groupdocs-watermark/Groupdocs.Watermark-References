---
title: "Clase SpreadsheetWatermarkShapeOptions"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa las opciones al agregar una marca de agua de forma a una hoja de cálculo Spreadsheet."
type: docs
url: /es/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/
is_root: false
weight: 120
---


## SpreadsheetWatermarkShapeOptions class

Representa las opciones al agregar una marca de agua de forma a una hoja de cálculo Spreadsheet.

Aprende más:
- Add watermarks to spreadsheet documents (https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)

El tipo SpreadsheetWatermarkShapeOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/__init__/) | Inicializa una nueva instancia de la clase SpreadsheetWatermarkShapeOptions. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [effects](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/effects/) | Los efectos aplicados a la marca de agua, especificados como una instancia de [`SpreadsheetImageEffects`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetimageeffects/) o [`SpreadsheetTextEffects`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheettexteffects/). |
| [worksheet_index](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/worksheet_index/) | El índice de la hoja de cálculo a la que se añadirá la marca de agua. |
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
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment
from groupdocs.watermark.options.spreadsheet import (
    SpreadsheetLoadOptions, SpreadsheetWatermarkShapeOptions,
)

def add_watermark_to_worksheet():
    with Watermarker("./spreadsheet.xlsx", SpreadsheetLoadOptions()) as watermarker:
        watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 19.0))
        watermark.foreground_color = Color.red
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER

        options = SpreadsheetWatermarkShapeOptions()
        options.worksheet_index = 0
        watermarker.add(watermark, options)

        watermarker.save("./output.xlsx")
```

### Ver también
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
