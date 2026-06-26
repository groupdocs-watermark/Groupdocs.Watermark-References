---
title: Attachment class
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Represents a file attached to a document."
type: docs
url: /python-net/groupdocs.watermark.common/attachment/
is_root: false
weight: 10
---


## Attachment class

Represents a file attached to a document.

- Email attachments: https://docs.groupdocs.com/display/watermarknet/Email+attachments
- Attachments in PDF document: https://docs.groupdocs.com/display/watermarknet/Attachments+in+PDF+document
- Working with spreadsheet document attachments: https://docs.groupdocs.com/display/watermarknet/Working+with+spreadsheet+document+attachments

The Attachment type exposes the following members:

### Methods
| Method | Description |
| :- | :- |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/) | Loads a content from the attached file. |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/#load_options) | Loads a content from the attached file with the specified load options. |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/#load_options-watermarker_settings) | Loads a content from the attached file with the specified load options and settings. |
| [create_watermarker_load_options](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker_load_options/) |  |
| [get_document_info](/watermark/python-net/groupdocs.watermark.common/attachment/get_document_info/) | Retrieves information about the document stored in the attached file. |

### Properties
| Property | Description |
| :- | :- |
| [content](/watermark/python-net/groupdocs.watermark.common/attachment/content/) | The attached file content. |

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.pdf as gwc_pdf
import groupdocs.watermark.watermarks as gww
from groupdocs.watermark.common import FileType

watermark = gww.TextWatermark("This is WaterMark on Attachment", gww.Font("Arial", 19.0))
load_options = gw.PdfLoadOptions()
with gw.Watermarker("document.pdf", load_options) as watermarker:
    pdf_content = watermarker.get_content(gwc_pdf.PdfContent)
    for attachment in pdf_content.attachments:
        info = attachment.get_document_info()
        if info.file_type != FileType.UNKNOWN and not info.is_encrypted:
            with attachment.create_watermarker() as attached:
                attached.add(watermark)
                attached.save()
    watermarker.save("document.pdf")
```

### See Also
* module [`groupdocs.watermark.common`](/watermark/python-net/groupdocs.watermark.common/)
