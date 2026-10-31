---
title: "__init__ konstruktor"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Menginisialisasi instance baru dari kelas WordProcessingLoadOptions."
type: docs
url: /id/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi sebuah instance baru dari kelas [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/).

```python
def __init__(self):
    ...
```

## __init__ {#password}

Menginisialisasi sebuah instance baru dari kelas WordProcessingLoadOptions dengan kata sandi yang ditentukan.

```python
def __init__(self, password):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| password | `str` | Kata sandi untuk membuka konten yang terenkripsi. |

### Contoh

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
    # lakukan operasi watermark
    pass
```

### Lihat Juga
* class [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/)
