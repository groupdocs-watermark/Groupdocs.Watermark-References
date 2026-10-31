---
title: "__init__ constructeur"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Initialise une nouvelle instance de la classe WatermarkResult."
type: docs
url: /fr/python-net/groupdocs.watermark.internal/watermarkresult/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une nouvelle instance de la classe [`WatermarkResult`](/watermark/python-net/groupdocs.watermark.internal/watermarkresult/).

```python
def __init__(self):
    ...
```

## __init__ {#source_document_size-processing_time-final_document_size-number_watermarks_applied}

Initialise une nouvelle instance de WatermarkResult avec des valeurs spécifiques.

```python
def __init__(self, source_document_size, processing_time, final_document_size, number_watermarks_applied):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| source_document_size | `int` | La taille du document source en octets. |
| processing_time | `timedelta` | Le temps de traitement en millisecondes. |
| final_document_size | `int` | La taille du document final traité en octets. |
| number_watermarks_applied | `int` | Le nombre total de filigranes appliqués au document. |

### Voir aussi
* class [`WatermarkResult`](/watermark/python-net/groupdocs.watermark.internal/watermarkresult/)
