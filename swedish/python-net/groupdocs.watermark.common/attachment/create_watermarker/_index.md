---
title: "create_watermarker-metod"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Läser in ett innehåll från den bifogade filen."
type: docs
url: /sv/python-net/groupdocs.watermark.common/attachment/create_watermarker/
is_root: false
weight: 1010
---


## create_watermarker

Läser in ett innehåll från den bifogade filen.

```python
def create_watermarker(self):
    ...
```

**Returns:** The instance of appropriate descendant of `Content` class.

### Exempel

```python
    import groupdocs.watermark as gw
    import groupdocs.watermark.contents.pdf as gwc_pdf
    import groupdocs.watermark.watermarks as gww

    watermark = gww.TextWatermark("This is WaterMark on Attachment", gww.Font("Arial", 19.0))

    with gw.Watermarker("document.pdf") as watermarker:
        pdf_content = watermarker.get_content()
        for attachment in pdf_content.attachments:
            with attachment.create_watermarker() as attached:
                attached.add(watermark)
                attached.save()
    ```

## create_watermarker {#load_options}

Läser in ett innehåll från den bifogade filen med de angivna inläsningsalternativen.

```python
def create_watermarker(self, load_options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| load_options | `LoadOptions` | Ytterligare alternativ att använda när bilagans innehåll laddas. |

**Returns:** Content: The instance of appropriate descendant of `Content` class.

### Exempel

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.pdf import PdfLoadOptions
import groupdocs.watermark.contents.pdf as gwc_pdf
import groupdocs.watermark.watermarks as gww
from groupdocs.watermark.common import FileType

watermark = gww.TextWatermark("This is WaterMark on Attachment", gww.Font("Arial", 19.0))

load_options = PdfLoadOptions()
with gw.Watermarker("document.pdf", load_options) as watermarker:
    pdf_content = watermarker.get_content()
    for attachment in pdf_content.attachments:
        info = attachment.get_document_info()
        if info.file_type != FileType.UNKNOWN and not info.is_encrypted:
            with attachment.create_watermarker() as attached:
                attached.add(watermark)
                attached.save()
    watermarker.save("output.pdf")
```

## create_watermarker {#load_options-watermarker_settings}

Läser in ett innehåll från den bifogade filen med de angivna inläsningsalternativen och inställningarna.

```python
def create_watermarker(self, load_options, watermarker_settings):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| load_options | `LoadOptions` | Ytterligare alternativ att använda när bilagans innehåll laddas. |
| watermarker_settings | `WatermarkerSettings` | Ytterligare inställningar att använda när du arbetar med ett inläst dokument. |

**Returns:** The instance of appropriate descendant of `Content` class.

### Exempel

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.pdf as gwc_pdf
import groupdocs.watermark.watermarks as gww

watermark = gww.TextWatermark("Sample watermark", gww.Font("Arial", 19.0))

with gw.Watermarker("document.pdf") as watermarker:
    pdf_content = watermarker.get_content()
    for attachment in pdf_content.attachments:
        with attachment.create_watermarker() as attached:
            attached.add(watermark)
            attached.save()
    watermarker.save("output.pdf")
```

### Se även
* class [`Attachment`](/watermark/python-net/groupdocs.watermark.common/attachment/)
