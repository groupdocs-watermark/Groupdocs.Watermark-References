---
title: "μέθοδος create_watermarker"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Φορτώνει περιεχόμενο από το συνημμένο αρχείο."
type: docs
url: /el/python-net/groupdocs.watermark.common/attachment/create_watermarker/
is_root: false
weight: 1010
---


## create_watermarker

Φορτώνει περιεχόμενο από το συνημμένο αρχείο.

```python
def create_watermarker(self):
    ...
```

**Returns:** The instance of appropriate descendant of `Content` class.

### Παράδειγμα

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

Φορτώνει περιεχόμενο από το συνημμένο αρχείο με τις καθορισμένες επιλογές φόρτωσης.

```python
def create_watermarker(self, load_options):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| load_options | `LoadOptions` | Πρόσθετες επιλογές για χρήση κατά τη φόρτωση του περιεχομένου ενός συνημμένου. |

**Returns:** Content: The instance of appropriate descendant of `Content` class.

### Παράδειγμα

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

Φορτώνει περιεχόμενο από το συνημμένο αρχείο με τις καθορισμένες επιλογές φόρτωσης και ρυθμίσεις.

```python
def create_watermarker(self, load_options, watermarker_settings):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| load_options | `LoadOptions` | Πρόσθετες επιλογές για χρήση κατά τη φόρτωση του περιεχομένου ενός συνημμένου. |
| watermarker_settings | `WatermarkerSettings` | Πρόσθετες ρυθμίσεις για χρήση κατά την εργασία με το φορτωμένο έγγραφο. |

**Returns:** The instance of appropriate descendant of `Content` class.

### Παράδειγμα

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

### Δείτε επίσης
* class [`Attachment`](/watermark/python-net/groupdocs.watermark.common/attachment/)
