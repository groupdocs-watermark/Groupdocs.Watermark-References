---
title: "get_supported_file_types 方法"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "检索受支持的文件类型。"
type: docs
url: /zh/python-net/groupdocs.watermark.common/filetype/get_supported_file_types/
is_root: false
weight: 1060
---


## get_supported_file_types

检索受支持的文件类型。

```python
def get_supported_file_types(cls):
    ...
```

**Returns:** Iterable[FileType]: The sequence of the supported file types.

### 示例

```python
    from groupdocs.watermark.common import FileType

    def list_supported_formats():
        # 列举库可以打开的所有文件类型
        supported_file_types = FileType.get_supported_file_types()
        for file_type in sorted(supported_file_types, key=lambda x: x.extension):
            print(file_type)

    if __name__ == "__main__":
        list_supported_formats()
    ```

### 另请参见
* class [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype/)
