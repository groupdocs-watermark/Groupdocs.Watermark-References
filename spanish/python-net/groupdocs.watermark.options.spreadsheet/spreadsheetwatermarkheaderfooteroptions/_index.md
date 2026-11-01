---
title: "Clase SpreadsheetWatermarkHeaderFooterOptions"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa las opciones al agregar la marca de agua al encabezado/pie de página de un Spreadsheet."
type: docs
url: /es/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/
is_root: false
weight: 100
---


## SpreadsheetWatermarkHeaderFooterOptions class

Representa las opciones al agregar la marca de agua al encabezado/pie de página de un Spreadsheet.

Aprende más:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents

El tipo SpreadsheetWatermarkHeaderFooterOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/__init__/) | Inicializa una nueva instancia de la clase [`SpreadsheetWatermarkHeaderFooterOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/). |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [worksheet_index](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/worksheet_index/) | El índice de la hoja de cálculo donde se añadirá la marca de agua. |

### Campos
| Campo | Descripción |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Obtiene el valor predeterminado para la clase. (heredado de [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions, SpreadsheetWatermarkHeaderFooterOptions
from groupdocs.watermark.watermarks import Font, TextWatermark
load_options = SpreadsheetLoadOptions()
with Watermarker("./test.xlsx", load_options) as watermarker:
    watermark = TextWatermark("Test", Font("Arial", 14))
    options = SpreadsheetWatermarkHeaderFooterOptions()
    options.worksheet_index = 0
    watermarker.add(watermark, options)
    watermarker.save()
```

### Ver también
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
