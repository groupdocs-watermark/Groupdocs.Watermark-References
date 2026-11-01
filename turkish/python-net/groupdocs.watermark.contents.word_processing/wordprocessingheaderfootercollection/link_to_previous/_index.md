---
title: "link_to_previous yöntemi"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Tüm başlık ve altbilgileri önceki bölümdeki karşılık gelen başlık ve altbilgilere bağlar veya bağını kaldırır."
type: docs
url: /tr/python-net/groupdocs.watermark.contents.word_processing/wordprocessingheaderfootercollection/link_to_previous/
is_root: false
weight: 1030
---


## link_to_previous {#is_link_to_previous}

Tüm başlık ve altbilgileri önceki bölümdeki karşılık gelen başlık ve altbilgilere bağlar veya bağını kaldırır.

```python
def link_to_previous(self, is_link_to_previous):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| is_link_to_previous | `bool` | Başlıkları ve altbilgileri önceki bölüme bağlamak için True; Bağlantıyı kaldırmak için False. |

### Örnek

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

### Ayrıca Bakınız
* class [`WordProcessingHeaderFooterCollection`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingheaderfootercollection/)
