---
title: "SpreadsheetImageEffects वर्ग"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "Excel दस्तावेज़ के लिए छवि वॉटरमार्क पर लागू किए जा सकने वाले प्रभावों का प्रतिनिधित्व करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetimageeffects/
is_root: false
weight: 30
---


## SpreadsheetImageEffects class

Excel दस्तावेज़ के लिए छवि वॉटरमार्क पर लागू किए जा सकने वाले प्रभावों का प्रतिनिधित्व करता है।

यह SpreadsheetImageEffects प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### निर्माता
| निर्माता | विवरण |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetimageeffects/__init__/) | [`SpreadsheetImageEffects`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetimageeffects/) वर्ग का एक नया उदाहरण प्रारंभ करता है। |

### गुणधर्म
| गुणधर्म | विवरण |
| :- | :- |
| [border_line_format](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/border_line_format/) | छवि सीमा के लिए लाइन फ़ॉर्मेट सेटिंग्स। ([`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/) से विरासत में मिला है) |
| [brightness](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/brightness/) | चित्र की चमक। यह 0.0 (सबसे धुंधला) और 1.0 (सबसे उज्ज्वल) के बीच एक फ्लोट होना चाहिए। डिफ़ॉल्ट मान 0.5 है। ([`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/) से विरासत में मिला है) |
| [chroma_key](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/chroma_key/) | छवि का वह रंग मान जो पारदर्शी माना जाएगा। डिफ़ॉल्ट मान पूरी तरह पारदर्शी रंग है। ([`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/) से विरासत में मिला है) |
| [contrast](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/contrast/) | निर्दिष्ट चित्र के लिए कंट्रास्ट। यह 0.0 (सबसे कम कंट्रास्ट) और 1.0 (सबसे अधिक कंट्रास्ट) के बीच एक फ्लोट होना चाहिए। डिफ़ॉल्ट मान 0.5 है। ([`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/) से विरासत में मिला है) |
| [gray_scale](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/gray_scale/) | यह गुण दर्शाता है कि चित्र ग्रेस्केल मोड में प्रदर्शित होगा या नहीं। ([`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/) से विरासत में मिला है) |

### उदाहरण

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

### संबंधित देखें
* module [`groupdocs.watermark.options.spreadsheet`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/)
