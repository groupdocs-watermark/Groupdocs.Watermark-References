---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يُنشئ مثيلاً جديداً من ImageWatermark بمسار ملف محدد."
type: docs
url: /ar/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

يُنشئ مثيلاً جديداً من ImageWatermark بمسار ملف محدد.

```python
def __init__(self, file_path):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | `str` | المسار إلى الصورة التي سيتم استخدامها كعلامة مائية. |

### مثال

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.watermarks import ImageWatermark

    with Watermarker("document.docx") as watermarker:
        watermark = ImageWatermark("logo.png")
        watermarker.add(watermark)
        watermarker.save("watermarked.docx")
    ```

## __init__ {#stream}

يُنشئ ImageWatermark جديداً باستخدام تدفق الصورة المقدم.

```python
def __init__(self, stream):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| stream | `io.RawIOBase` | الدفق الذي يحتوي على الصورة التي سيتم استخدامها كعلامة مائية. |

### مثال

```python
import io
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark

with open("logo.png", "rb") as f:
    image_data = f.read()

with Watermarker("sample.docx") as watermarker:
    with ImageWatermark(stream=io.BytesIO(image_data)) as watermark:
        watermarker.add(watermark)
    watermarker.save("watermarked.docx")
```

### انظر أيضًا
* class [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/)
