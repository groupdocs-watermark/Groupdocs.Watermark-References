---
title: "__init__ constructeur"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Initialise une nouvelle instance ImageDctHashSearchCriteria avec un chemin de fichier spécifié."
type: docs
url: /fr/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Initialise une nouvelle instance ImageDctHashSearchCriteria avec un chemin de fichier spécifié.

```python
def __init__(self, file_path):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | `str` | Le chemin du fichier à partir duquel charger l'image. |

### Exemple

```python
    from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

    criteria = ImageDctHashSearchCriteria("./logo.png")
    ```

## __init__ {#stream}

Initialise une nouvelle instance ImageDctHashSearchCriteria avec le flux d'image fourni.

```python
def __init__(self, stream):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| stream | `io.RawIOBase` | Le flux à partir duquel charger l'image. |

### Voir aussi
* class [`ImageDctHashSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/)
