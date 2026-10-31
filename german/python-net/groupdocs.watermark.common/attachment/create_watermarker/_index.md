---
title: "create_watermarker-Methode"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Lädt einen Inhalt aus der angehängten Datei."
type: docs
url: /de/python-net/groupdocs.watermark.common/attachment/create_watermarker/
is_root: false
weight: 1010
---


## create_watermarker

Lädt einen Inhalt aus der angehängten Datei.

```python
def create_watermarker(self):
    ...
```

**Returns:** The instance of appropriate descendant of `Content` class.

### Beispiel

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

Lädt einen Inhalt aus der angehängten Datei mit den angegebenen Ladeoptionen.

```python
def create_watermarker(self, load_options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| load_options | `LoadOptions` | Zusätzliche Optionen, die beim Laden von Anhangsinhalten verwendet werden. |

**Returns:** Content: The instance of appropriate descendant of `Content` class.

### Beispiel

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

Lädt einen Inhalt aus der angehängten Datei mit den angegebenen Ladeoptionen und Einstellungen.

```python
def create_watermarker(self, load_options, watermarker_settings):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| load_options | `LoadOptions` | Zusätzliche Optionen, die beim Laden von Anhangsinhalten verwendet werden. |
| watermarker_settings | `WatermarkerSettings` | Zusätzliche Einstellungen, die bei der Arbeit mit geladenen Dokumenten verwendet werden. |

**Returns:** The instance of appropriate descendant of `Content` class.

### Beispiel

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

### Siehe auch
* class [`Attachment`](/watermark/python-net/groupdocs.watermark.common/attachment/)
