---
title: "__init__ konstruktor"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Initierar en ny instans av PresentationPreviewOptions‑klassen vilket får utdataströmmen att stängas."
type: docs
url: /sv/python-net/groupdocs.watermark.options.presentation/presentationpreviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Initierar en ny instans av PresentationPreviewOptions‑klassen vilket får utdataströmmen att stängas.

```python
def __init__(self, create_page_stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Skapar ett flöde för en specifik sidförhandsgranskning. |

## __init__ {#create_page_stream-release_page_stream}

Initierar en ny instans av [`PresentationPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationpreviewoptions/) vilket får att utdataströmmen returneras till klienten för vidare användning.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Skapar ett flöde för en specifik sidförhandsgranskning. |
| release_page_stream | `ReleasePageStream` | Meddelar att genereringen av sidförhandsgranskning är klar och hämtar utdataflödet. |

### Se även
* class [`PresentationPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationpreviewoptions/)
