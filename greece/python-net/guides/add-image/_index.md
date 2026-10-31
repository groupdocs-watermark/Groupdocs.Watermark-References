---
title: "Προσθήκη υδατογραφιών εικόνας"
linkTitle: "Add image watermarks"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αυτό το άρθρο δείχνει πώς να προσθέσετε μια υδατογραφία εικόνας σε ένα έγγραφο και να αποθηκεύσετε το αποτέλεσμα με το GroupDocs.Watermark για Python μέσω .NET."
type: docs
url: /el/python-net/guides/add-image/
is_root: false
weight: 50
---


Ένα από τα κύρια χαρακτηριστικά του GroupDocs.Watermark είναι η προσθήκη υδατογραφιών εικόνας σε έγγραφα. Μπορείτε να προσθέσετε υδατογραφίες σε έγγραφα ή εικόνες από τοπική διαδρομή, καθώς και από ροή. Για πλήρη λίστα των υποστηριζόμενων μορφών, ελέγξτε [Supported document formats](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/).

## Add an image watermark

Για να προσθέσετε μια υδατογραφία εικόνας, ακολουθήστε τα παρακάτω βήματα:

1. Ανοίξτε το έγγραφο περνώντας τη διαδρομή του (ή μια ροή) στην κλάση [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/).
2. Δημιουργήστε ένα [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/) από το αρχείο εικόνας υδατογραφίας (ή μια ροή).
3. Τοποθετήστε την υδατογραφία — για παράδειγμα, ορίστε `horizontal_alignment`, `vertical_alignment` και `opacity`.
4. Καλέστε `add()` για να εφαρμόσετε την υδατογραφία και `save()` για να γράψετε το αποτέλεσμα.

{{< tabs "code-example-add-image">}}
{{< tab "add_image_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def add_image_watermark():
    with Watermarker("./sample.docx") as watermarker:
        # Δημιουργήστε μια υδατογραφία εικόνας από ένα αρχείο λογότυπου και τοποθετήστε την στο κέντρο
        watermark = ImageWatermark("./logo.png")
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER
        watermark.opacity = 0.7

        watermarker.add(watermark)
        watermarker.save("./output.docx")

if __name__ == "__main__":
    add_image_watermark()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` και `logo.png` είναι τα δείγμα αρχεία που χρησιμοποιούνται σε αυτό το παράδειγμα. Κατεβάστε [sample.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-image/sample.docx) και [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-image/logo.png).

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 127 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/add-image/add_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}

## What's next

Το GroupDocs.Watermark προσφέρει περισσότερες δυνατότητες για υδατογραφίες εικόνας — φόρτωση από ροές, κλιμάκωση, επικάλυψη, και απόλυτη ή σχετική τοποθέτηση. Δείτε [Adding image watermarks](https://docs.groupdocs.com/watermark/python-net/adding-image-watermarks/) στον προχωρημένο οδηγό.
