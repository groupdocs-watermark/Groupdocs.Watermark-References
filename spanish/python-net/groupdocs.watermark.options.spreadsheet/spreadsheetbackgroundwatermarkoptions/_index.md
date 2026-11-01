---
title: "Clase SpreadsheetBackgroundWatermarkOptions"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa opciones al agregar la marca de agua como fondo a una hoja de cálculo Spreadsheet."
type: docs
url: /es/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/
is_root: false
weight: 20
---


## SpreadsheetBackgroundWatermarkOptions class

Representa opciones al agregar la marca de agua como fondo a una hoja de cálculo Spreadsheet.

Más información: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents

El tipo SpreadsheetBackgroundWatermarkOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/__init__/) | Inicializa una nueva instancia de la clase [`SpreadsheetBackgroundWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/). |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [background_height](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/background_height/) | La altura deseada de la imagen de fondo en píxeles. |
| [background_width](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/background_width/) | El ancho deseado de la imagen de fondo en píxeles. |
| [worksheet_index](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/worksheet_index/) | El índice de la hoja de cálculo a la que se añadirá la marca de agua. |

### Campos
| Campo | Descripción |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Obtiene el valor predeterminado para la clase. (heredado de [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions, SpreadsheetBackgroundWatermarkOptions
from groupdocs.watermark.watermarks import TextWatermark, Font

load_options = SpreadsheetLoadOptions()
with Watermarker(r"C:\Documents\test.xlsx", load_options) as watermarker:
    watermark = TextWatermark("Test watermark", Font("Arial", 36))

    options = SpreadsheetBackgroundWatermarkOptions()
    options.worksheet_index = -1  # default
    options.background_width = 800
    options.background_height = 600

    watermarker.add(watermark, options)
    watermarker.save()
```

### Ver también
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
