---
title: __init__ constructor
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.options.presentation/presentationloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new instance of the [`PresentationLoadOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/) class.

```python
def __init__(self):
    ...
```

## __init__ {#password}

Initializes a new instance of the PresentationLoadOptions class with a specified password.

```python
def __init__(self, password):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| password | `str` | The password for opening an encrypted content. |

### Example

```python
import groupdocs.watermark as gw

load_options = gw.PresentationLoadOptions(password="mySecret")
```

### See Also
* class [`PresentationLoadOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/)
