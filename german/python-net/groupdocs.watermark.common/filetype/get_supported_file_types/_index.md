---
title: "get_supported_file_types-Methode"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Ruft die unterstützten Dateitypen ab."
type: docs
url: /de/python-net/groupdocs.watermark.common/filetype/get_supported_file_types/
is_root: false
weight: 1060
---


## get_supported_file_types

Ruft die unterstützten Dateitypen ab.

```python
def get_supported_file_types(cls):
    ...
```

**Returns:** Iterable[FileType]: The sequence of the supported file types.

### Beispiel

```python
    from groupdocs.watermark.common import FileType

    def list_supported_formats():
        # Alle Dateitypen auflisten, die die Bibliothek öffnen kann
        supported_file_types = FileType.get_supported_file_types()
        for file_type in sorted(supported_file_types, key=lambda x: x.extension):
            print(file_type)

    if __name__ == "__main__":
        list_supported_formats()
    ```

### Siehe auch
* class [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype/)
