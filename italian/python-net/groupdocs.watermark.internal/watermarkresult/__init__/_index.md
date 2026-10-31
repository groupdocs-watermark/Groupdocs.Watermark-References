---
title: "__init__ costruttore"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Inizializza una nuova istanza della classe WatermarkResult."
type: docs
url: /it/python-net/groupdocs.watermark.internal/watermarkresult/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una nuova istanza della classe [`WatermarkResult`](/watermark/python-net/groupdocs.watermark.internal/watermarkresult/).

```python
def __init__(self):
    ...
```

## __init__ {#source_document_size-processing_time-final_document_size-number_watermarks_applied}

Inizializza una nuova istanza di WatermarkResult con valori specifici.

```python
def __init__(self, source_document_size, processing_time, final_document_size, number_watermarks_applied):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_document_size | `int` | La dimensione del documento sorgente in byte. |
| processing_time | `timedelta` | Il tempo di elaborazione in millisecondi. |
| final_document_size | `int` | La dimensione del documento finale elaborato in byte. |
| number_watermarks_applied | `int` | Il numero totale di filigrane applicate al documento. |

### Vedi anche
* class [`WatermarkResult`](/watermark/python-net/groupdocs.watermark.internal/watermarkresult/)
