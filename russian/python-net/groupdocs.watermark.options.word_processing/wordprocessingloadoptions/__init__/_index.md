---
title: "__init__ конструктор"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Инициализирует новый экземпляр класса WordProcessingLoadOptions."
type: docs
url: /ru/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует новый экземпляр класса [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/).

```python
def __init__(self):
    ...
```

## __init__ {#password}

Инициализирует новый экземпляр класса WordProcessingLoadOptions с указанным паролем.

```python
def __init__(self, password):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| password | `str` | Пароль для открытия зашифрованного содержимого. |

### Пример

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
    # выполнять операции водяного знака
    pass
```

### См. также
* class [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/)
