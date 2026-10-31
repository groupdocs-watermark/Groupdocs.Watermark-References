---
title: "get_document_info metode"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Mendapatkan informasi tentang format dokumen yang dimuat."
type: docs
url: /id/python-net/groupdocs.watermark/watermarker/get_document_info/
is_root: false
weight: 1070
---


## get_document_info

Mendapatkan informasi tentang format dokumen yang dimuat.

Pelajari lebih lanjut tentang mendapatkan informasi dokumen.

```python
def get_document_info(self):
    ...
```

**Returns:** IDocumentInfo: The instance that contains detected information.

### Contoh

```python
    from groupdocs.watermark import Watermarker

    with Watermarker("./sample.docx") as watermarker:
        info = watermarker.get_document_info()
        print("File type:", info.file_type)
        print("Pages:", info.page_count)
        print("Size, bytes:", info.size)
    ```

### Lihat Juga
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
