---
title: "Belge bilgilerini alın"
linkTitle: "Get document info"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: ".NET üzerinden Python için GroupDocs.Watermark kullanarak bir belgenin dosya türünü, sayfa sayısını ve boyutunu alın."
type: docs
url: /tr/python-net/guides/get-document-info/
is_root: false
weight: 120
---


GroupDocs.Watermark, bir belgeyi işlemeye başlamadan önce temel bilgilerini — dosya türü, sayfa sayısı ve boyut — elde edebilir. `get_document_info()` yöntemi, bir dosya yolu ya da akıştan açılan bir [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) üzerinde çalışır.

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

`sample.docx` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/get-document-info/sample.docx) tıklayın.

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

Bir belge ayrıca herhangi bir okunabilir akıştan da açılabilir:

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

`sample.docx` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/get-document-info/sample.docx) tıklayın.

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
