---
title: "get_supported_file_types メソッド"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "サポートされているファイルタイプを取得します。"
type: docs
url: /ja/python-net/groupdocs.watermark.common/filetype/get_supported_file_types/
is_root: false
weight: 1060
---


## get_supported_file_types

サポートされているファイルタイプを取得します。

```python
def get_supported_file_types(cls):
    ...
```

**Returns:** Iterable[FileType]: The sequence of the supported file types.

### 例

```python
    from groupdocs.watermark.common import FileType

    def list_supported_formats():
        # ライブラリが開くことのできるすべてのファイルタイプを列挙してください
        supported_file_types = FileType.get_supported_file_types()
        for file_type in sorted(supported_file_types, key=lambda x: x.extension):
            print(file_type)

    if __name__ == "__main__":
        list_supported_formats()
    ```

### 関連項目
* class [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype/)
