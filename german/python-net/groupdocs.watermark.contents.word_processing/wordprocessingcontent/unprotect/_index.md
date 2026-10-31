---
title: "unprotect-Methode"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Entfernt den Schutz des Dokuments, unabhängig vom Kennwort."
type: docs
url: /de/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/unprotect/
is_root: false
weight: 1090
---


## unprotect

Entfernt den Schutz des Dokuments, unabhängig vom Kennwort.

```python
def unprotect(self):
    ...
```

### Beispiel

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

### Siehe auch
* class [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/)
