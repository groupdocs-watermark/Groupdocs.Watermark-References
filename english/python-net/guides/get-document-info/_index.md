---
title: Get document info
linkTitle: "Get document info"
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Retrieve file type, page count, and size of a document using GroupDocs.Watermark for Python via .NET."
type: docs
url: /python-net/guides/get-document-info/
is_root: false
weight: 120
---


GroupDocs.Watermark can obtain a document's basic information — file type, page count, and size — before you process it. The `get_document_info()` method works on a [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) opened from either a file path or a stream.

## Get document information from a file

  
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

  

`sample.docx` is the sample file used in this example. Click [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/get-document-info/sample.docx) to download it.

  
```text
File type: Docx (.docx) - WordProcessing
Pages: 3
Size, bytes: 121298
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/get-document-info/get_document_info/get-document-info.txt)

## Get document information from a stream

A document can also be opened from any readable stream:

  
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

  

`sample.docx` is the sample file used in this example. Click [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/get-document-info/sample.docx) to download it.

  
```text
File type: Docx (.docx) - WordProcessing
Pages: 3
Size, bytes: 121298
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/get-document-info/get_document_info_from_stream/get-document-info-from-stream.txt)

**Use case:** Validate documents before processing — for example, reject unsupported file types or confirm page limits.
