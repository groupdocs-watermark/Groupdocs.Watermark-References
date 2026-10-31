---
title: "metode unprotect"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Menghapus perlindungan dari dokumen terlepas dari kata sandi."
type: docs
url: /id/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/unprotect/
is_root: false
weight: 1090
---


## unprotect

Menghapus perlindungan dari dokumen terlepas dari kata sandi.

```python
def unprotect(self):
    ...
```

### Contoh

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

### Lihat Juga
* class [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/)
