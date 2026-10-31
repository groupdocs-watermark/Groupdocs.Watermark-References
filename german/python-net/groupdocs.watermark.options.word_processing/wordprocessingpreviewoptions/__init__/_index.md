---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz von WordProcessingPreviewOptions, die den Ausgabestream schließt."
type: docs
url: /de/python-net/groupdocs.watermark.options.word_processing/wordprocessingpreviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Initialisiert eine neue Instanz von WordProcessingPreviewOptions, die den Ausgabestream schließt.

```python
def __init__(self, create_page_stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Erstellt einen Stream für eine bestimmte Seitenvorschau. |

## __init__ {#create_page_stream-release_page_stream}

Initialisiert eine neue Instanz der Klasse WordProcessingPreviewOptions, die den Ausgabestream an den Client zurückgibt, um ihn weiter zu verwenden.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Erstellt einen Stream für eine bestimmte Seitenvorschau. |
| release_page_stream | `ReleasePageStream` | Benachrichtigt, dass die Erzeugung der Seitenvorschau abgeschlossen ist, und holt den Ausgabestream. |

### Siehe auch
* class [`WordProcessingPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingpreviewoptions/)
