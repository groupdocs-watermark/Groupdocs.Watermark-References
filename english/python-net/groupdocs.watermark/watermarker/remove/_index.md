---
title: remove method
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
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

**Returns:** None.

### Example

```python
import groupdocs.watermark as gw

with gw.Watermarker("document.pdf") as watermarker:
    possible = watermarker.search()
    if possible.count > 0:
        watermarker.remove(possible[0])
    watermarker.save("document.pdf")
```

## remove {#possible_watermarks}

Removes all watermarks in the collection from the document.

Learn more about removing watermarks at the GroupDocs documentation: https://docs.groupdocs.com/display/watermarknet/Removing+found+watermarks.

```python
def remove(self, possible_watermarks):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| possible_watermarks | `PossibleWatermarkCollection` | The collection of watermarks to remove. |

**Returns:** None.

### Example

```python
import groupdocs.watermark as gw

with gw.Watermarker("input.doc") as watermarker:
    # Find watermarks matching specific criteria
    watermarks = watermarker.search()
    # Remove all found watermarks from the document
    watermarker.remove(watermarks)
    watermarker.save("output.doc")
```

### See Also
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
