---
title: "__init__ constructor"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Initialiseert een nieuwe instantie van de WatermarkResult‑klasse."
type: docs
url: /nl/python-net/groupdocs.watermark.internal/watermarkresult/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een nieuw exemplaar van de [`WatermarkResult`](/watermark/python-net/groupdocs.watermark.internal/watermarkresult/) klasse.

```python
def __init__(self):
    ...
```

## __init__ {#source_document_size-processing_time-final_document_size-number_watermarks_applied}

Initialiseert een nieuw WatermarkResult‑exemplaar met specifieke waarden.

```python
def __init__(self, source_document_size, processing_time, final_document_size, number_watermarks_applied):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_document_size | `int` | De grootte van het brondocument in bytes. |
| processing_time | `timedelta` | De verwerkingstijd in milliseconden. |
| final_document_size | `int` | De grootte van het uiteindelijk verwerkte document in bytes. |
| number_watermarks_applied | `int` | Het totale aantal watermerken dat op het document is toegepast. |

### Zie ook
* class [`WatermarkResult`](/watermark/python-net/groupdocs.watermark.internal/watermarkresult/)
