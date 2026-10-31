---
title: "__init__ costruttore"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Inizializza una nuova istanza della classe EmailLoadOptions."
type: docs
url: /it/python-net/groupdocs.watermark.options.email/emailloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una nuova istanza della classe [`EmailLoadOptions`](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/).

```python
def __init__(self):
    ...
```

### Esempio

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

### Vedi anche
* class [`EmailLoadOptions`](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/)
