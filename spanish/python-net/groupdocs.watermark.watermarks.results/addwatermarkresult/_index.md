---
title: "Clase AddWatermarkResult"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa el resultado de agregar marcas de agua a un documento."
type: docs
url: /es/python-net/groupdocs.watermark.watermarks.results/addwatermarkresult/
is_root: false
weight: 10
---


## AddWatermarkResult class

Representa el resultado de agregar marcas de agua a un documento.

El tipo AddWatermarkResult expone los siguientes miembros:

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [number_applied_watermarks](/watermark/python-net/groupdocs.watermark.watermarks.results/addwatermarkresult/number_applied_watermarks/) | El número de marcas de agua aplicadas. |
| [succeeded](/watermark/python-net/groupdocs.watermark.watermarks.results/addwatermarkresult/succeeded/) | La lista de marcas de agua recién creadas. |

### Ejemplo

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww

with gw.Watermarker("sample_2_pages.pdf") as watermarker:
    font = gww.Font("Arial", 19.0, gww.FontStyle.BOLD | gww.FontStyle.ITALIC)
    watermark = gww.TextWatermark("Test watermark", font)

    watermark.foreground_color = gww.Color.red
    watermark.background_color = gww.Color.blue
    watermark.text_alignment = gww.TextAlignment.RIGHT
    watermark.opacity = 0.5

    result = watermarker.add(watermark)

    for item in result.succeeded:
        print("WatermarkId:", item.watermark_id)
        print("WatermarkType:", item.watermark_type)
        print("PageNumber:", item.page_number)
        print("WatermarkPosition:", item.watermark_position)

    watermarker.save("output.pdf")
```

### Ver también
* module [`groupdocs.watermark.watermarks.results`](/watermark/python-net/groupdocs.watermark.watermarks.results/)
