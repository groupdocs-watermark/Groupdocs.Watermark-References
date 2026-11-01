---
title: "from_extension メソッド"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "ファイル拡張子をファイルタイプにマッピングします。"
type: docs
url: /ja/python-net/groupdocs.watermark.common/filetype/from_extension/
is_root: false
weight: 1040
---


## from_extension {#extension}

ファイル拡張子をファイルタイプにマッピングします。

```python
def from_extension(cls, extension):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| extension | `str` | ファイル拡張子（ピリオド「.」を含む）。 |

**Returns:** FileType: When the file type is supported returns it, otherwise returns the default `FileType.unknown` file type.

| 例外が発生 | 説明 |
| :- | :- |
| `ValueError` | `extension` が null または空文字列の場合にスローされます。 |

### 関連項目
* class [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype/)
