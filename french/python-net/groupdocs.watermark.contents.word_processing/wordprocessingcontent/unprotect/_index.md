---
title: "méthode unprotect"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Supprime la protection du document quel que soit le mot de passe."
type: docs
url: /fr/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/unprotect/
is_root: false
weight: 1090
---


## unprotect

Supprime la protection du document quel que soit le mot de passe.

```python
def unprotect(self):
    ...
```

### Exemple

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

### Voir aussi
* class [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/)
