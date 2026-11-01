---
title: "método unprotect"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Elimina la protección del documento sin importar la contraseña."
type: docs
url: /es/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/unprotect/
is_root: false
weight: 1090
---


## unprotect

Elimina la protección del documento sin importar la contraseña.

```python
def unprotect(self):
    ...
```

### Ejemplo

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

### Ver también
* class [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/)
