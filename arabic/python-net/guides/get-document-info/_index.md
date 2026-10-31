---
title: "احصل على معلومات المستند"
linkTitle: "Get document info"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "استرجع نوع الملف، عدد الصفحات، وحجم المستند باستخدام GroupDocs.Watermark للبايثون عبر .NET."
type: docs
url: /ar/python-net/guides/get-document-info/
is_root: false
weight: 120
---


يمكن لـ GroupDocs.Watermark الحصول على المعلومات الأساسية للمستند — نوع الملف، عدد الصفحات، والحجم — قبل معالجته. تعمل طريقة `get_document_info()` على كائن [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) المفتوح إما من مسار ملف أو من تدفق.

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

`sample.docx` هو ملف العينة المستخدم في هذا المثال. انقر على [هنا](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/get-document-info/sample.docx) لتحميله.

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

يمكن أيضًا فتح المستند من أي تدفق قابل للقراءة:

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

`sample.docx` هو ملف العينة المستخدم في هذا المثال. انقر على [هنا](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/get-document-info/sample.docx) لتحميله.

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
