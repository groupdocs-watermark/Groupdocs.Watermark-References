---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz der Klasse EmailPreviewOptions, wodurch der Ausgabestream geschlossen wird."
type: docs
url: /de/python-net/groupdocs.watermark.options.email/emailpreviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Initialisiert eine neue Instanz der [`EmailPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.email/emailpreviewoptions/) Klasse, wodurch der Ausgabestream geschlossen wird.

```python
def __init__(self, create_page_stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Erstellt einen Stream für eine bestimmte Seitenvorschau. |

## __init__ {#create_page_stream-release_page_stream}

Initialisiert eine neue Instanz der EmailPreviewOptions Klasse, wodurch der Ausgabestream dem Client zur weiteren Verwendung zurückgegeben wird.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Erstellt einen Stream für eine bestimmte Seitenvorschau. |
| release_page_stream | `ReleasePageStream` | Benachrichtigt, dass die Erzeugung der Seitenvorschau abgeschlossen ist, und holt den Ausgabestream. |

### Siehe auch
* class [`EmailPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.email/emailpreviewoptions/)
