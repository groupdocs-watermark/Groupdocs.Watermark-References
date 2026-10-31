---
title: "unprotect मेथड"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "पासवर्ड की परवाह किए बिना दस्तावेज़ से सुरक्षा हटाता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/unprotect/
is_root: false
weight: 1090
---


## unprotect

पासवर्ड की परवाह किए बिना दस्तावेज़ से सुरक्षा हटाता है।

```python
def unprotect(self):
    ...
```

### उदाहरण

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

### संबंधित देखें
* class [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/)
