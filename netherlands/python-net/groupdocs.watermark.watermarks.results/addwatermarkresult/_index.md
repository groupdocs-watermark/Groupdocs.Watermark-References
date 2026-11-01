---
title: "AddWatermarkResult klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Stelt het resultaat voor van het toevoegen van watermarks aan een document."
type: docs
url: /nl/python-net/groupdocs.watermark.watermarks.results/addwatermarkresult/
is_root: false
weight: 10
---


## AddWatermarkResult class

Stelt het resultaat voor van het toevoegen van watermarks aan een document.

Het AddWatermarkResult-type geeft de volgende leden weer:

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [number_applied_watermarks](/watermark/python-net/groupdocs.watermark.watermarks.results/addwatermarkresult/number_applied_watermarks/) | Het aantal toegepaste watermerken. |
| [succeeded](/watermark/python-net/groupdocs.watermark.watermarks.results/addwatermarkresult/succeeded/) | De lijst met nieuw aangemaakte watermerken. |

### Voorbeeld

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

### Zie ook
* module [`groupdocs.watermark.watermarks.results`](/watermark/python-net/groupdocs.watermark.watermarks.results/)
