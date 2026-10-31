---
title: "Ottieni informazioni sul documento"
linkTitle: "Get document info"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Recupera il tipo di file, il numero di pagine e la dimensione di un documento usando GroupDocs.Watermark per Python tramite .NET."
type: docs
url: /it/python-net/guides/get-document-info/
is_root: false
weight: 120
---


GroupDocs.Watermark può ottenere le informazioni di base di un documento — tipo di file, numero di pagine e dimensione — prima di elaborarlo. Il metodo `get_document_info()` funziona su un [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) aperto sia da un percorso file sia da uno stream.

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

`sample.docx` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/get-document-info/sample.docx) per scaricarlo.

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

Un documento può anche essere aperto da qualsiasi stream leggibile:

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

`sample.docx` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/get-document-info/sample.docx) per scaricarlo.

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
