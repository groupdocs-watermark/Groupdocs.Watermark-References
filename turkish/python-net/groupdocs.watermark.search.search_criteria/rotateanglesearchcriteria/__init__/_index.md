---
title: "__init__ yapıcı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Başlangıç açısı ve bitiş açısı ile yeni bir RotateAngleSearchCriteria başlatır."
type: docs
url: /tr/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#min_angle-max_angle}

Başlangıç açısı ve bitiş açısı ile yeni bir RotateAngleSearchCriteria başlatır.

```python
def __init__(self, min_angle, max_angle):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| min_angle | `float` | Başlangıç açısı derece cinsinden. |
| max_angle | `float` | Bitiş açısı derece cinsinden. |

### Örnek

```python
from groupdocs.watermark.search.search_criteria import RotateAngleSearchCriteria

# 30 ile 60 derece arasında döndürülmüş filigranları ara
angle_criteria = RotateAngleSearchCriteria(30, 60)
```

### Ayrıca Bakınız
* class [`RotateAngleSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/rotateanglesearchcriteria/)
