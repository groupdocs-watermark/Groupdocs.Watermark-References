---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يُنشئ مثيلاً جديدًا من RotateAngleSearchCriteria بزاوية بداية وزاوية نهاية."
type: docs
url: /ar/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#min_angle-max_angle}

يُنشئ مثيلاً جديدًا من RotateAngleSearchCriteria بزاوية بداية وزاوية نهاية.

```python
def __init__(self, min_angle, max_angle):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| min_angle | `float` | زاوية البداية بالدرجات. |
| max_angle | `float` | زاوية النهاية بالدرجات. |

### مثال

```python
from groupdocs.watermark.search.search_criteria import RotateAngleSearchCriteria

# البحث عن العلامات المائية المدارة بين 30 و60 درجة
angle_criteria = RotateAngleSearchCriteria(30, 60)
```

### انظر أيضًا
* class [`RotateAngleSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/)
