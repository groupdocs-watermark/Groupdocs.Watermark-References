---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "EmailLoadOptions क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.options.email/emailloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

एक नया उदाहरण प्रारंभ करता है [`EmailLoadOptions`](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/) क्लास का।

```python
def __init__(self):
    ...
```

### उदाहरण

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

### संबंधित देखें
* class [`EmailLoadOptions`](/watermark/python-net/groupdocs.watermark.options.email/emailloadoptions/)
