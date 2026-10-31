---
title: "create_watermarker method"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Memuat konten dari file yang dilampirkan."
type: docs
url: /id/python-net/groupdocs.watermark.common/attachment/create_watermarker/
is_root: false
weight: 1010
---


## create_watermarker

Memuat konten dari file yang dilampirkan.

```python
def create_watermarker(self):
    ...
```

**Returns:** The instance of appropriate descendant of `Content` class.

### Contoh

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

Memuat konten dari file yang dilampirkan dengan opsi pemuatan yang ditentukan.

```python
def create_watermarker(self, load_options):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| load_options | `LoadOptions` | Opsi tambahan untuk digunakan saat memuat konten lampiran. |

**Returns:** Content: The instance of appropriate descendant of `Content` class.

### Contoh

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

Memuat konten dari file yang dilampirkan dengan opsi pemuatan dan pengaturan yang ditentukan.

```python
def create_watermarker(self, load_options, watermarker_settings):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| load_options | `LoadOptions` | Opsi tambahan untuk digunakan saat memuat konten lampiran. |
| watermarker_settings | `WatermarkerSettings` | Pengaturan tambahan untuk digunakan saat bekerja dengan dokumen yang dimuat. |

**Returns:** The instance of appropriate descendant of `Content` class.

### Contoh

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

### Lihat Juga
* class [`Attachment`](/watermark/python-net/groupdocs.watermark.common/attachment/)
