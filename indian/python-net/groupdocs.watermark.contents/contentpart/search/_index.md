---
title: "search मेथड"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "निर्दिष्ट खोज मानदंडों के अनुसार संभावित वॉटरमार्क खोजता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.contents/contentpart/search/
is_root: false
weight: 1030
---


## search {#search_criteria}

निर्दिष्ट खोज मानदंडों के अनुसार संभावित वॉटरमार्क खोजता है। खोज उन ऑब्जेक्ट्स पर की जाती है जो [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) में सूचीबद्ध हैं।

```python
def search(self, search_criteria):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| search_criteria | `SearchCriteria` | उपयोग करने के लिए खोज मानदंड। |

**Returns:** The collection of the possible watermarks.

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
    print("Found", len(possible), "possible watermark(s)")
```

## search

सामग्री में सभी संभावित वॉटरमार्क खोजता है।

खोज उन वस्तुओं में की जाती है जो [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/) में निर्दिष्ट हैं।

```python
def search(self):
    ...
```

**Returns:** Iterable[Watermark]: The collection of the possible watermarks.

### संबंधित देखें
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)
