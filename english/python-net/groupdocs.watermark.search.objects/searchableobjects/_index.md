---
title: SearchableObjects class
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Specifies document objects that are to be included in a watermark search."
type: docs
url: /python-net/groupdocs.watermark.search.objects/searchableobjects/
is_root: false
weight: 50
---


## SearchableObjects class

Specifies document objects that are to be included in a watermark search.

Learn more:
- [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

The SearchableObjects type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/__init__/) | Initializes a new instance of the [`SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) class. |

### Properties
| Property | Description |
| :- | :- |
| [diagram_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/diagram_searchable_objects/) | The objects inside a Visio document that are to be included in a watermark search. |
| [email_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/email_searchable_objects/) | The objects inside an email message that are to be included in a watermark search. |
| [pdf_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/pdf_searchable_objects/) | The objects inside a PDF document that are to be included in a watermark search. |
| [presentation_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/presentation_searchable_objects/) | The objects inside a PowerPoint document that are to be included in a watermark search. |
| [spreadsheet_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/spreadsheet_searchable_objects/) | The objects inside an Excel document that are to be included in a watermark search. |
| [word_processing_searchable_objects](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/word_processing_searchable_objects/) | The objects inside a Word document that are to be included in a watermark search. |

### Example

```python
import os
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

files = ["document.docx", "spreadsheet.xlsx", "presentation.pptx", "diagram.vsdx", "document.pdf"]
for file in files:
    with gw.Watermarker(file, settings) as watermarker:
        possible = watermarker.search()
        print(f"In {os.path.basename(file)} found {possible.count} possible watermark(s).")
```

### Guides
Task guides that use `SearchableObjects`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### See Also
* module [`groupdocs.watermark.search.objects`](/watermark/python-net/groupdocs.watermark.search.objects/)
