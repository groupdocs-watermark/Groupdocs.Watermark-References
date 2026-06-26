---
title: create_watermarker method
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Loads a content from the attached file."
type: docs
url: /python-net/groupdocs.watermark.common/attachment/create_watermarker/
is_root: false
weight: 1010
---


## create_watermarker

Loads a content from the attached file.

```python
def create_watermarker(self):
    ...
```

**Returns:** An instance of the appropriate descendant of `Content`.

### Example

```python
    import groupdocs.watermark as gw
    import groupdocs.watermark.contents.pdf as gwc_pdf
    import groupdocs.watermark.watermarks as gww

    watermark = gww.TextWatermark("This is WaterMark on Attachment", gww.Font("Arial", 19.0))

    with gw.Watermarker("document.pdf") as watermarker:
        pdf_content = watermarker.get_content(gwc_pdf.PdfContent)
        for attachment in pdf_content.attachments:
            with attachment.create_watermarker() as attached:
                attached.add(watermark)
                attached.save()
    ```

## create_watermarker {#load_options}

Loads a content from the attached file with the specified load options.

```python
def create_watermarker(self, load_options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| load_options | `LoadOptions` | Additional options to use when loading an attachment content. |

**Returns:** Content: The instance of appropriate descendant of `Content` class.

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

## create_watermarker {#load_options-watermarker_settings}

Loads a content from the attached file with the specified load options and settings.

```python
def create_watermarker(self, load_options, watermarker_settings):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| load_options | `LoadOptions` | Additional options to use when loading an attachment content. |
| watermarker_settings | `WatermarkerSettings` | Additional settings to use when working with loaded document. |

**Returns:** An instance of a subclass of `Content` representing the loaded attachment content.

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.pdf as gwc_pdf
import groupdocs.watermark.watermarks as gww

watermark = gww.TextWatermark("Sample watermark", gww.Font("Arial", 19.0))

with gw.Watermarker("document.pdf") as watermarker:
    pdf_content = watermarker.get_content(gwc_pdf.PdfContent)
    for attachment in pdf_content.attachments:
        with attachment.create_watermarker() as attached:
            attached.add(watermark)
            attached.save()
    watermarker.save("document.pdf")
```

### See Also
* class [`Attachment`](/watermark/python-net/groupdocs.watermark.common/attachment/)
