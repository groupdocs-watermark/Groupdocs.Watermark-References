---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "ينشئ مثيلاً جديداً من فئة WordProcessingWatermarkPagesOptions."
type: docs
url: /ar/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/__init__/
is_root: false
weight: 10
---


## __init__

ينشئ مثيلاً جديداً من فئة WordProcessingWatermarkPagesOptions.

```python
def __init__(self):
    ...
```

### مثال

```python
import groupdocs.watermark.options.word_processing as gwo_wp

# إنشاء خيارات لتطبيق العلامة المائية على صفحات محددة
options = gwo_wp.WordProcessingWatermarkPagesOptions()
options.page_numbers = [1, 3]  # target pages 1 and 3
```

### انظر أيضًا
* class [`WordProcessingWatermarkPagesOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/)
