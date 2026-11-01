---
title: "метод link_to_previous"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Связывает или разрывает связь всех заголовков и нижних колонтитулов с соответствующими заголовками и нижними колонтитулами в предыдущем разделе."
type: docs
url: /ru/python-net/groupdocs.watermark.contents.word_processing/wordprocessingheaderfootercollection/link_to_previous/
is_root: false
weight: 1030
---


## link_to_previous {#is_link_to_previous}

Связывает или разрывает связь всех заголовков и нижних колонтитулов с соответствующими заголовками и нижними колонтитулами в предыдущем разделе.

```python
def link_to_previous(self, is_link_to_previous):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| is_link_to_previous | `bool` | True, чтобы связать заголовки и колонтитулы с предыдущим разделом; False, чтобы разорвать связь. |

### Пример

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

### См. также
* class [`WordProcessingHeaderFooterCollection`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingheaderfootercollection/)
