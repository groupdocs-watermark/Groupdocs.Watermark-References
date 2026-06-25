---
title: WordProcessingLoadOptions class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/
is_root: false
weight: 40
---


## WordProcessingLoadOptions class

Represents document loading options for a Word document.

The WordProcessingLoadOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/__init__/) | Initializes a new instance of the [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/) class. |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/__init__/#password) | Initializes a new instance of [`gw.WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/) with a specified password. |

### Properties
| Property | Description |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | The file type, indicating its format (e.g., docx, pdf, xlsx, etc.). (inherited from [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | The format family of the document, indicating its type (e.g., Image, Pdf, Spreadsheet, etc.). (inherited from [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | The password for opening an encrypted document. (inherited from [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Fields
| Field | Description |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/default/) | Gets the default value for the class. |

### Example

```python
import groupdocs.watermark as gw

load_options = gw.WordProcessingLoadOptions()
```

### See Also
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
