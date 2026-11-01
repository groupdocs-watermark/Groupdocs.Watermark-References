---
title: "__init__ yapıcı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "EmailLoadOptions sınıfının yeni bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.watermark.options.email/emailloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Yeni bir [`EmailLoadOptions`](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/) sınıfı örneği başlatır.

```python
def __init__(self):
    ...
```

### Örnek

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

### Ayrıca Bakınız
* class [`EmailLoadOptions`](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/)
