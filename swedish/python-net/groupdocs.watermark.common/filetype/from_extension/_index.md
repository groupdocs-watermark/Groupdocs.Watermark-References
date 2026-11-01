---
title: "from_extension-metod"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Kopplar filändelsen till filtypen."
type: docs
url: /sv/python-net/groupdocs.watermark.common/filetype/from_extension/
is_root: false
weight: 1040
---


## from_extension {#extension}

Kopplar filändelsen till filtypen.

```python
def from_extension(cls, extension):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| extension | `str` | Filändelsen (inklusive punkten "."). |

**Returns:** FileType: When the file type is supported returns it, otherwise returns the default `FileType.unknown` file type.

| Kastar | Beskrivning |
| :- | :- |
| `ValueError` | Kastas när `extension` är null eller en tom sträng. |

### Se även
* class [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype/)
