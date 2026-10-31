---
title: "get_document_info 方法"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "获取已加载文档格式的信息。"
type: docs
url: /zh/python-net/groupdocs.watermark/watermarker/get_document_info/
is_root: false
weight: 1070
---


## get_document_info

获取已加载文档格式的信息。

了解更多关于获取文档信息的内容。

```python
def get_document_info(self):
    ...
```

**Returns:** IDocumentInfo: The instance that contains detected information.

### 示例

```python
    from groupdocs.watermark import Watermarker

    with Watermarker("./sample.docx") as watermarker:
        info = watermarker.get_document_info()
        print("File type:", info.file_type)
        print("Pages:", info.page_count)
        print("Size, bytes:", info.size)
    ```

### 另请参见
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
