---
title: "Obtener información del documento"
linkTitle: "Get document info"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Recupere el tipo de archivo, el número de páginas y el tamaño de un documento usando GroupDocs.Watermark para Python a través de .NET."
type: docs
url: /es/python-net/guides/get-document-info/
is_root: false
weight: 120
---


GroupDocs.Watermark puede obtener la información básica de un documento — tipo de archivo, número de páginas y tamaño — antes de procesarlo. El método `get_document_info()` funciona sobre un [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) abierto desde una ruta de archivo o un flujo.

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
{{< tab \"sample.docx\" >}}

`sample.docx` es el archivo de ejemplo usado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/get-document-info/sample.docx) para descargarlo.

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

Un documento también puede abrirse desde cualquier flujo legible:

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
{{< tab \"sample.docx\" >}}

`sample.docx` es el archivo de ejemplo usado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/get-document-info/sample.docx) para descargarlo.

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
