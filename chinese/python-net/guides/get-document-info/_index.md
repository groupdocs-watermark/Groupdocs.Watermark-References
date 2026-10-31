---
title: "获取文档信息"
linkTitle: "Get document info"
second_title: "GroupDocs.Watermark 用于 Python via .NET API 参考"
description: "使用 GroupDocs.Watermark for Python via .NET 检索文档的文件类型、页数和大小。"
type: docs
url: /zh/python-net/guides/get-document-info/
is_root: false
weight: 120
---


GroupDocs.Watermark 可以在处理文档之前获取文档的基本信息——文件类型、页数和大小。`get_document_info()` 方法适用于从文件路径或流打开的 [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)。

## Get document information from a file

{{< tabs "code-example-get-document-info">}}
{{< tab "get_document_info.py" >}}
```python
from groupdocs.watermark import Watermarker

def get_document_info():
    with Watermarker("./sample.docx") as watermarker:
        info = watermarker.get_document_info()
        print("File type:", info.file_type)
        print("Pages:", info.page_count)
        print("Size, bytes:", info.size)

if __name__ == "__main__":
    get_document_info()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` 是本示例使用的示例文件。点击 [此处](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/get-document-info/sample.docx) 下载它。

{{< /tab >}}
{{< tab "get-document-info.txt" >}}
```text
File type: Docx (.docx) - WordProcessing
Pages: 4
Size, bytes: 122480
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/get-document-info/get_document_info/get-document-info.txt)
{{< /tab >}}
{{< /tabs >}}

## Get document information from a stream

文档也可以从任何可读取的流中打开：

{{< tabs "code-example-get-document-info-stream">}}
{{< tab "get_document_info_from_stream.py" >}}
```python
import io
from groupdocs.watermark import Watermarker

def get_document_info_from_stream():
    with open("./sample.docx", "rb") as f:
        stream = io.BytesIO(f.read())

    with Watermarker(stream) as watermarker:
        info = watermarker.get_document_info()
        print("File type:", info.file_type)
        print("Pages:", info.page_count)
        print("Size, bytes:", info.size)

if __name__ == "__main__":
    get_document_info_from_stream()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` 是本示例使用的示例文件。点击 [此处](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/get-document-info/sample.docx) 下载它。

{{< /tab >}}
{{< tab "get-document-info-from-stream.txt" >}}
```text
File type: Docx (.docx) - WordProcessing
Pages: 4
Size, bytes: 122480
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/get-document-info/get_document_info_from_stream/get-document-info-from-stream.txt)
{{< /tab >}}
{{< /tabs >}}

**Use case:** Validate documents before processing — for example, reject unsupported file types or confirm page limits.
