---
title: "Obtenir les formats de fichiers pris en charge"
linkTitle: "Get supported file formats"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Listez tous les formats de fichiers pris en charge par GroupDocs.Watermark pour Python via .NET."
type: docs
url: /fr/python-net/guides/get-supported-file-formats/
is_root: false
weight: 130
---


Récupérez rapidement la liste complète des formats de fichiers pris en charge par GroupDocs.Watermark. Cela permet à votre application de vérifier la compatibilité de manière dynamique avant de traiter un document — par exemple, pour valider les fichiers téléchargés par les utilisateurs.

## List supported file formats

`FileType.get_supported_file_types()` renvoie chaque type de fichier pris en charge. Chaque élément expose son `extension` et une description conviviale.

{{< tabs "code-example-get-supported-file-formats">}}
{{< tab "list_supported_formats.py" >}}
```python
from groupdocs.watermark.common import FileType

def list_supported_formats():
    # Énumérez chaque type de fichier que la bibliothèque peut ouvrir
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
