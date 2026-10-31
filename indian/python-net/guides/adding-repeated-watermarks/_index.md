---
title: "दोहराए गए वॉटरमार्क जोड़ना"
linkTitle: "Repeated watermarks"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "GroupDocs.Watermark for Python को .NET के माध्यम से उपयोग करके स्पेसिंग, रोटेशन और पैटर्न के साथ दोहराए गए (टाइल्ड) टेक्स्ट या इमेज वॉटरमार्क जोड़ें।"
type: docs
url: /hi/python-net/guides/adding-repeated-watermarks/
is_root: false
weight: 70
---


दोहराए गए (टाइल्ड) वॉटरमार्क आपको पूरे पृष्ठों को टेक्स्ट या इमेज पैटर्न से कवर करने देते हैं। आप स्पेसिंग, रोटेशन, ऑफसेट को नियंत्रित कर सकते हैं, और वॉटरमार्क पर `tile_options` सेट करके विभिन्न टाइलिंग टेम्प्लेट चुन सकते हैं।

## Add a repeated text watermark

नीचे दिया गया उदाहरण पूरे पृष्ठ पर तिरछा टेक्स्ट वॉटरमार्क टाइल करता है। `line_spacing` और `watermark_spacing` पृष्ठ के प्रतिशत के रूप में व्यक्त किए गए हैं, और `tile_type` टाइलिंग टेम्प्लेट चुनता है।

{{< tabs \"code-example-adding-repeated-watermarks\">}}
{{< tab \"add_repeated_watermark.py\" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import (
    TextWatermark, Font, Color, TextAlignment,
    TileOptions, TileType, MeasureValue, TileMeasureType,
)

def add_repeated_watermark():
    with Watermarker("./sample.pdf") as watermarker:
        watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 19.0))
        watermark.foreground_color = Color.gray
        watermark.opacity = 0.3
        watermark.rotate_angle = -45.0
        watermark.text_alignment = TextAlignment.CENTER

        # पृष्ठ के प्रतिशत के रूप में पंक्तियों और दोहराए गए वॉटरमार्क के बीच की दूरी
        line_spacing = MeasureValue()
        line_spacing.measure_type = TileMeasureType.PERCENT
        line_spacing.value = 12.0
        watermark_spacing = MeasureValue()
        watermark_spacing.measure_type = TileMeasureType.PERCENT
        watermark_spacing.value = 10.0

        # वॉटरमार्क को पूरे पृष्ठ पर टाइल करें
        tile_options = TileOptions()
        tile_options.tile_type = TileType.ONE_THIRD_OFFSET
        tile_options.line_spacing = line_spacing
        tile_options.watermark_spacing = watermark_spacing
        watermark.tile_options = tile_options

        watermarker.add(watermark)
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    add_repeated_watermark()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/adding-repeated-watermarks/sample.pdf) क्लिक करें।

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 379 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/adding-repeated-watermarks/add_repeated_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

आप इस तरह से पृष्ठ पर लोगो या सील टाइल करने के लिए [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) को [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/) से बदल सकते हैं — इमेज वॉटरमार्क पर समान `tile_options` सेट करें।

**Use case:** Protect sensitive PDFs by overlaying a tiled "Confidential" text across every page, or reinforce branding by repeating a logo in the background.
