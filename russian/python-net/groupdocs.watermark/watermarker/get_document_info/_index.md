---
title: "метод get_document_info"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Получает информацию о формате загруженного документа."
type: docs
url: /ru/python-net/groupdocs.watermark/watermarker/get_document_info/
is_root: false
weight: 1070
---


## get_document_info

Получает информацию о формате загруженного документа.

Узнайте больше о получении информации о документе.

```python
def get_document_info(self):
    ...
```

**Returns:** IDocumentInfo: The instance that contains detected information.

### Пример

```python
    from groupdocs.watermark import Watermarker

    with Watermarker("./sample.docx") as watermarker:
        info = watermarker.get_document_info()
        print("File type:", info.file_type)
        print("Pages:", info.page_count)
        print("Size, bytes:", info.size)
    ```

### См. также
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
