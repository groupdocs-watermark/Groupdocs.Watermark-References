---
title: "__init__ konstruktor"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Initierar en ny instans av klassen EmailPreviewOptions och får utdataflödet att stängas."
type: docs
url: /sv/python-net/groupdocs.watermark.options.email/emailpreviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Initierar en ny instans av klassen [`EmailPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.email/emailpreviewoptions/) som stänger utdataströmmen.

```python
def __init__(self, create_page_stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Skapar ett flöde för en specifik sidförhandsgranskning. |

## __init__ {#create_page_stream-release_page_stream}

Initierar en ny instans av EmailPreviewOptions‑klassen som returnerar utdataströmmen till klienten för vidare användning.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Skapar ett flöde för en specifik sidförhandsgranskning. |
| release_page_stream | `ReleasePageStream` | Meddelar att genereringen av sidförhandsgranskning är klar och hämtar utdataflödet. |

### Se även
* class [`EmailPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.email/emailpreviewoptions/)
