---
title: DiagramLoadOptions class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.options.diagram/diagramloadoptions/
is_root: false
weight: 10
---


## DiagramLoadOptions class

Represents document loading options for a Visio document.

The DiagramLoadOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/__init__/) | Initializes a new instance of the DiagramLoadOptions class. |
| [__init__](/watermark/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/__init__/#password) | Initializes a new instance of the DiagramLoadOptions class with a specified password. |

### Properties
| Property | Description |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | The file type, indicating its format (e.g., docx, pdf, xlsx, etc.). (inherited from [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | The format family of the document, indicating its type (e.g., Image, Pdf, Spreadsheet, etc.). (inherited from [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | The password for opening an encrypted document. (inherited from [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Fields
| Field | Description |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.diagram/diagramloadoptions/default/) | Gets the default value for the class. |

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.diagram as gwc_vsdx

load_options = gw.DiagramLoadOptions()
with gw.Watermarker("diagram.vsdx", load_options) as watermarker:
    content = watermarker.get_content(gwc_vsdx.DiagramContent)
    # manipulate shapes, e.g., replace text or images
    watermarker.save("diagram.vsdx")
```

### See Also
* module [`groupdocs.watermark.options.diagram`](/watermark/python-net/groupdocs.watermark.options.diagram/)
