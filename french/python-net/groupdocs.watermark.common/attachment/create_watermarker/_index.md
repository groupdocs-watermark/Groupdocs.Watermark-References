---
title: "create_watermarker méthode"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Charge un contenu depuis le fichier joint."
type: docs
url: /fr/python-net/groupdocs.watermark.common/attachment/create_watermarker/
is_root: false
weight: 1010
---


## create_watermarker

Charge un contenu depuis le fichier joint.

```python
def create_watermarker(self):
    ...
```

**Returns:** The instance of appropriate descendant of `Content` class.

### Exemple

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

Charge un contenu depuis le fichier joint avec les options de chargement spécifiées.

```python
def create_watermarker(self, load_options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| load_options | `LoadOptions` | Options supplémentaires à utiliser lors du chargement du contenu d'une pièce jointe. |

**Returns:** Content: The instance of appropriate descendant of `Content` class.

### Exemple

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

Charge un contenu depuis le fichier joint avec les options de chargement et les paramètres spécifiés.

```python
def create_watermarker(self, load_options, watermarker_settings):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| load_options | `LoadOptions` | Options supplémentaires à utiliser lors du chargement du contenu d'une pièce jointe. |
| watermarker_settings | `WatermarkerSettings` | Paramètres supplémentaires à utiliser lors du travail avec le document chargé. |

**Returns:** The instance of appropriate descendant of `Content` class.

### Exemple

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

### Voir aussi
* class [`Attachment`](/watermark/python-net/groupdocs.watermark.common/attachment/)
