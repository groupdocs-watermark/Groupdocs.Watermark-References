---
title: "SpreadsheetTextEffects वर्ग"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "Excel दस्तावेज़ के लिए टेक्स्ट वॉटरमार्क पर लागू किए जा सकने वाले प्रभावों का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.options.spreadsheet/spreadsheettexteffects/
is_root: false
weight: 80
---


## SpreadsheetTextEffects class

Excel दस्तावेज़ के लिए टेक्स्ट वॉटरमार्क पर लागू किए जा सकने वाले प्रभावों का प्रतिनिधित्व करता है।

यह SpreadsheetTextEffects प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### निर्माता
| निर्माता | विवरण |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheettexteffects/__init__/) | [`SpreadsheetTextEffects`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheettexteffects/) वर्ग का एक नया उदाहरण प्रारंभ करता है। |

### गुणधर्म
| गुणधर्म | विवरण |
| :- | :- |
| [line_format](/watermark/python-net/groupdocs.watermark.contents/officetexteffects/line_format/) | लाइन फ़ॉर्मेट सेटिंग्स, एक [`OfficeLineFormat`](/watermark/python-net/groupdocs.watermark.contents/officelineformat/) उदाहरण द्वारा प्रतिनिधित्वित। ([`OfficeTextEffects`](/watermark/python-net/groupdocs.watermark.contents/officetexteffects/) से विरासत में मिली)। |

### उदाहरण

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

### संबंधित देखें
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
