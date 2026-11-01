---
title: "TiffImageLoadOptions klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Stelt afbeeldingslaadopties voor een TIFF-afbeelding voor."
type: docs
url: /nl/python-net/groupdocs.watermark.options.image/tiffimageloadoptions/
is_root: false
weight: 80
---


## TiffImageLoadOptions class

Stelt afbeeldingslaadopties voor een TIFF-afbeelding voor.

Het type TiffImageLoadOptions exposeert de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.image/tiffimageloadoptions/__init__/) | Initialiseert een nieuw exemplaar van de TiffImageLoadOptions klasse. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Het type van het bestand, dat het formaat aangeeft (bijv. docx, pdf, xlsx, enz.). (geërfd van [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | De formaatfamilie van het document, die het type aangeeft (bijv. Image, Pdf, Spreadsheet, enz.). (geërfd van [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | Het wachtwoord voor het openen van een versleuteld document. (geërfd van [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Velden
| Veld | Beschrijving |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.image/tiffimageloadoptions/default/) | Haalt de standaardwaarde op voor de klasse. |

### Voorbeeld

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment
from groupdocs.watermark.options.image import TiffImageLoadOptions, TiffImageWatermarkOptions

with Watermarker("./image.tiff", TiffImageLoadOptions()) as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 19.0))
    watermark.foreground_color = Color.red
    watermark.horizontal_alignment = HorizontalAlignment.CENTER
    watermark.vertical_alignment = VerticalAlignment.CENTER

    options = TiffImageWatermarkOptions()
    options.frame_index = 0
    watermarker.add(watermark, options)

    watermarker.save("./output.tiff")
```

### Zie ook
* module [`groupdocs.watermark.options.image`](/watermark/python-net/groupdocs.watermark.options.image/)
