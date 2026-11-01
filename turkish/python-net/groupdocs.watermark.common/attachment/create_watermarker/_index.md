---
title: "create_watermarker yöntemi"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Ekli dosyadan içerik yükler."
type: docs
url: /tr/python-net/groupdocs.watermark.common/attachment/create_watermarker/
is_root: false
weight: 1010
---


## create_watermarker

Ekli dosyadan içerik yükler.

```python
def create_watermarker(self):
    ...
```

**Returns:** The instance of appropriate descendant of `Content` class.

### Örnek

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

Ekli dosyadan belirtilen yükleme seçenekleriyle içerik yükler.

```python
def create_watermarker(self, load_options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| load_options | `LoadOptions` | Ek dosya içeriği yüklerken kullanılacak ek seçenekler. |

**Returns:** Content: The instance of appropriate descendant of `Content` class.

### Örnek

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

Ekli dosyadan belirtilen yükleme seçenekleri ve ayarlarla içerik yükler.

```python
def create_watermarker(self, load_options, watermarker_settings):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| load_options | `LoadOptions` | Ek dosya içeriği yüklerken kullanılacak ek seçenekler. |
| watermarker_settings | `WatermarkerSettings` | Yüklenmiş belgeyle çalışırken kullanılacak ek ayarlar. |

**Returns:** The instance of appropriate descendant of `Content` class.

### Örnek

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

### Ayrıca Bakınız
* class [`Attachment`](/watermark/python-net/groupdocs.watermark.common/attachment/)
