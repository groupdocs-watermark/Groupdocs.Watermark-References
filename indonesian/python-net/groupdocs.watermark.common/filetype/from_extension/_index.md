---
title: "from_extension metode"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Memetakan ekstensi file ke tipe file."
type: docs
url: /id/python-net/groupdocs.watermark.common/filetype/from_extension/
is_root: false
weight: 1040
---


## from_extension {#extension}

Memetakan ekstensi file ke tipe file.

```python
def from_extension(cls, extension):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| extension | `str` | Ekstensi file (termasuk titik "."). |

**Returns:** FileType: When the file type is supported returns it, otherwise returns the default `FileType.unknown` file type.

| Menaikkan | Deskripsi |
| :- | :- |
| `ValueError` | Dilempar ketika `extension` bernilai null atau string kosong. |

### Lihat Juga
* class [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype/)
