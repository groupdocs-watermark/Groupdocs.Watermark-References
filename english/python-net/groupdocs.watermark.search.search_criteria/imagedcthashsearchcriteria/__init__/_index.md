---
title: __init__ constructor
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Initializes a new ImageDctHashSearchCriteria instance with a specified file path."
type: docs
url: /python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Initializes a new ImageDctHashSearchCriteria instance with a specified file path.

```python
def __init__(self, file_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | The file path to load image from. |

### Example

```python
    from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

    criteria = ImageDctHashSearchCriteria("./logo.png")
    ```

## __init__ {#stream}

Initializes a new ImageDctHashSearchCriteria instance with the provided image stream.

```python
def __init__(self, stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| stream | `io.RawIOBase` | The stream to load image from. |

### See Also
* class [`ImageDctHashSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/)
