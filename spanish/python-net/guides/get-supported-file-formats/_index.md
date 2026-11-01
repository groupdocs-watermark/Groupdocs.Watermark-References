---
title: "Obtener formatos de archivo compatibles"
linkTitle: "Get supported file formats"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Enumere todos los formatos de archivo compatibles con GroupDocs.Watermark para Python a través de .NET."
type: docs
url: /es/python-net/guides/get-supported-file-formats/
is_root: false
weight: 130
---


Recupere rápidamente la lista completa de formatos de archivo compatibles con GroupDocs.Watermark. Esto permite que su aplicación verifique la compatibilidad de forma dinámica antes de procesar un documento, por ejemplo, para validar archivos cargados por el usuario.

## List supported file formats

`FileType.get_supported_file_types()` devuelve todos los tipos de archivo compatibles. Cada elemento expone su `extension` y una descripción amigable.

{{< tabs "code-example-get-supported-file-formats">}}
{{< tab "list_supported_formats.py" >}}
```python
from groupdocs.watermark.common import FileType

def list_supported_formats():
    # Enumere cada tipo de archivo que la biblioteca puede abrir
    supported_file_types = FileType.get_supported_file_types()
    for file_type in sorted(supported_file_types, key=lambda x: x.extension):
        print(file_type)

if __name__ == "__main__":
    list_supported_formats()
```
{{< /tab >}}
{{< tab "list-supported-formats.txt" >}}
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
