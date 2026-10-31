---
title: "__init__ konstruktor"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Menginisialisasi instance baru dari kelas PresentationLoadOptions."
type: docs
url: /id/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi instance baru dari kelas [`PresentationLoadOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/).

```python
def __init__(self):
    ...
```

### Contoh

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

Menginisialisasi instance baru dari kelas PresentationLoadOptions dengan kata sandi yang ditentukan.

```python
def __init__(self, password):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| password | `str` | Kata sandi untuk membuka konten yang terenkripsi. |

### Contoh

```python
    import groupdocs.watermark as gw
    from groupdocs.watermark.options.presentation import PresentationLoadOptions

    load_options = PresentationLoadOptions()
    ```

### Lihat Juga
* class [`PresentationLoadOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/)
