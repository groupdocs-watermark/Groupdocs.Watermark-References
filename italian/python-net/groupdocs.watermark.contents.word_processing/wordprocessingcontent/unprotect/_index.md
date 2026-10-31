---
title: "metodo unprotect"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Rimuove la protezione dal documento indipendentemente dalla password."
type: docs
url: /it/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/unprotect/
is_root: false
weight: 1090
---


## unprotect

Rimuove la protezione dal documento indipendentemente dalla password.

```python
def unprotect(self):
    ...
```

### Esempio

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

def unprotect_document():
    with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
        content = watermarker.get_content()
        content.unprotect()
        watermarker.save("./output.docx")

if __name__ == "__main__":
    unprotect_document()
```

### Vedi anche
* class [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/)
