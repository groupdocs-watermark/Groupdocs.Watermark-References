---
title: "método get_supported_file_types"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Recupera los tipos de archivo compatibles."
type: docs
url: /es/python-net/groupdocs.watermark.common/filetype/get_supported_file_types/
is_root: false
weight: 1060
---


## get_supported_file_types

Recupera los tipos de archivo compatibles.

```python
def get_supported_file_types(cls):
    ...
```

**Returns:** Iterable[FileType]: The sequence of the supported file types.

### Ejemplo

```python
    from groupdocs.watermark.common import FileType

    def list_supported_formats():
        # Enumere cada tipo de archivo que la biblioteca puede abrir
        supported_file_types = FileType.get_supported_file_types()
        for file_type in sorted(supported_file_types, key=lambda x: x.extension):
            print(file_type)

    if __name__ == "__main__":
        list_supported_formats()
    ```

### Ver también
* class [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype/)
