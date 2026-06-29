---
title: WatermarkerSettings class
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Defines settings for customizing Watermarker behaviour."
type: docs
url: /python-net/groupdocs.watermark/watermarkersettings/
is_root: false
weight: 190
---


## WatermarkerSettings class

Defines settings for customizing Watermarker behaviour.

The WatermarkerSettings type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarkersettings/__init__/) | Initializes a new instance of [`WatermarkerSettings`](/watermark/python-net/groupdocs.watermark/watermarkersettings/). |

### Properties
| Property | Description |
| :- | :- |
| [logger](/watermark/python-net/groupdocs.watermark/watermarkersettings/logger/) | The logger used for logging events and errors during watermarking. |
| [searchable_objects](/watermark/python-net/groupdocs.watermark/watermarkersettings/searchable_objects/) | The searchable objects that are included in a watermark search. |

### Fields
| Field | Description |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark/watermarkersettings/default/) | Gets the default value for the class. |

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.search as gws

settings = gw.WatermarkerSettings()
settings.searchable_objects = gws.SearchableObjects(
    word_processing_searchable_objects=gws.WordProcessingSearchableObjects.HYPERLINKS
    | gws.WordProcessingSearchableObjects.TEXT,
    spreadsheet_searchable_objects=gws.SpreadsheetSearchableObjects.HEADERS_FOOTERS,
    presentation_searchable_objects=gws.PresentationSearchableObjects.SLIDES_BACKGROUNDS
    | gws.PresentationSearchableObjects.SHAPES,
    diagram_searchable_objects=gws.DiagramSearchableObjects.NONE,
    pdf_searchable_objects=gws.PdfSearchableObjects.ALL,
)
```

### Guides
Task guides that use `WatermarkerSettings`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### See Also
* module [`groupdocs.watermark`](/watermark/python-net/groupdocs.watermark/)
