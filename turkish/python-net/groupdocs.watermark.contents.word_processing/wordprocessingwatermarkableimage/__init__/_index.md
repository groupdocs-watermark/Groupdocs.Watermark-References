---
title: "__init__ yapıcı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Belirtilen görüntü verilerini kullanarak WordProcessingWatermarkableImage sınıfının yeni bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/__init__/
is_root: false
weight: 10
---


## __init__ {#image_data}

Belirtilen görüntü verisini kullanarak [`WordProcessingWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/) sınıfının yeni bir örneğini başlatır.

```python
def __init__(self, image_data):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image_data | `list[int]` | `WordProcessingWatermarkableImage`'ı oluşturmak için kullanılacak işaretsiz baytların dizisi. |

### Örnek

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.word_processing as gwc_wp

with open("test.png", "rb") as f:
    img_bytes = f.read()

image = gwc_wp.WordProcessingWatermarkableImage(img_bytes)
```

### Ayrıca Bakınız
* class [`WordProcessingWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/)
