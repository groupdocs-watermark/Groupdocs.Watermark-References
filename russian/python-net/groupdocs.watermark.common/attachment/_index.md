---
title: "Класс Attachment"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Представляет файл, прикреплённый к документу."
type: docs
url: /ru/python-net/groupdocs.watermark.common/attachment/
is_root: false
weight: 10
---


## Attachment class

Представляет файл, прикреплённый к документу.

Узнать больше

- https://docs.groupdocs.com/display/watermarknet/Email+attachments
- https://docs.groupdocs.com/display/watermarknet/Attachments+in+PDF+document
- https://docs.groupdocs.com/display/watermarknet/Working+with+spreadsheet+document+attachments

Тип Attachment раскрывает следующие члены:

### Методы
| Метод | Описание |
| :- | :- |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/) | Загружает содержимое из прикреплённого файла. |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/#load_options) | Загружает содержимое из прикреплённого файла с указанными параметрами загрузки. |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/#load_options-watermarker_settings) | Загружает содержимое из прикреплённого файла с указанными параметрами загрузки и настройками. |
| [create_watermarker_load_options](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker_load_options/) |  |
| [get_document_info](/watermark/python-net/groupdocs.watermark.common/attachment/get_document_info/) | Получает информацию о документе, хранящемся в прикреплённом файле. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [content](/watermark/python-net/groupdocs.watermark.common/attachment/content/) | Содержимое прикреплённого файла. |

### Пример

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

### См. также
* module [`groupdocs.watermark.common`](/watermark/python-net/groupdocs.watermark.common/)
