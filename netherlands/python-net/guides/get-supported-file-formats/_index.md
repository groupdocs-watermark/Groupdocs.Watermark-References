---
title: "Ophalen ondersteunde bestandsformaten"
linkTitle: "Get supported file formats"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Lijst alle bestandsformaten die worden ondersteund door GroupDocs.Watermark voor Python via .NET."
type: docs
url: /nl/python-net/guides/get-supported-file-formats/
is_root: false
weight: 130
---


Haal snel de volledige lijst met bestandsformaten op die door GroupDocs.Watermark worden ondersteund. Hiermee kan je applicatie dynamisch de compatibiliteit controleren voordat een document wordt verwerkt — bijvoorbeeld om door gebruikers geüploade bestanden te valideren.

## List supported file formats

`FileType.get_supported_file_types()` retourneert elk ondersteund bestandstype. Elk item geeft zijn `extension` en een vriendelijke beschrijving weer.

{{< tabs "code-example-get-supported-file-formats">}}
{{< tab "list_supported_formats.py" >}}
```python
from groupdocs.watermark.common import FileType

def list_supported_formats():
    # Som alle bestandstypen op die de bibliotheek kan openen
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
