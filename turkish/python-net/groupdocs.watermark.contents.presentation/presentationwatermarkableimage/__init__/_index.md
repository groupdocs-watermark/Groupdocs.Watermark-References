---
title: "__init__ yapıcı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Belirtilen görüntü verilerini kullanarak PresentationWatermarkableImage sınıfının yeni bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Belirtilen resim verileri kullanılarak [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/) sınıfının yeni bir örneğini başlatır.

```python
def __init__(self, image_data):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image_data | `list[int]` | `PresentationWatermarkableImage` oluşturmak için kullanılacak işaretsiz bayt dizisi. |

### Örnek

```python
import groupdocs.watermark.contents.presentation as gwc_ppt

with open("background.png", "rb") as f:
    img = gwc_ppt.PresentationWatermarkableImage(f.read())
```

### Ayrıca Bakınız
* class [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/)
