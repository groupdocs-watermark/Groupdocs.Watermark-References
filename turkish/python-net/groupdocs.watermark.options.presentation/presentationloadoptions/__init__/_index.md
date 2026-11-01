---
title: "__init__ yapıcı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "PresentationLoadOptions sınıfının yeni bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Yeni bir [`PresentationLoadOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/) sınıfı örneği başlatır.

```python
def __init__(self):
    ...
```

### Örnek

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.presentation import PresentationLoadOptions

def remove_slide_background():
    with Watermarker("./presentation.pptx", PresentationLoadOptions()) as watermarker:
        content = watermarker.get_content()
        content.slides[0].image_fill_format.background_image = None
        watermarker.save("./output.pptx")
```

## __init__ {#password}

Belirtilen bir şifre ile yeni bir PresentationLoadOptions sınıfı örneği başlatır.

```python
def __init__(self, password):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| password | `str` | Şifreli içeriği açmak için şifre. |

### Örnek

```python
    import groupdocs.watermark as gw
    from groupdocs.watermark.options.presentation import PresentationLoadOptions

    load_options = PresentationLoadOptions()
    ```

### Ayrıca Bakınız
* class [`PresentationLoadOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/)
