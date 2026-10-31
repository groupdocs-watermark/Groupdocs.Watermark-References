---
title: "Ottieni i formati di file supportati"
linkTitle: "Get supported file formats"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Elenca tutti i formati di file supportati da GroupDocs.Watermark per Python tramite .NET."
type: docs
url: /it/python-net/guides/get-supported-file-formats/
is_root: false
weight: 130
---


Recupera rapidamente l'elenco completo dei formati di file supportati da GroupDocs.Watermark. Questo consente alla tua applicazione di verificare dinamicamente la compatibilità prima di elaborare un documento — ad esempio, per convalidare i file caricati dagli utenti.

## List supported file formats

`FileType.get_supported_file_types()` restituisce tutti i tipi di file supportati. Ogni elemento espone la sua `extension` e una descrizione leggibile.

{{< tabs \"code-example-get-supported-file-formats\">}}
{{< tab \"list_supported_formats.py\" >}}
```python
from groupdocs.watermark.common import FileType

def list_supported_formats():
    # Elenca tutti i tipi di file che la libreria può aprire
    supported_file_types = FileType.get_supported_file_types()
    for file_type in sorted(supported_file_types, key=lambda x: x.extension):
        print(file_type)

if __name__ == "__main__":
    list_supported_formats()
```
{{< /tab >}}
{{< tab \"list-supported-formats.txt\" >}}
```text
Bmp (.bmp) - Image
Doc (.doc) - WordProcessing
Docm (.docm) - WordProcessing
Docx (.docx) - WordProcessing
Dot (.dot) - WordProcessing
Dotm (.dotm) - WordProcessing
Dotx (.dotx) - WordProcessing
Eml (.eml) - Email
Emlx (.emlx) - Email
Gif (.gif) - Image
[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/get-supported-file-formats/list_supported_formats/list-supported-formats.txt)
{{< /tab >}}
{{< /tabs >}}

**Use case:** Build flexible applications that validate user-uploaded files and tell the user whether watermarking is supported.
