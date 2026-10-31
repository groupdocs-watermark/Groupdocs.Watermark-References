---
title: "from_extension Methode"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Ordnet die Dateierweiterung dem Dateityp zu."
type: docs
url: /de/python-net/groupdocs.watermark.common/filetype/from_extension/
is_root: false
weight: 1040
---


## from_extension {#extension}

Ordnet die Dateierweiterung dem Dateityp zu.

```python
def from_extension(cls, extension):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| extension | `str` | Die Dateierweiterung (einschließlich des Punktes "."). |

**Returns:** FileType: When the file type is supported returns it, otherwise returns the default `FileType.unknown` file type.

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wird ausgelöst, wenn `extension` null oder ein leerer String ist. |

### Siehe auch
* class [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype/)
