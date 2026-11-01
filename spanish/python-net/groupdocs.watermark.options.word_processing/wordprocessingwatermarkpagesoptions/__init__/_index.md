---
title: "__init__ constructor"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Inicializa una nueva instancia de la clase WordProcessingWatermarkPagesOptions."
type: docs
url: /es/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una nueva instancia de la clase WordProcessingWatermarkPagesOptions.

```python
def __init__(self):
    ...
```

### Ejemplo

```python
import groupdocs.watermark.options.word_processing as gwo_wp

# Crear opciones para aplicar una marca de agua a páginas específicas
options = gwo_wp.WordProcessingWatermarkPagesOptions()
options.page_numbers = [1, 3]  # target pages 1 and 3
```

### Ver también
* class [`WordProcessingWatermarkPagesOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/)
