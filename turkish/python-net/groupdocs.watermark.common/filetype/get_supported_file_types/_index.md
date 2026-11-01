---
title: "get_supported_file_types yöntemi"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Desteklenen dosya türlerini alır."
type: docs
url: /tr/python-net/groupdocs.watermark.common/filetype/get_supported_file_types/
is_root: false
weight: 1060
---


## get_supported_file_types

Desteklenen dosya türlerini alır.

```python
def get_supported_file_types(cls):
    ...
```

**Returns:** Iterable[FileType]: The sequence of the supported file types.

### Örnek

```python
    from groupdocs.watermark.common import FileType

    def list_supported_formats():
        # Kütüphanenin açabildiği her dosya türünü listeleyin
        supported_file_types = FileType.get_supported_file_types()
        for file_type in sorted(supported_file_types, key=lambda x: x.extension):
            print(file_type)

    if __name__ == "__main__":
        list_supported_formats()
    ```

### Ayrıca Bakınız
* class [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype/)
