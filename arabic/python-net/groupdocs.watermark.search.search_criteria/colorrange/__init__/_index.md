---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يقوم بإنشاء نسخة جديدة من الفئة ColorRange."
type: docs
url: /ar/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/
is_root: false
weight: 10
---


## __init__

ينشئ مثلاً جديدًا من الفئة [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/).

```python
def __init__(self):
    ...
```

### مثال

```python
from groupdocs.watermark.search.search_criteria import ColorRange

# إنشاء نطاق ألوان افتراضي
color_range = ColorRange()
color_range.min_hue = -15
color_range.max_hue = 15
color_range.min_brightness = 0.01
color_range.max_brightness = 0.99
```

## __init__ {#exact_color}

ينشئ مثلاً جديدًا من [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/) بلون محدد دقيق.

```python
def __init__(self, exact_color):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| exact_color | `Color` | اللون الدقيق الذي يتم إنشاء النطاق منه. |

### انظر أيضًا
* class [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/)
