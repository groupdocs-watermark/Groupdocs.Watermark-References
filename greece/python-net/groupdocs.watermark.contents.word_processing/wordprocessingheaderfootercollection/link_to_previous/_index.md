---
title: "μέθοδος link_to_previous"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Συνδέει ή αποσυνδέει όλα τα κεφαλίδες και υποσέλιδα με τις αντίστοιχες κεφαλίδες και υποσέλιδα στην προηγούμενη ενότητα."
type: docs
url: /el/python-net/groupdocs.watermark.contents.word_processing/wordprocessingheaderfootercollection/link_to_previous/
is_root: false
weight: 1030
---


## link_to_previous {#is_link_to_previous}

Συνδέει ή αποσυνδέει όλα τα κεφαλίδες και υποσέλιδα με τις αντίστοιχες κεφαλίδες και υποσέλιδα στην προηγούμενη ενότητα.

```python
def link_to_previous(self, is_link_to_previous):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| is_link_to_previous | `bool` | True για σύνδεση των κεφαλίδων και υποσέλιδων με την προηγούμενη ενότητα· False για αποσύνδεσή τους. |

### Παράδειγμα

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions
import groupdocs.watermark.contents.word_processing as wp

load_options = WordProcessingLoadOptions()
with gw.Watermarker("document.docx", load_options) as watermarker:
    content = watermarker.get_content()
    for i in range(1, content.sections.count):
        content.sections[i].headers_footers.link_to_previous(True)
    watermarker.save("output.docx")
```

### Δείτε επίσης
* class [`WordProcessingHeaderFooterCollection`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingheaderfootercollection/)
