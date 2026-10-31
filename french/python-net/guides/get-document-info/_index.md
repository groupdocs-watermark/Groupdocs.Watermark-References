---
title: "Obtenir les informations du document"
linkTitle: "Get document info"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Récupérez le type de fichier, le nombre de pages et la taille d'un document en utilisant GroupDocs.Watermark pour Python via .NET."
type: docs
url: /fr/python-net/guides/get-document-info/
is_root: false
weight: 120
---


GroupDocs.Watermark peut obtenir les informations de base d'un document — type de fichier, nombre de pages et taille — avant de le traiter. La méthode `get_document_info()` fonctionne sur un [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) ouvert à partir d'un chemin de fichier ou d'un flux.

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

`sample.docx` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/get-document-info/sample.docx) pour le télécharger.

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

Un document peut également être ouvert à partir de n'importe quel flux lisible :

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

`sample.docx` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/get-document-info/sample.docx) pour le télécharger.

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
