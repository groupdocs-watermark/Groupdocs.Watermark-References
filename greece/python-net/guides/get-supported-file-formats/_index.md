---
title: "Λάβετε υποστηριζόμενες μορφές αρχείων"
linkTitle: "Get supported file formats"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Καταγράψτε όλες τις μορφές αρχείων που υποστηρίζονται από το GroupDocs.Watermark για Python μέσω .NET."
type: docs
url: /el/python-net/guides/get-supported-file-formats/
is_root: false
weight: 130
---


Ανακτήστε γρήγορα την πλήρη λίστα των μορφών αρχείων που υποστηρίζονται από το GroupDocs.Watermark. Αυτό επιτρέπει στην εφαρμογή σας να ελέγχει τη συμβατότητα δυναμικά πριν επεξεργαστεί ένα έγγραφο — για παράδειγμα, για να επικυρώσει αρχεία που ανέβηκαν από χρήστες.

## List supported file formats

`FileType.get_supported_file_types()` επιστρέφει κάθε υποστηριζόμενη μορφή αρχείου. Κάθε στοιχείο εμφανίζει την `extension` του και μια φιλική περιγραφή.

{{< tabs "code-example-get-supported-file-formats">}}
{{< tab "list_supported_formats.py" >}}
```python
from groupdocs.watermark.common import FileType

def list_supported_formats():
    # Απαριθμίστε κάθε τύπο αρχείου που μπορεί να ανοίξει η βιβλιοθήκη
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
