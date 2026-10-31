---
title: "protect μέθοδος"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Προστατεύει το έγγραφο από αλλαγές και ορίζει κωδικό προστασίας."
type: docs
url: /el/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect/
is_root: false
weight: 1050
---


## protect {#protection_type-password}

Προστατεύει το έγγραφο από αλλαγές και ορίζει κωδικό προστασίας.

Για να είναι το περιεχόμενο του εγγράφου επεξεργάσιμο, χρησιμοποιήστε τη κατάλληλη μέθοδο προσθήκης υδατογραφήματος με την παράμετρο `WordProcessingLockType.allow_only_form_fields` ή `WordProcessingLockType.read_only_with_editable_content`.

```python
def protect(self, protection_type, password):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| protection_type | `WordProcessingProtectionType` | Καθορίζει τον τύπο προστασίας για το έγγραφο. |
| password | `str` | Ο κωδικός πρόσβασης για την προστασία του εγγράφου. |

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions
from groupdocs.watermark.contents.word_processing import WordProcessingProtectionType

def protect_document():
    with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
        content = watermarker.get_content()
        content.protect(WordProcessingProtectionType.READ_ONLY, "p@ssw0rd")
        watermarker.save("./output.docx")
```

### Δείτε επίσης
* class [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/)
