---
title: get_supported_file_types method
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Retrieves the supported file types."
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

**Returns:** Iterable[FileType]: The sequence of the supported file types.

### Example

```python
    from groupdocs.watermark.common import FileType

    def list_supported_formats():
        # Enumerate every file type the library can open
        supported_file_types = FileType.get_supported_file_types()
        for file_type in sorted(supported_file_types, key=lambda x: x.extension):
            print(file_type)

    if __name__ == "__main__":
        list_supported_formats()
    ```

### See Also
* class [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype/)
