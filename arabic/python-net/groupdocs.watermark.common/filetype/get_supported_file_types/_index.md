---
title: "طريقة get_supported_file_types"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يسترجع أنواع الملفات المدعومة."
type: docs
url: /ar/python-net/groupdocs.watermark.common/filetype/get_supported_file_types/
is_root: false
weight: 1060
---


## get_supported_file_types

يسترجع أنواع الملفات المدعومة.

```python
def get_supported_file_types(cls):
    ...
```

**Returns:** Iterable[FileType]: The sequence of the supported file types.

### مثال

```python
    from groupdocs.watermark.common import FileType

    def list_supported_formats():
        # عدد جميع أنواع الملفات التي يمكن للمكتبة فتحها
        supported_file_types = FileType.get_supported_file_types()
        for file_type in sorted(supported_file_types, key=lambda x: x.extension):
            print(file_type)

    if __name__ == "__main__":
        list_supported_formats()
    ```

### انظر أيضًا
* class [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype/)
