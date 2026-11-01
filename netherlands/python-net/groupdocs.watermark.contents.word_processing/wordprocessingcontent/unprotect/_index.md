---
title: "unprotect methode"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Verwijdert de bescherming van het document, ongeacht het wachtwoord."
type: docs
url: /nl/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/unprotect/
is_root: false
weight: 1090
---


## unprotect

Verwijdert de bescherming van het document, ongeacht het wachtwoord.

```python
def unprotect(self):
    ...
```

### Voorbeeld

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

### Zie ook
* class [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/)
