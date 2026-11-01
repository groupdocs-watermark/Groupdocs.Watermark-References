---
title: "метод get_supported_file_types"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Получает поддерживаемые типы файлов."
type: docs
url: /ru/python-net/groupdocs.watermark.common/filetype/get_supported_file_types/
is_root: false
weight: 1060
---


## get_supported_file_types

Получает поддерживаемые типы файлов.

```python
def get_supported_file_types(cls):
    ...
```

**Returns:** Iterable[FileType]: The sequence of the supported file types.

### Пример

```python
    from groupdocs.watermark.common import FileType

    def list_supported_formats():
        # Перечислите все типы файлов, которые библиотека может открывать
        supported_file_types = FileType.get_supported_file_types()
        for file_type in sorted(supported_file_types, key=lambda x: x.extension):
            print(file_type)

    if __name__ == "__main__":
        list_supported_formats()
    ```

### См. также
* class [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype/)
