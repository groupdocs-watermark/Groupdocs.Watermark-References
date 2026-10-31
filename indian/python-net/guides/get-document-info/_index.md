---
title: "दस्तावेज़ जानकारी प्राप्त करें"
linkTitle: "Get document info"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "GroupDocs.Watermark for Python via .NET का उपयोग करके दस्तावेज़ का फ़ाइल प्रकार, पृष्ठ गिनती और आकार प्राप्त करें।"
type: docs
url: /hi/python-net/guides/get-document-info/
is_root: false
weight: 120
---


GroupDocs.Watermark दस्तावेज़ की मूल जानकारी — फ़ाइल प्रकार, पृष्ठ गिनती, और आकार — को प्रोसेस करने से पहले प्राप्त कर सकता है। `get_document_info()` मेथड एक [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) पर काम करता है जिसे फ़ाइल पाथ या स्ट्रीम से खोला गया हो।

## Get document information from a file

{{< tabs \"code-example-get-document-info\">}}
{{< tab \"get_document_info.py\" >}}
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

`sample.docx` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/get-document-info/sample.docx) क्लिक करें।

{{< /tab >}}
{{< tab \"get-document-info.txt\" >}}
```text
File type: Docx (.docx) - WordProcessing
Pages: 4
Size, bytes: 122480
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/get-document-info/get_document_info/get-document-info.txt)
{{< /tab >}}
{{< /tabs >}}

## Get document information from a stream

किसी भी पठनीय स्ट्रीम से भी दस्तावेज़ खोला जा सकता है:

{{< tabs \"code-example-get-document-info-stream\">}}
{{< tab \"get_document_info_from_stream.py\" >}}
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

`sample.docx` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/get-document-info/sample.docx) क्लिक करें।

{{< /tab >}}
{{< tab \"get-document-info-from-stream.txt\" >}}
```text
File type: Docx (.docx) - WordProcessing
Pages: 4
Size, bytes: 122480
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/get-document-info/get_document_info_from_stream/get-document-info-from-stream.txt)
{{< /tab >}}
{{< /tabs >}}

**Use case:** Validate documents before processing — for example, reject unsupported file types or confirm page limits.
