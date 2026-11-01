---
title: "__init__ konstruktor"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Initierar en ny instans av klassen WatermarkResult."
type: docs
url: /sv/python-net/groupdocs.watermark.internal/watermarkresult/__init__/
is_root: false
weight: 10
---


## __init__

Initierar en ny instans av [`WatermarkResult`](/watermark/python-net/groupdocs.watermark.internal/watermarkresult/) klassen.

```python
def __init__(self):
    ...
```

## __init__ {#source_document_size-processing_time-final_document_size-number_watermarks_applied}

Initierar en ny WatermarkResult-instans med specifika värden.

```python
def __init__(self, source_document_size, processing_time, final_document_size, number_watermarks_applied):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_document_size | `int` | Storleken på källdokumentet i byte. |
| processing_time | `timedelta` | Bearbetningstiden i millisekunder. |
| final_document_size | `int` | Storleken på det slutgiltiga bearbetade dokumentet i byte. |
| number_watermarks_applied | `int` | Det totala antalet vattenmärken som applicerats på dokumentet. |

### Se även
* class [`WatermarkResult`](/watermark/python-net/groupdocs.watermark.internal/watermarkresult/)
