---
title: "HyperlinkPossibleWatermark क्लास"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "PowerPoint सामग्री में संभावित हाइपरलिंक वॉटरमार्क दर्शाता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/
is_root: false
weight: 60
---


## HyperlinkPossibleWatermark class

PowerPoint सामग्री में संभावित हाइपरलिंक वॉटरमार्क दर्शाता है।

HyperlinkPossibleWatermark प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### गुणधर्म
| गुणधर्म | विवरण |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/height/) | इस HyperlinkPossibleWatermark की ऊँचाई। |
| [parent](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/parent/) | इस HyperlinkPossibleWatermark का पैरेंट। |
| [rotate_angle](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/rotate_angle/) | इस HyperlinkPossibleWatermark का घूर्णन कोण डिग्री में। |
| [text](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/text/) | इस HyperlinkPossibleWatermark का URL। |
| [unit_of_measurement](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/unit_of_measurement/) | इस [`HyperlinkPossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/) की माप इकाई। |
| [width](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/width/) | इस HyperlinkPossibleWatermark की चौड़ाई। |
| [x](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/x/) | इस HyperlinkPossibleWatermark का x-निर्देशांक। |
| [y](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/y/) | इस [`HyperlinkPossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/hyperlinkpossiblewatermark/) का y-निर्देशांक। |
| [formatted_text_fragments](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/formatted_text_fragments/) | इस [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) के स्वरूपित टेक्स्ट फ्रैगमेंट्स का संग्रह। ([`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) से विरासत में मिला) |
| [image_data](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/image_data/) | इस [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) की छवि या None यदि वॉटरमार्क में कोई छवि नहीं है। ([`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) से विरासत में मिला) |
| [page_number](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/page_number/) | वॉटरमार्क जहाँ रखा गया है उसका पृष्ठ संख्या। ([`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) से विरासत में मिला) |

### उदाहरण

```python
import re
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search import HyperlinkPossibleWatermark
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    possible = watermarker.search(TextSearchCriteria(re.compile(r"someurl\.com")))
    for i in range(len(possible) - 1, -1, -1):
        if isinstance(possible[i], HyperlinkPossibleWatermark):
            print(possible[i].text)
            watermarker.remove(possible[i])
    watermarker.save("./output.pdf")
```

### संबंधित देखें
* module [`groupdocs.watermark.search`](/watermark/python-net/groupdocs.watermark.search/)
