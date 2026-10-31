---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "एक प्रारंभिक कोण और एक समाप्ति कोण के साथ नया RotateAngleSearchCriteria प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#min_angle-max_angle}

एक प्रारंभिक कोण और एक समाप्ति कोण के साथ नया RotateAngleSearchCriteria प्रारंभ करता है।

```python
def __init__(self, min_angle, max_angle):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| min_angle | `float` | डिग्री में प्रारंभिक कोण। |
| max_angle | `float` | डिग्री में समाप्ति कोण। |

### उदाहरण

```python
from groupdocs.watermark.search.search_criteria import RotateAngleSearchCriteria

# 30 से 60 डिग्री के बीच घुमाए गए वॉटरमार्क की खोज करें
angle_criteria = RotateAngleSearchCriteria(30, 60)
```

### संबंधित देखें
* class [`RotateAngleSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/)
