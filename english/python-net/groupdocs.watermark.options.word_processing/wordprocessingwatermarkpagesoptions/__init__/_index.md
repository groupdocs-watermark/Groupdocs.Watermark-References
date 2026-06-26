---
title: __init__ constructor
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Initializes a new instance of the WordProcessingWatermarkPagesOptions class."
type: docs
url: /python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new instance of the WordProcessingWatermarkPagesOptions class.

```python
def __init__(self):
    ...
```

### Example

```python
import groupdocs.watermark.options.wordprocessing as gwo_wp

# Create options for applying a watermark to specific pages
options = gwo_wp.WordProcessingWatermarkPagesOptions()
options.page_numbers = [1, 3]  # target pages 1 and 3
```

### See Also
* class [`WordProcessingWatermarkPagesOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/)
