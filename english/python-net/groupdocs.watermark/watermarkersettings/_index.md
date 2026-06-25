---
title: WatermarkerSettings class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
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
| [logger](/watermark/python-net/groupdocs.watermark/watermarkersettings/logger/) | The logger used for logging events and errors during watermarking. Must be an instance implementing [`ILogger`](/watermark/python-net/groupdocs.watermark.options/ilogger/). |
| [searchable_objects](/watermark/python-net/groupdocs.watermark/watermarkersettings/searchable_objects/) | The [`SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) that are to be included in a watermark search. |

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
    word_processing_searchable_objects=gws.WordProcessingSearchableObjects.HYPERLINKS | gws.WordProcessingSearchableObjects.TEXT,
    spreadsheet_searchable_objects=gws.SpreadsheetSearchableObjects.HEADERS_FOOTERS,
    presentation_searchable_objects=gws.PresentationSearchableObjects.SLIDES_BACKGROUNDS | gws.PresentationSearchableObjects.SHAPES,
    diagram_searchable_objects=gws.DiagramSearchableObjects.NONE,
    pdf_searchable_objects=gws.PdfSearchableObjects.ALL,
)

with gw.Watermarker("document.docx", settings) as watermarker:
    possible = watermarker.search()
    print(f"Found {possible.count} possible watermark(s).")
```

### See Also
* module [`groupdocs.watermark`](/watermark/python-net/groupdocs.watermark/)
