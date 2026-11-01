---
title: "__init__ constructor"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Initialiseert een nieuwe ImageDctHashSearchCriteria‑instantie met een opgegeven bestandspad."
type: docs
url: /nl/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Initialiseert een nieuwe ImageDctHashSearchCriteria‑instantie met een opgegeven bestandspad.

```python
def __init__(self, file_path):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | `str` | Het bestandspad om de afbeelding van te laden. |

### Voorbeeld

```python
    from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

    criteria = ImageDctHashSearchCriteria("./logo.png")
    ```

## __init__ {#stream}

Initialiseert een nieuwe ImageDctHashSearchCriteria‑instantie met de opgegeven afbeeldingsstroom.

```python
def __init__(self, stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | `io.RawIOBase` | De stream om de afbeelding van te laden. |

### Zie ook
* class [`ImageDctHashSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/)
