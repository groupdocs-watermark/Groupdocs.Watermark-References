---
title: get_supported_file_types method
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.common/filetype/get_supported_file_types/
is_root: false
weight: 1060
---


## get_supported_file_types

Retrieves the supported file types.

```python
def get_supported_file_types(cls):
    ...
```

**Returns:** Iterable[FileType]: The sequence of supported file types.

### Example

```python
    from groupdocs.watermark.common import FileType

    supported = FileType.get_supported_file_types()
    for ft in supported:
        print(ft)
    ```

### See Also
* class [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype/)
