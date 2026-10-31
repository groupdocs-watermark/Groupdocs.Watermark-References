---
title: "metodo from_extension"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Mappa l'estensione del file al tipo di file."
type: docs
url: /it/python-net/groupdocs.watermark.common/filetype/from_extension/
is_root: false
weight: 1040
---


## from_extension {#extension}

Mappa l'estensione del file al tipo di file.

```python
def from_extension(cls, extension):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| extension | `str` | L'estensione del file (incluso il punto "."). |

**Returns:** FileType: When the file type is supported returns it, otherwise returns the default `FileType.unknown` file type.

| Genera | Descrizione |
| :- | :- |
| `ValueError` | Lanciata quando `extension` è null o una stringa vuota. |

### Vedi anche
* class [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype/)
