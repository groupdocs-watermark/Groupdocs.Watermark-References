---
title: "metodo get_supported_file_types"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Recupera i tipi di file supportati."
type: docs
url: /it/python-net/groupdocs.watermark.common/filetype/get_supported_file_types/
is_root: false
weight: 1060
---


## get_supported_file_types

Recupera i tipi di file supportati.

```python
def get_supported_file_types(cls):
    ...
```

**Returns:** Iterable[FileType]: The sequence of the supported file types.

### Esempio

```python
    from groupdocs.watermark.common import FileType

    def list_supported_formats():
        # Elenca tutti i tipi di file che la libreria può aprire
        supported_file_types = FileType.get_supported_file_types()
        for file_type in sorted(supported_file_types, key=lambda x: x.extension):
            print(file_type)

    if __name__ == "__main__":
        list_supported_formats()
    ```

### Vedi anche
* class [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype/)
