---
title: "get_supported_file_types méthode"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Récupère les types de fichiers pris en charge."
type: docs
url: /fr/python-net/groupdocs.watermark.common/filetype/get_supported_file_types/
is_root: false
weight: 1060
---


## get_supported_file_types

Récupère les types de fichiers pris en charge.

```python
def get_supported_file_types(cls):
    ...
```

**Returns:** Iterable[FileType]: The sequence of the supported file types.

### Exemple

```python
    from groupdocs.watermark.common import FileType

    def list_supported_formats():
        # Énumérez chaque type de fichier que la bibliothèque peut ouvrir
        supported_file_types = FileType.get_supported_file_types()
        for file_type in sorted(supported_file_types, key=lambda x: x.extension):
            print(file_type)

    if __name__ == "__main__":
        list_supported_formats()
    ```

### Voir aussi
* class [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype/)
