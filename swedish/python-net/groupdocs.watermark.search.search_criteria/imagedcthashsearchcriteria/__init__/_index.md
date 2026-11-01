---
title: "__init__ konstruktor"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Initierar en ny ImageDctHashSearchCriteria-instans med en angiven filsökväg."
type: docs
url: /sv/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Initierar en ny ImageDctHashSearchCriteria-instans med en angiven filsökväg.

```python
def __init__(self, file_path):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | `str` | Filsökvägen för att läsa in bilden från. |

### Exempel

```python
    from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

    criteria = ImageDctHashSearchCriteria("./logo.png")
    ```

## __init__ {#stream}

Initierar en ny ImageDctHashSearchCriteria-instans med den tillhandahållna bildströmmen.

```python
def __init__(self, stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | `io.RawIOBase` | Strömmen för att läsa in bilden från. |

### Se även
* class [`ImageDctHashSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/)
