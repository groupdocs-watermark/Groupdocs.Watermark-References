---
title: "Dapatkan format file yang didukung"
linkTitle: "Get supported file formats"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Daftar semua format file yang didukung oleh GroupDocs.Watermark untuk Python melalui .NET."
type: docs
url: /id/python-net/guides/get-supported-file-formats/
is_root: false
weight: 130
---


Segera dapatkan daftar lengkap format file yang didukung oleh GroupDocs.Watermark. Ini memungkinkan aplikasi Anda memeriksa kompatibilitas secara dinamis sebelum memproses dokumen — misalnya, untuk memvalidasi file yang diunggah pengguna.

## List supported file formats

`FileType.get_supported_file_types()` mengembalikan setiap tipe file yang didukung. Setiap item menampilkan `extension`-nya dan deskripsi yang ramah.

{{< tabs "code-example-get-supported-file-formats">}}
{{< tab "list_supported_formats.py" >}}
```python
from groupdocs.watermark.common import FileType

def list_supported_formats():
    # Enumerasikan setiap jenis file yang dapat dibuka oleh perpustakaan
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
