---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يُهيئ نسخة جديدة من فئة PresentationLoadOptions."
type: docs
url: /ar/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

ينشئ مثلاً جديداً من [`PresentationLoadOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/) فئة.

```python
def __init__(self):
    ...
```

### مثال

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

ينشئ مثلاً جديداً من فئة PresentationLoadOptions باستخدام كلمة مرور محددة.

```python
def __init__(self, password):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| password | `str` | كلمة المرور لفتح محتوى مشفر. |

### مثال

```python
    import groupdocs.watermark as gw
    from groupdocs.watermark.options.presentation import PresentationLoadOptions

    load_options = PresentationLoadOptions()
    ```

### انظر أيضًا
* class [`PresentationLoadOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/)
