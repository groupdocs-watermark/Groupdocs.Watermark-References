---
title: "search मेथड"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "दस्तावेज़ में सभी संभावित वॉटरमार्क की खोज करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark/watermarker/search/
is_root: false
weight: 1190
---


## search

दस्तावेज़ में सभी संभावित वॉटरमार्क की खोज करता है।

खोज उन वस्तुओं में की जाती है जो [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/) में निर्दिष्ट हैं।

वॉटरमार्क खोजने के बारे में अधिक जानें https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def search(self):
    ...
```

**Returns:** The collection of possible watermarks.

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def search_by_text():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_text()
```

## search {#search_criteria}

निर्दिष्ट खोज मानदंडों के अनुसार संभावित वॉटरमार्क की खोज करता है।

खोज उन वस्तुओं में की जाती है जो [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/) में निर्दिष्ट हैं।

वॉटरमार्क खोजने के बारे में अधिक जानें: https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def search(self, search_criteria):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| search_criteria | `SearchCriteria` | उपयोग करने के लिए खोज मानदंड। |

**Returns:** The collection of possible watermarks.

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def search_by_text():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_text()
```

### संबंधित देखें
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
