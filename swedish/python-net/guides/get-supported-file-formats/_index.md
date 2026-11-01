---
title: "Hämta stödda filformat"
linkTitle: "Get supported file formats"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Lista alla filformat som stöds av GroupDocs.Watermark för Python via .NET."
type: docs
url: /sv/python-net/guides/get-supported-file-formats/
is_root: false
weight: 130
---


Hämta snabbt den fullständiga listan över filformat som stöds av GroupDocs.Watermark. Detta låter din applikation kontrollera kompatibilitet dynamiskt innan ett dokument bearbetas — till exempel för att validera användaruppladdade filer.

## List supported file formats

`FileType.get_supported_file_types()` returnerar alla stödda filtyper. Varje objekt visar sin `extension` och en beskrivning.

{{< tabs "code-example-get-supported-file-formats">}}
{{< tab "list_supported_formats.py" >}}
```python
from groupdocs.watermark.common import FileType

def list_supported_formats():
    # Enumerera alla filtyper som biblioteket kan öppna
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
