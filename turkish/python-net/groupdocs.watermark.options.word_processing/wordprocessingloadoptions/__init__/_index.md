---
title: "__init__ yapıcı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "WordProcessingLoadOptions sınıfının yeni bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Yeni bir [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/) sınıfı örneği başlatır.

```python
def __init__(self):
    ...
```

## __init__ {#password}

Belirtilen bir şifre ile WordProcessingLoadOptions sınıfının yeni bir örneğini başlatır.

```python
def __init__(self, password):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| password | `str` | Şifreli içeriği açmak için şifre. |

### Örnek

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
    # filigran işlemlerini gerçekleştir
    pass
```

### Ayrıca Bakınız
* class [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/)
