---
title: "Dokumentinformationen abrufen"
linkTitle: "Get document info"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Rufe Dateityp, Seitenanzahl und Größe eines Dokuments mit GroupDocs.Watermark für Python über .NET ab."
type: docs
url: /de/python-net/guides/get-document-info/
is_root: false
weight: 120
---


GroupDocs.Watermark kann die grundlegenden Informationen eines Dokuments — Dateityp, Seitenanzahl und Größe — abrufen, bevor du es verarbeitest. Die Methode `get_document_info()` funktioniert mit einem [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/), der entweder von einem Dateipfad oder einem Stream geöffnet wurde.

## Get document information from a file

{{< tabs \"code-example-get-document-info\" >}}
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

`sample.docx` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicke [hier](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/get-document-info/sample.docx) zum Herunterladen.

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

Ein Dokument kann auch von jedem lesbaren Stream geöffnet werden:

{{< tabs \"code-example-get-document-info-stream\" >}}
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

`sample.docx` ist die Beispieldatei, die in diesem Beispiel verwendet wird. Klicke [hier](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/get-document-info/sample.docx) zum Herunterladen.

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
