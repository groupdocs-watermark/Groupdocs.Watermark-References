---
title: "Hämta dokumentinformation"
linkTitle: "Get document info"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Hämta filtyp, sidantal och storlek på ett dokument med GroupDocs.Watermark för Python via .NET."
type: docs
url: /sv/python-net/guides/get-document-info/
is_root: false
weight: 120
---


GroupDocs.Watermark kan hämta ett dokuments grundläggande information — filtyp, sidantal och storlek — innan du bearbetar det. Metoden `get_document_info()` fungerar på en [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) som öppnats från antingen en filsökväg eller en ström.

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

`sample.docx` är exempel-filen som används i detta exempel. Klicka [här](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/get-document-info/sample.docx) för att ladda ner den.

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

Ett dokument kan också öppnas från vilken läsbar ström som helst:

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

`sample.docx` är exempel-filen som används i detta exempel. Klicka [här](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/get-document-info/sample.docx) för att ladda ner den.

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
