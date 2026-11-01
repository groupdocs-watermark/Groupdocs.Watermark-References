---
title: "ドキュメント情報を取得"
linkTitle: "Get document info"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "GroupDocs.Watermark for Python via .NET を使用して、ドキュメントのファイルタイプ、ページ数、サイズを取得します。"
type: docs
url: /ja/python-net/guides/get-document-info/
is_root: false
weight: 120
---


GroupDocs.Watermark は、ドキュメントを処理する前に、基本情報（ファイルタイプ、ページ数、サイズ）を取得できます。`get_document_info()` メソッドは、ファイルパスまたはストリームのいずれかから開かれた [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) で動作します。

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
{{< tab \"sample.docx\" >}}

`sample.docx` はこの例で使用されるサンプルファイルです。ダウンロードするには、[ここ](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/get-document-info/sample.docx) をクリックしてください。

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

ドキュメントは、任意の読み取り可能なストリームからも開くことができます:

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
{{< tab \"sample.docx\" >}}

`sample.docx` はこの例で使用されるサンプルファイルです。ダウンロードするには、[ここ](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/get-document-info/sample.docx) をクリックしてください。

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
