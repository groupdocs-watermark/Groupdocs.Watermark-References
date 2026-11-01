---
title: "__init__ yapıcı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Belirtilen görüntü verilerini kullanarak DiagramWatermarkableImage sınıfının yeni bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Belirtilen görüntü verisini kullanarak [`DiagramWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/) sınıfının yeni bir örneğini başlatır.

```python
def __init__(self, image_data):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image_data | `list[int]` | `DiagramWatermarkableImage`'ı oluşturmak için kullanılacak işaretsiz bayt dizisi. |

### Örnek

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.diagram as gwc_vsdx

with open("test.png", "rb") as f:
    img = gwc_vsdx.DiagramWatermarkableImage(f.read())
```

### Ayrıca Bakınız
* class [`DiagramWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramwatermarkableimage/)
