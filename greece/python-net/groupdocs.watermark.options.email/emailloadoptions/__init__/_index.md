---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης EmailLoadOptions."
type: docs
url: /el/python-net/groupdocs.watermark.options.email/emailloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Αρχικοποιεί μια νέα παρουσία της κλάσης [`EmailLoadOptions`](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/).

```python
def __init__(self):
    ...
```

### Παράδειγμα

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.email import EmailLoadOptions

def modify_message():
    with Watermarker("./message.msg", EmailLoadOptions()) as watermarker:
        content = watermarker.get_content()
        content.subject = content.subject + " [CONFIDENTIAL]"
        content.body = content.body + "\n\nThis message is confidential."
        watermarker.save("./output.msg")
```

### Δείτε επίσης
* class [`EmailLoadOptions`](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/)
