---
title: "get_document_info मेथड"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "लोड किए गए दस्तावेज़ के फ़ॉर्मेट के बारे में जानकारी प्राप्त करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark/watermarker/get_document_info/
is_root: false
weight: 1070
---


## get_document_info

लोड किए गए दस्तावेज़ के फ़ॉर्मेट के बारे में जानकारी प्राप्त करता है।

दस्तावेज़ जानकारी प्राप्त करने के बारे में अधिक जानें।

```python
def get_document_info(self):
    ...
```

**Returns:** IDocumentInfo: The instance that contains detected information.

### उदाहरण

```python
    from groupdocs.watermark import Watermarker

    with Watermarker("./sample.docx") as watermarker:
        info = watermarker.get_document_info()
        print("File type:", info.file_type)
        print("Pages:", info.page_count)
        print("Size, bytes:", info.size)
    ```

### संबंधित देखें
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
