---
title: "метод create_watermarker"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Загружает содержимое из прикреплённого файла."
type: docs
url: /ru/python-net/groupdocs.watermark.common/attachment/create_watermarker/
is_root: false
weight: 1010
---


## create_watermarker

Загружает содержимое из прикреплённого файла.

```python
def create_watermarker(self):
    ...
```

**Returns:** The instance of appropriate descendant of `Content` class.

### Пример

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

Загружает содержимое из прикреплённого файла с указанными параметрами загрузки.

```python
def create_watermarker(self, load_options):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| load_options | `LoadOptions` | Дополнительные параметры, используемые при загрузке содержимого вложения. |

**Returns:** Content: The instance of appropriate descendant of `Content` class.

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

## create_watermarker {#load_options-watermarker_settings}

Загружает содержимое из прикреплённого файла с указанными параметрами загрузки и настройками.

```python
def create_watermarker(self, load_options, watermarker_settings):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| load_options | `LoadOptions` | Дополнительные параметры, используемые при загрузке содержимого вложения. |
| watermarker_settings | `WatermarkerSettings` | Дополнительные настройки, используемые при работе с загруженным документом. |

**Returns:** The instance of appropriate descendant of `Content` class.

### Пример

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

### См. также
* class [`Attachment`](/watermark/python-net/groupdocs.watermark.common/attachment/)
