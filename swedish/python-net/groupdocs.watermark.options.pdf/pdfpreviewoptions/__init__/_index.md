---
title: "__init__ konstruktor"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Initierar en ny instans av klassen PdfPreviewOptions och stänger utdataströmmen."
type: docs
url: /sv/python-net/groupdocs.watermark.options.pdf/pdfpreviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Initierar en ny instans av [`PdfPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfpreviewoptions/) klassen som orsakar att utdataströmmen stängs.

```python
def __init__(self, create_page_stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Skapar ett flöde för en specifik sidförhandsgranskning. |

## __init__ {#create_page_stream-release_page_stream}

Initierar en ny PdfPreviewOptions-instans som returnerar utdataströmmen till klienten för vidare användning.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Skapar ett flöde för en specifik sidförhandsgranskning. |
| release_page_stream | `ReleasePageStream` | Meddelar att genereringen av sidförhandsgranskning är klar och hämtar utdataflödet. |

### Se även
* class [`PdfPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfpreviewoptions/)
