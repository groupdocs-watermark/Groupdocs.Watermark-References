---
title: PdfLoadOptions class
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Represents document loading options for a PDF document."
type: docs
url: /python-net/groupdocs.watermark.options.pdf/pdfloadoptions/
is_root: false
weight: 30
---


## PdfLoadOptions class

Represents document loading options for a PDF document.

The PdfLoadOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/__init__/) | Initializes a new instance of the [`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/) class. |
| [__init__](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/__init__/#password) | Initializes a new instance of the [`PdfLoadOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/) class with a specified password. |

### Properties
| Property | Description |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | The file type, indicating its format (e.g., docx, pdf, xlsx, etc.). (inherited from [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | The format family of the document, indicating its type (e.g., Image, Pdf, Spreadsheet, etc.). (inherited from [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | The password for opening an encrypted document. (inherited from [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Fields
| Field | Description |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.pdf/pdfloadoptions/default/) | Gets the default value for the class. |

### Example

```python
import groupdocs.watermark as gw

# Create default PDF load options
load_options = gw.PdfLoadOptions()

# Use the options when opening a PDF with Watermarker
with gw.Watermarker("document.pdf", load_options) as watermarker:
    # perform watermark operations here
    pass
```

### See Also
* module [`groupdocs.watermark.options.pdf`](/watermark/python-net/groupdocs.watermark.options.pdf/)
