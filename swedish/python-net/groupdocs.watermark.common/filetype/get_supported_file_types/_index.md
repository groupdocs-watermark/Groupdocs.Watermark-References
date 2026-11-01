---
title: "metoden get_supported_file_types"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Hämtar de stödda filtyperna."
type: docs
url: /sv/python-net/groupdocs.watermark.common/filetype/get_supported_file_types/
is_root: false
weight: 1060
---


## get_supported_file_types

Hämtar de stödda filtyperna.

```python
def get_supported_file_types(cls):
    ...
```

**Returns:** Iterable[FileType]: The sequence of the supported file types.

### Exempel

```python
    from groupdocs.watermark.common import FileType

    def list_supported_formats():
        # Enumerera alla filtyper som biblioteket kan öppna
        supported_file_types = FileType.get_supported_file_types()
        for file_type in sorted(supported_file_types, key=lambda x: x.extension):
            print(file_type)

    if __name__ == "__main__":
        list_supported_formats()
    ```

### Se även
* class [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype/)
