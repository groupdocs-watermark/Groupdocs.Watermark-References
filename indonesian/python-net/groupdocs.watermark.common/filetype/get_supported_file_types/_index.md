---
title: "get_supported_file_types metode"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mengambil tipe file yang didukung."
type: docs
url: /id/python-net/groupdocs.watermark.common/filetype/get_supported_file_types/
is_root: false
weight: 1060
---


## get_supported_file_types

Mengambil tipe file yang didukung.

```python
def get_supported_file_types(cls):
    ...
```

**Returns:** Iterable[FileType]: The sequence of the supported file types.

### Contoh

```python
    from groupdocs.watermark.common import FileType

    def list_supported_formats():
        # Enumerasikan setiap jenis file yang dapat dibuka oleh perpustakaan
        supported_file_types = FileType.get_supported_file_types()
        for file_type in sorted(supported_file_types, key=lambda x: x.extension):
            print(file_type)

    if __name__ == "__main__":
        list_supported_formats()
    ```

### Lihat Juga
* class [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype/)
