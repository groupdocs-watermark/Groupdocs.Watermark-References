---
title: "get_supported_file_types-methode"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Haalt de ondersteunde bestandstypen op."
type: docs
url: /nl/python-net/groupdocs.watermark.common/filetype/get_supported_file_types/
is_root: false
weight: 1060
---


## get_supported_file_types

Haalt de ondersteunde bestandstypen op.

```python
def get_supported_file_types(cls):
    ...
```

**Returns:** Iterable[FileType]: The sequence of the supported file types.

### Voorbeeld

```python
    from groupdocs.watermark.common import FileType

    def list_supported_formats():
        # Som alle bestandstypen op die de bibliotheek kan openen
        supported_file_types = FileType.get_supported_file_types()
        for file_type in sorted(supported_file_types, key=lambda x: x.extension):
            print(file_type)

    if __name__ == "__main__":
        list_supported_formats()
    ```

### Zie ook
* class [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype/)
