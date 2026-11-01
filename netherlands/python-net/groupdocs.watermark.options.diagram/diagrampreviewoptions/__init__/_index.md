---
title: "__init__ constructor"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Initialiseert een nieuw exemplaar van de DiagramPreviewOptions-klasse waardoor de uitvoerstroom wordt gesloten."
type: docs
url: /nl/python-net/groupdocs.watermark.options.diagram/diagrampreviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Initialiseert een nieuw exemplaar van de [`DiagramPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampreviewoptions/) klasse waardoor de uitvoerstroom wordt gesloten.

```python
def __init__(self, create_page_stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Maakt een stroom aan voor een specifieke paginavoorbeeld. |

## __init__ {#create_page_stream-release_page_stream}

Initialiseert een nieuw exemplaar van [`DiagramPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampreviewoptions/) waardoor de uitvoerstroom wordt teruggegeven aan de client voor verder gebruik.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Maakt een stroom aan voor een specifieke paginavoorbeeld. |
| release_page_stream | `ReleasePageStream` | Meldt dat de generatie van het paginavoorbeeld voltooid is en haalt de uitvoerstroom op. |

### Zie ook
* class [`DiagramPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampreviewoptions/)
