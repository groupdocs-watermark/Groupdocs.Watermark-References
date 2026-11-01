---
title: "Attachment sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Bir belgeye eklenmiş dosyayı temsil eder."
type: docs
url: /tr/python-net/groupdocs.watermark.common/attachment/
is_root: false
weight: 10
---


## Attachment class

Bir belgeye eklenmiş dosyayı temsil eder.

Daha fazla bilgi.

- https://docs.groupdocs.com/display/watermarknet/Email+attachments
- https://docs.groupdocs.com/display/watermarknet/Attachments+in+PDF+document
- https://docs.groupdocs.com/display/watermarknet/Working+with+spreadsheet+document+attachments

Attachment türü aşağıdaki üyeleri gösterir:

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/) | Ekli dosyadan içerik yükler. |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/#load_options) | Ekli dosyadan belirtilen yükleme seçenekleriyle içerik yükler. |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/#load_options-watermarker_settings) | Ekli dosyadan belirtilen yükleme seçenekleri ve ayarlarla içerik yükler. |
| [create_watermarker_load_options](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker_load_options/) |  |
| [get_document_info](/watermark/python-net/groupdocs.watermark.common/attachment/get_document_info/) | Ekli dosyada depolanan bir belge hakkında bilgileri alır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [content](/watermark/python-net/groupdocs.watermark.common/attachment/content/) | Ekli dosya içeriği. |

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

### Ayrıca Bakınız
* module [`groupdocs.watermark.common`](/watermark/python-net/groupdocs.watermark.common/)
