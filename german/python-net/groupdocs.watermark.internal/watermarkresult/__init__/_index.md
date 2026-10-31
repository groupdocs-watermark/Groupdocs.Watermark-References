---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz der Klasse WatermarkResult."
type: docs
url: /de/python-net/groupdocs.watermark.internal/watermarkresult/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine neue Instanz der [`WatermarkResult`](/watermark/python-net/groupdocs.watermark.internal/watermarkresult/) Klasse.

```python
def __init__(self):
    ...
```

## __init__ {#source_document_size-processing_time-final_document_size-number_watermarks_applied}

Initialisiert eine neue WatermarkResult-Instanz mit spezifischen Werten.

```python
def __init__(self, source_document_size, processing_time, final_document_size, number_watermarks_applied):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_document_size | `int` | Die Größe des Quelldokuments in Bytes. |
| processing_time | `timedelta` | Die Verarbeitungszeit in Millisekunden. |
| final_document_size | `int` | Die Größe des final verarbeiteten Dokuments in Bytes. |
| number_watermarks_applied | `int` | Die Gesamtzahl der auf das Dokument angewendeten Wasserzeichen. |

### Siehe auch
* class [`WatermarkResult`](/watermark/python-net/groupdocs.watermark.internal/watermarkresult/)
