---
title: "Unterstützte Dateiformate abrufen"
linkTitle: "Get supported file formats"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Alle von GroupDocs.Watermark für Python über .NET unterstützten Dateiformate auflisten."
type: docs
url: /de/python-net/guides/get-supported-file-formats/
is_root: false
weight: 130
---


Rufe schnell die vollständige Liste der von GroupDocs.Watermark unterstützten Dateiformate ab. Dadurch kann deine Anwendung die Kompatibilität dynamisch prüfen, bevor ein Dokument verarbeitet wird – zum Beispiel, um vom Benutzer hochgeladene Dateien zu validieren.

## List supported file formats

`FileType.get_supported_file_types()` gibt jeden unterstützten Dateityp zurück. Jeder Eintrag stellt seine `extension` und eine benutzerfreundliche Beschreibung bereit.

{{< tabs \"code-example-get-supported-file-formats\" >}}
{{< tab \"list_supported_formats.py\" >}}
```python
from groupdocs.watermark.common import FileType

def list_supported_formats():
    # Alle Dateitypen auflisten, die die Bibliothek öffnen kann
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
