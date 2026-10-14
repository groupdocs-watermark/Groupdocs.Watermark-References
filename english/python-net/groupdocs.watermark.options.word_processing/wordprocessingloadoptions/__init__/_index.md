---
title: __init__ constructor
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Initializes a new instance of the WordProcessingLoadOptions class."
type: docs
url: /python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new instance of the [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/) class.

```python
def __init__(self):
    ...
```

## __init__ {#password}

Initializes a new instance of the WordProcessingLoadOptions class with a specified password.

```python
def __init__(self, password):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| password | `str` | The password for opening an encrypted content. |

### Example

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
    # perform watermark operations
    pass
```

### See Also
* class [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/)
