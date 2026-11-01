---
title: "create_watermarker methode"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Laadt een inhoud van het bijgevoegde bestand."
type: docs
url: /nl/python-net/groupdocs.watermark.common/attachment/create_watermarker/
is_root: false
weight: 1010
---


## create_watermarker

Laadt een inhoud van het bijgevoegde bestand.

```python
def create_watermarker(self):
    ...
```

**Returns:** The instance of appropriate descendant of `Content` class.

### Voorbeeld

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

Laadt een inhoud van het bijgevoegde bestand met de opgegeven laadopties.

```python
def create_watermarker(self, load_options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| load_options | `LoadOptions` | Aanvullende opties om te gebruiken bij het laden van een bijlage-inhoud. |

**Returns:** Content: The instance of appropriate descendant of `Content` class.

### Voorbeeld

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

Laadt een inhoud van het bijgevoegde bestand met de opgegeven laadopties en instellingen.

```python
def create_watermarker(self, load_options, watermarker_settings):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| load_options | `LoadOptions` | Aanvullende opties om te gebruiken bij het laden van een bijlage-inhoud. |
| watermarker_settings | `WatermarkerSettings` | Aanvullende instellingen om te gebruiken bij het werken met een geladen document. |

**Returns:** The instance of appropriate descendant of `Content` class.

### Voorbeeld

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

### Zie ook
* class [`Attachment`](/watermark/python-net/groupdocs.watermark.common/attachment/)
