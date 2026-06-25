---
title: from_extension method
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.common/filetype/from_extension/
is_root: false
weight: 1040
---


## from_extension {#extension}

Maps the file extension to the file type.

```python
def from_extension(cls, extension):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| extension | `str` | The file extension (including the period "."). |

**Returns:** FileType: The corresponding file type if supported; otherwise returns `FileType.Unknown`.

| Raises | Description |
| :- | :- |
| `ValueError` | When `extension` is None or an empty string. |

### See Also
* class [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype/)
