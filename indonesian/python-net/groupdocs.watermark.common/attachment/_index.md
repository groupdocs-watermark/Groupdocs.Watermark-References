---
title: "Kelas Attachment"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mewakili file yang dilampirkan ke dokumen."
type: docs
url: /id/python-net/groupdocs.watermark.common/attachment/
is_root: false
weight: 10
---


## Attachment class

Mewakili file yang dilampirkan ke dokumen.

Pelajari lebih lanjut

- https://docs.groupdocs.com/display/watermarknet/Email+attachments
- https://docs.groupdocs.com/display/watermarknet/Attachments+in+PDF+document
- https://docs.groupdocs.com/display/watermarknet/Working+with+spreadsheet+document+attachments

Tipe Attachment menampilkan anggota-anggota berikut:

### Metode
| Metode | Deskripsi |
| :- | :- |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/) | Memuat konten dari file yang dilampirkan. |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/#load_options) | Memuat konten dari file yang dilampirkan dengan opsi pemuatan yang ditentukan. |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/#load_options-watermarker_settings) | Memuat konten dari file yang dilampirkan dengan opsi pemuatan dan pengaturan yang ditentukan. |
| [create_watermarker_load_options](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker_load_options/) |  |
| [get_document_info](/watermark/python-net/groupdocs.watermark.common/attachment/get_document_info/) | Mengambil informasi tentang dokumen yang disimpan dalam file yang dilampirkan. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [content](/watermark/python-net/groupdocs.watermark.common/attachment/content/) | Konten file yang dilampirkan. |

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

### Lihat Juga
* module [`groupdocs.watermark.common`](/watermark/python-net/groupdocs.watermark.common/)
