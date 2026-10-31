---
title: "or_ मेथड"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "तार्किक OR ऑपरेटर का उपयोग करके इस SearchCriteria को अन्य मानदंडों के साथ संयोजित करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/
is_root: false
weight: 1040
---


## or_ {#other}

तार्किक OR ऑपरेटर का उपयोग करके इस SearchCriteria को अन्य मानदंडों के साथ संयोजित करता है।

```python
def or_(self, other):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| other | `SearchCriteria` | संयुक्त करने के लिए खोज मानदंड। |

**Returns:** SearchCriteria: Combined search criteria.

### उदाहरण

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.search.search_criteria import (
        ImageDctHashSearchCriteria,
        TextSearchCriteria,
    )

    with Watermarker("./document.pdf") as watermarker:
        image_criteria = ImageDctHashSearchCriteria("./logo.png")
        text_criteria = TextSearchCriteria("CONFIDENTIAL")
        combined = image_criteria.or_(text_criteria)
        results = watermarker.search(combined)
        print(f"Found {len(results)} possible watermark(s)")
    ```

### संबंधित देखें
* class [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)
