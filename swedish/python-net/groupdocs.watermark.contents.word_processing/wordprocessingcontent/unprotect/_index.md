---
title: "unprotect-metod"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Tar bort skyddet från dokumentet oavsett lösenord."
type: docs
url: /sv/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/unprotect/
is_root: false
weight: 1090
---


## unprotect

Tar bort skyddet från dokumentet oavsett lösenord.

```python
def unprotect(self):
    ...
```

### Exempel

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

### Se även
* class [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/)
