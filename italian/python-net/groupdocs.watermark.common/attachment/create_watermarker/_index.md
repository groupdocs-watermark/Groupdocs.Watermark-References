---
title: "metodo create_watermarker"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Carica un contenuto dal file allegato."
type: docs
url: /it/python-net/groupdocs.watermark.common/attachment/create_watermarker/
is_root: false
weight: 1010
---


## create_watermarker

Carica un contenuto dal file allegato.

```python
def create_watermarker(self):
    ...
```

**Returns:** The instance of appropriate descendant of `Content` class.

### Esempio

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

Carica un contenuto dal file allegato con le opzioni di caricamento specificate.

```python
def create_watermarker(self, load_options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| load_options | `LoadOptions` | Opzioni aggiuntive da utilizzare durante il caricamento del contenuto di un allegato. |

**Returns:** Content: The instance of appropriate descendant of `Content` class.

### Esempio

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

Carica un contenuto dal file allegato con le opzioni di caricamento e le impostazioni specificate.

```python
def create_watermarker(self, load_options, watermarker_settings):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| load_options | `LoadOptions` | Opzioni aggiuntive da utilizzare durante il caricamento del contenuto di un allegato. |
| watermarker_settings | `WatermarkerSettings` | Impostazioni aggiuntive da utilizzare quando si lavora con il documento caricato. |

**Returns:** The instance of appropriate descendant of `Content` class.

### Esempio

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

### Vedi anche
* class [`Attachment`](/watermark/python-net/groupdocs.watermark.common/attachment/)
