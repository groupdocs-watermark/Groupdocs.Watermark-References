---
title: "__init__ constructor"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Inicializa una nueva instancia de la clase EmailLoadOptions."
type: docs
url: /es/python-net/groupdocs.watermark.options.email/emailloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una nueva instancia de la clase [`EmailLoadOptions`](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/).

```python
def __init__(self):
    ...
```

### Ejemplo

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

### Ver también
* class [`EmailLoadOptions`](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/)
