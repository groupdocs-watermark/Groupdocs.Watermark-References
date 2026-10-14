---
title: __init__ constructor
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Initializes ImageWatermarkResult with a unique watermark identifier obtained after a search process."
type: docs
url: /python-net/groupdocs.watermark.watermarks.results/imagewatermarkresult/__init__/
is_root: false
weight: 10
---


## __init__ {#watermark_id}

Initializes ImageWatermarkResult with a unique watermark identifier obtained after a search process. This identifier is used to retrieve additional properties for the watermark from the document's watermark information layer.

```python
def __init__(self, watermark_id):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| watermark_id | `str` | Unique watermark identifier obtained by the `Sign` or `Search` method of `GroupDocs.Signature.Signature`. |

### See Also
* class [`ImageWatermarkResult`](/watermark/python-net/groupdocs.watermark.watermarks.results/imagewatermarkresult/)
