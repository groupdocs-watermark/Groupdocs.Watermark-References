---
title: "from_extension methode"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Koppelt de bestandsextensie aan het bestandstype."
type: docs
url: /nl/python-net/groupdocs.watermark.common/filetype/from_extension/
is_root: false
weight: 1040
---


## from_extension {#extension}

Koppelt de bestandsextensie aan het bestandstype.

```python
def from_extension(cls, extension):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| extension | `str` | De bestandsextensie (inclusief de punt "."). |

**Returns:** FileType: When the file type is supported returns it, otherwise returns the default `FileType.unknown` file type.

| Verhoogt | Beschrijving |
| :- | :- |
| `ValueError` | Wordt gegooid wanneer `extension` null of een lege tekenreeks is. |

### Zie ook
* class [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype/)
