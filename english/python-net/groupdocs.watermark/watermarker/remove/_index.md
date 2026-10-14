---
title: remove method
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Removes a watermark from the document."
type: docs
url: /python-net/groupdocs.watermark/watermarker/remove/
is_root: false
weight: 1100
---


## remove {#possible_watermark}

Removes a watermark from the document.

Learn more about removing watermarks: Removing found watermarks.

```python
def remove(self, possible_watermark):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| possible_watermark | `PossibleWatermark` | The watermark to remove. |

### Example

```python
from groupdocs.watermark import Watermarker

def remove_first_watermark():
    with Watermarker("./document.pdf") as watermarker:
        watermarks = watermarker.search()
        if watermarks:
            watermarker.remove(watermarks[0])
        watermarker.save("./output.pdf")
```

## remove {#possible_watermarks}

Removes all watermarks in the collection from the document.

Learn more about removing watermarks in the GroupDocs documentation.

```python
def remove(self, possible_watermarks):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| possible_watermarks | `PossibleWatermarkCollection` | The collection of watermarks to remove. |

### Example

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def remove_watermark():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search()
        # Remove in reverse order to keep indexes valid
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.pdf")
```

### See Also
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
