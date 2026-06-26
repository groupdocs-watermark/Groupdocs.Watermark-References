---
title: __init__ constructor
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Initializes a new instance of the ImageDctHashSearchCriteria class with a specified file path."
type: docs
url: /python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Initializes a new instance of the ImageDctHashSearchCriteria class with a specified file path.

```python
def __init__(self, file_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | The file path to load image from. |

### Example

```python
import groupdocs.watermark.search.searchcriteria as gws_sc

criteria = gws_sc.ImageDctHashSearchCriteria("logo.png")
```

## __init__ {#stream}

Initializes a new instance of the ImageDctHashSearchCriteria class with a specified stream.

```python
def __init__(self, stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| stream | `io.RawIOBase` | The stream to load image from. |

### See Also
* class [`ImageDctHashSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/)
