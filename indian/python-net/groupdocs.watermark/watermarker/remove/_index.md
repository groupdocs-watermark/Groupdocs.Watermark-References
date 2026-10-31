---
title: "remove मेथड"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "दस्तावेज़ से एक वॉटरमार्क हटाता है।"
type: docs
url: /hi/python-net/groupdocs.watermark/watermarker/remove/
is_root: false
weight: 1100
---


## remove {#possible_watermark}

दस्तावेज़ से एक वॉटरमार्क हटाता है।

वॉटरमार्क हटाने के बारे में अधिक जानें: पाए गए वॉटरमार्क हटाना।

```python
def remove(self, possible_watermark):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| possible_watermark | `PossibleWatermark` | हटाने के लिए वॉटरमार्क। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker

def remove_first_watermark():
    with Watermarker("./document.pdf") as watermarker:
        watermarks = watermarker.search()
        if watermarks:
            watermarker.remove(watermarks[0])
        watermarker.save("./output.pdf")
```

## remove {#possible_watermarks}

दस्तावेज़ से संग्रह में सभी वॉटरमार्क हटाता है।

GroupDocs दस्तावेज़ीकरण में वॉटरमार्क हटाने के बारे में अधिक जानें।

```python
def remove(self, possible_watermarks):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| possible_watermarks | `PossibleWatermarkCollection` | हटाने के लिए वॉटरमार्क का संग्रह। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def remove_watermark():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search()
        # इंडेक्स वैध रखने के लिए उल्टे क्रम में हटाएँ
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.pdf")
```

### संबंधित देखें
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
