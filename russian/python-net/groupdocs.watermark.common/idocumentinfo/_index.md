---
title: "Класс IDocumentInfo"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Предоставляет методы, необходимые для получения основной информации о документе."
type: docs
url: /ru/python-net/groupdocs.watermark.common/idocumentinfo/
is_root: false
weight: 70
---


## IDocumentInfo class

Предоставляет методы, необходимые для получения основной информации о документе.

Узнать больше: Получить информацию о документе.

Тип IDocumentInfo раскрывает следующие члены:

### Свойства
| Свойство | Описание |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/file_type/) | Описание формата файла. |
| [is_encrypted](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/is_encrypted/) | Свойство указывает, зашифрован ли документ и требуется ли пароль для его открытия. |
| [page_count](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/page_count/) | Общее количество страниц. |
| [pages](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/pages/) | Коллекция описаний страниц документа. |
| [size](/watermark/python-net/groupdocs.watermark.common/idocumentinfo/size/) | Размер документа в байтах. |

### Пример

```python
from groupdocs.watermark import Watermarker

with Watermarker(r"D:\input.pdf") as watermarker:
    doc_info = watermarker.get_document_info()
    print(f"Document size: {doc_info.size}")
    print(f"Document format: {doc_info.file_type.file_format_name}")
    print(f"Document contains {doc_info.page_count} pages")
```

### См. также
* module [`groupdocs.watermark.common`](/watermark/python-net/groupdocs.watermark.common/)
