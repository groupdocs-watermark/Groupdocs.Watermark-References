---
title: "__init__ yapıcı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "WordProcessingWatermarkPagesOptions sınıfının yeni bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/__init__/
is_root: false
weight: 10
---


## __init__

WordProcessingWatermarkPagesOptions sınıfının yeni bir örneğini başlatır.

```python
def __init__(self):
    ...
```

### Örnek

```python
import groupdocs.watermark.options.word_processing as gwo_wp

# Belirli sayfalara filigran uygulamak için seçenekler oluştur
options = gwo_wp.WordProcessingWatermarkPagesOptions()
options.page_numbers = [1, 3]  # target pages 1 and 3
```

### Ayrıca Bakınız
* class [`WordProcessingWatermarkPagesOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/)
