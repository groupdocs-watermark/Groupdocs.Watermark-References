---
title: "Desteklenen dosya formatlarını alın"
linkTitle: "Get supported file formats"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: ".NET üzerinden Python için GroupDocs.Watermark tarafından desteklenen tüm dosya formatlarını listeleyin."
type: docs
url: /tr/python-net/guides/get-supported-file-formats/
is_root: false
weight: 130
---


GroupDocs.Watermark tarafından desteklenen dosya formatlarının tam listesini hızlıca alın. Bu, uygulamanızın bir belgeyi işlemeye başlamadan önce uyumluluğu dinamik olarak kontrol etmesini sağlar — örneğin, kullanıcı tarafından yüklenen dosyaları doğrulamak için.

## List supported file formats

`FileType.get_supported_file_types()` tüm desteklenen dosya türlerini döndürür. Her öğe `extension` özelliğini ve dostane bir açıklamayı gösterir.

{{< tabs "code-example-get-supported-file-formats">}}
{{< tab "list_supported_formats.py" >}}
```python
from groupdocs.watermark.common import FileType

def list_supported_formats():
    # Kütüphanenin açabildiği her dosya türünü listeleyin
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
