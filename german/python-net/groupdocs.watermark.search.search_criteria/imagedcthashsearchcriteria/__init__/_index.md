---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Initialisiert eine neue ImageDctHashSearchCriteria‑Instanz mit einem angegebenen Dateipfad."
type: docs
url: /de/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Initialisiert eine neue ImageDctHashSearchCriteria‑Instanz mit einem angegebenen Dateipfad.

```python
def __init__(self, file_path):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | `str` | Der Dateipfad, von dem das Bild geladen wird. |

### Beispiel

```python
    from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

    criteria = ImageDctHashSearchCriteria("./logo.png")
    ```

## __init__ {#stream}

Initialisiert eine neue ImageDctHashSearchCriteria‑Instanz mit dem bereitgestellten Bildstrom.

```python
def __init__(self, stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | `io.RawIOBase` | Der Stream, von dem das Bild geladen wird. |

### Siehe auch
* class [`ImageDctHashSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/)
