---
title: "método from_extension"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Asocia la extensión del archivo con el tipo de archivo."
type: docs
url: /es/python-net/groupdocs.watermark.common/filetype/from_extension/
is_root: false
weight: 1040
---


## from_extension {#extension}

Asocia la extensión del archivo con el tipo de archivo.

```python
def from_extension(cls, extension):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| extension | `str` | La extensión del archivo (incluyendo el punto "."). |

**Returns:** FileType: When the file type is supported returns it, otherwise returns the default `FileType.unknown` file type.

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Lanzado cuando `extension` es nulo o una cadena vacía. |

### Ver también
* class [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype/)
