---
title: "__init__ конструктор"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Инициализирует новый экземпляр класса WordProcessingWatermarkPagesOptions."
type: docs
url: /ru/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует новый экземпляр класса WordProcessingWatermarkPagesOptions.

```python
def __init__(self):
    ...
```

### Пример

```python
import groupdocs.watermark.options.word_processing as gwo_wp

# Создать параметры для применения водяного знака к определённым страницам
options = gwo_wp.WordProcessingWatermarkPagesOptions()
options.page_numbers = [1, 3]  # target pages 1 and 3
```

### См. также
* class [`WordProcessingWatermarkPagesOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/)
