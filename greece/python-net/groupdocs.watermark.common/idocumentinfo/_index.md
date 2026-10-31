---
title: "Κλάση IDocumentInfo"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Παρέχει τις μεθόδους που απαιτούνται για την ανάκτηση βασικών πληροφοριών εγγράφου."
type: docs
url: /el/python-net/groupdocs.watermark.common/idocumentinfo/
is_root: false
weight: 70
---


## IDocumentInfo class

Παρέχει τις μεθόδους που απαιτούνται για την ανάκτηση βασικών πληροφοριών εγγράφου.

Μάθετε περισσότερα: Λάβετε πληροφορίες εγγράφου.

Ο τύπος IDocumentInfo εκθέτει τα ακόλουθα μέλη:

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/file_type/) | Η περιγραφή μορφής αρχείου. |
| [is_encrypted](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/is_encrypted/) | Η ιδιότητα υποδεικνύει εάν το έγγραφο είναι κρυπτογραφημένο και απαιτεί κωδικό πρόσβασης για άνοιγμα. |
| [page_count](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/page_count/) | Ο συνολικός αριθμός σελίδων. |
| [pages](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/pages/) | Η συλλογή περιγραφών σελίδων εγγράφου. |
| [size](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/size/) | Το μέγεθος του εγγράφου σε bytes. |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker

with Watermarker(r"D:\input.pdf") as watermarker:
    doc_info = watermarker.get_document_info()
    print(f"Document size: {doc_info.size}")
    print(f"Document format: {doc_info.file_type.file_format_name}")
    print(f"Document contains {doc_info.page_count} pages")
```

### Δείτε επίσης
* module [`groupdocs.watermark.common`](/watermark/python-net/groupdocs.watermark.common/)
