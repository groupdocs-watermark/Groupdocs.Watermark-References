---
title: "__init__ yapıcı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "ColorRange sınıfının yeni bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.watermark.search.search_criteria/colorrange/__init__/
is_root: false
weight: 10
---


## __init__

`[`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/)` sınıfının yeni bir örneğini başlatır.

```python
def __init__(self):
    ...
```

### Örnek

```python
from groupdocs.watermark.search.search_criteria import ColorRange

# Varsayılan bir renk aralığı oluşturun
color_range = ColorRange()
color_range.min_hue = -15
color_range.max_hue = 15
color_range.min_brightness = 0.01
color_range.max_brightness = 0.99
```

## __init__ {#exact_color}

`[`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/)` sınıfının belirtilen kesin renk ile yeni bir örneğini başlatır.

```python
def __init__(self, exact_color):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| exact_color | `Color` | Aralığın oluşturulduğu kesin renk. |

### Ayrıca Bakınız
* class [`ColorRange`](/watermark/python-net/groupdocs.watermark.search.search_criteria/colorrange/)
