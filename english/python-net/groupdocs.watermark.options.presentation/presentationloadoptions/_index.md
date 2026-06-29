---
title: PresentationLoadOptions class
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Represents document loading options for a Presentation document."
type: docs
url: /python-net/groupdocs.watermark.options.presentation/presentationloadoptions/
is_root: false
weight: 30
---


## PresentationLoadOptions class

Represents document loading options for a Presentation document.

The PresentationLoadOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/__init__/) | Initializes a new instance of the [`PresentationLoadOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/) class. |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/__init__/#password) | Initializes a new instance of the PresentationLoadOptions class with a specified password. |

### Properties
| Property | Description |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | The file type, indicating its format (e.g., docx, pdf, xlsx, etc.). (inherited from [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | The format family of the document, indicating its type (e.g., Image, Pdf, Spreadsheet, etc.). (inherited from [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | The password for opening an encrypted document. (inherited from [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Fields
| Field | Description |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/default/) | Gets the default value for the class. |

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.presentation as gwc_ppt

load_options = gw.PresentationLoadOptions()
with gw.Watermarker("presentation.pptx", load_options) as watermarker:
    content = watermarker.get_content(gwc_ppt.PresentationContent)
    print(content.slide_width)
    print(content.slide_height)
```

### See Also
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
