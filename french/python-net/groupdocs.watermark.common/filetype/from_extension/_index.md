---
title: "méthode from_extension"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Mappe l'extension de fichier au type de fichier."
type: docs
url: /fr/python-net/groupdocs.watermark.common/filetype/from_extension/
is_root: false
weight: 1040
---


## from_extension {#extension}

Mappe l'extension de fichier au type de fichier.

```python
def from_extension(cls, extension):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| extension | `str` | L'extension du fichier (y compris le point "."). |

**Returns:** FileType: When the file type is supported returns it, otherwise returns the default `FileType.unknown` file type.

| Lève | Description |
| :- | :- |
| `ValueError` | Lancée lorsque `extension` est nul ou une chaîne vide. |

### Voir aussi
* class [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype/)
