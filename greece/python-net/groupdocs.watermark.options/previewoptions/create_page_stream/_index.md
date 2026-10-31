---
title: "ιδιότητα create_page_stream"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Ο delegate δημιουργίας ροής σελίδας που χρησιμοποιείται για την απόκτηση μιας εγγράψιμης ροής για κάθε αποδομένη σελίδα."
type: docs
url: /el/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/
is_root: false
weight: 2010
---


## create_page_stream property

Ο delegate δημιουργίας ροής σελίδας που χρησιμοποιείται για την απόκτηση μιας εγγράψιμης ροής για κάθε αποδομένη σελίδα.

Το GroupDocs.Watermark αποδίδει τις σελίδες εγγράφου ως εικόνες. Παρέχετε ένα callable που λαμβάνει έναν αριθμό σελίδας (`int`) και επιστρέφει μια εγγράψιμη ροή `io.RawIOBase`; η βιβλιοθήκη γράφει την αποδοθείσα εικόνα στη ροή και την κλείνει.

### Definition:
```python
@property
def create_page_stream(self):
    ...
@create_page_stream.setter
def create_page_stream(self, value):
    ...
```

### Δείτε επίσης
* class [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)
