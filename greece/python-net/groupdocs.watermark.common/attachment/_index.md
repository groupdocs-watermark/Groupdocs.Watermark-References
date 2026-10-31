---
title: "Κλάση Attachment"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει ένα αρχείο που επισυνάπτεται σε ένα έγγραφο."
type: docs
url: /el/python-net/groupdocs.watermark.common/attachment/
is_root: false
weight: 10
---


## Attachment class

Αντιπροσωπεύει ένα αρχείο που επισυνάπτεται σε ένα έγγραφο.

Μάθετε περισσότερα

- https://docs.groupdocs.com/display/watermarknet/Email+attachments
- https://docs.groupdocs.com/display/watermarknet/Attachments+in+PDF+document
- https://docs.groupdocs.com/display/watermarknet/Working+with+spreadsheet+document+attachments

Ο τύπος Attachment εκθέτει τα ακόλουθα μέλη:

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/) | Φορτώνει περιεχόμενο από το συνημμένο αρχείο. |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/#load_options) | Φορτώνει περιεχόμενο από το συνημμένο αρχείο με τις καθορισμένες επιλογές φόρτωσης. |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/#load_options-watermarker_settings) | Φορτώνει περιεχόμενο από το συνημμένο αρχείο με τις καθορισμένες επιλογές φόρτωσης και ρυθμίσεις. |
| [create_watermarker_load_options](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker_load_options/) |  |
| [get_document_info](/watermark/python-net/groupdocs.watermark.common/attachment/get_document_info/) | Ανακτά τις πληροφορίες για ένα έγγραφο που είναι αποθηκευμένο στο συνημμένο αρχείο. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [content](/watermark/python-net/groupdocs.watermark.common/attachment/content/) | Το περιεχόμενο του συνημμένου αρχείου. |

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

### Δείτε επίσης
* module [`groupdocs.watermark.common`](/watermark/python-net/groupdocs.watermark.common/)
