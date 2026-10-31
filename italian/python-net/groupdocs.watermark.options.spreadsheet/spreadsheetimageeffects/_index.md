---
title: "Classe SpreadsheetImageEffects"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Rappresenta gli effetti che possono essere applicati a un watermark immagine per un documento Excel."
type: docs
url: /it/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetimageeffects/
is_root: false
weight: 30
---


## SpreadsheetImageEffects class

Rappresenta gli effetti che possono essere applicati a un watermark immagine per un documento Excel.

Il tipo SpreadsheetImageEffects espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetimageeffects/__init__/) | Inizializza una nuova istanza della classe [`SpreadsheetImageEffects`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetimageeffects/). |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [border_line_format](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/border_line_format/) | Le impostazioni del formato della linea per il bordo dell'immagine. (eredita da [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [brightness](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/brightness/) | La luminosità dell'immagine. Deve essere un valore float compreso tra 0.0 (più scuro) e 1.0 (più luminoso). Il valore predefinito è 0.5. (eredita da [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [chroma_key](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/chroma_key/) | Il valore di colore dell'immagine che sarà trattato come trasparente. Il valore predefinito è un colore completamente trasparente. (eredita da [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [contrast](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/contrast/) | Il contrasto per l'immagine specificata. Deve essere un valore float compreso tra 0.0 (meno contrasto) e 1.0 (massimo contrasto). Il valore predefinito è 0.5. (eredita da [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [gray_scale](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/gray_scale/) | La proprietà indica se un'immagine verrà visualizzata in modalità scala di grigi. (eredita da [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |

### Esempio

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.spreadsheet as gwo_xls

load_options = gwo_xls.SpreadsheetLoadOptions()
with gw.Watermarker("spreadsheet.xlsx", load_options) as watermarker:
    with gww.ImageWatermark("logo.png") as watermark:
        effects = gwo_xls.SpreadsheetImageEffects()
        effects.brightness = 0.7
        effects.contrast = 0.6
        effects.chroma_key = gww.Color.red
        effects.border_line_format.enabled = True
        effects.border_line_format.weight = 1
        options = gwo_xls.SpreadsheetWatermarkShapeOptions()
        options.effects = effects
        watermarker.add(watermark, options)
    watermarker.save("output.xlsx")
```

### Vedi anche
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
