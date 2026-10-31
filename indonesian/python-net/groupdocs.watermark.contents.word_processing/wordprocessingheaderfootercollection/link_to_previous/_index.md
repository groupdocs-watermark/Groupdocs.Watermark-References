---
title: "metode link_to_previous"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Menautkan atau memutuskan semua header dan footer ke header dan footer yang sesuai di bagian sebelumnya."
type: docs
url: /id/python-net/groupdocs.watermark.contents.word_processing/wordprocessingheaderfootercollection/link_to_previous/
is_root: false
weight: 1030
---


## link_to_previous {#is_link_to_previous}

Menautkan atau memutuskan semua header dan footer ke header dan footer yang sesuai di bagian sebelumnya.

```python
def link_to_previous(self, is_link_to_previous):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| is_link_to_previous | `bool` | True untuk menautkan header dan footer ke bagian sebelumnya; False untuk memutus tautannya. |

### Contoh

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions
import groupdocs.watermark.contents.word_processing as wp

load_options = WordProcessingLoadOptions()
with gw.Watermarker("document.docx", load_options) as watermarker:
    content = watermarker.get_content()
    for i in range(1, content.sections.count):
        content.sections[i].headers_footers.link_to_previous(True)
    watermarker.save("output.docx")
```

### Lihat Juga
* class [`WordProcessingHeaderFooterCollection`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingheaderfootercollection/)
