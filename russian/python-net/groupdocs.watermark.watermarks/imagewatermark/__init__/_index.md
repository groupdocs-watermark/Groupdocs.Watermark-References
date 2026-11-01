---
title: "__init__ конструктор"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Инициализирует новый экземпляр ImageWatermark с указанным путём к файлу."
type: docs
url: /ru/python-net/groupdocs.watermark.watermarks/imagewatermark/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Инициализирует новый экземпляр ImageWatermark с указанным путём к файлу.

```python
def __init__(self, file_path):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | `str` | Путь к изображению, которое будет использоваться в качестве водяного знака. |

### Пример

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.watermarks import ImageWatermark

    with Watermarker("document.docx") as watermarker:
        watermark = ImageWatermark("logo.png")
        watermarker.add(watermark)
        watermarker.save("watermarked.docx")
    ```

## __init__ {#stream}

Инициализирует новый ImageWatermark с предоставленным потоком изображения.

```python
def __init__(self, stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | `io.RawIOBase` | Поток, содержащий изображение, которое будет использоваться в качестве водяного знака. |

### Пример

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

### См. также
* class [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/)
