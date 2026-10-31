---
title: "Προσθήκη υδατογραφιών κειμένου"
linkTitle: "Add text watermarks"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αυτό το άρθρο δείχνει πώς να προσθέσετε μια υδατογραφία κειμένου σε ένα έγγραφο και να αποθηκεύσετε το αποτέλεσμα με το GroupDocs.Watermark για Python μέσω .NET."
type: docs
url: /el/python-net/guides/add-text/
is_root: false
weight: 40
---


Ένα από τα κύρια χαρακτηριστικά του GroupDocs.Watermark είναι η προσθήκη υδατογραφιών κειμένου σε έγγραφα. Μπορείτε να προσθέσετε υδατογραφίες σε έγγραφα ή εικόνες από τοπική διαδρομή, καθώς και από ρεύμα. Για πλήρη λίστα των υποστηριζόμενων μορφών, ελέγξτε [Supported document formats](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/).

## Add a text watermark

Για να προσθέσετε μια υδατογραφία κειμένου, ακολουθήστε τα παρακάτω βήματα:

1. Ανοίξτε το έγγραφο περνώντας τη διαδρομή του (ή ένα ρεύμα) στην κλάση [Watermarker](https://reference.groupdocs.com/watermark/python-net/) χρησιμοποιώντας ένα μπλοκ `with` ώστε το έγγραφο να απελευθερώνεται αυτόματα.
2. Δημιουργήστε ένα [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) με το επιθυμητό κείμενο και ένα [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/).
3. Στυλιζάτε την υδατογραφία — για παράδειγμα, ορίστε `foreground_color` και την στοίχιση.
4. Καλέστε `add()` για να εφαρμόσετε την υδατογραφία και `save()` για να γράψετε το αποτέλεσμα.

{{< tabs \"code-example-add-text\">}}
{{< tab \"add_text_watermark.py\" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def add_text_watermark():
    with Watermarker("./sample.pdf") as watermarker:
        # Δημιουργήστε την υδατογραφία κειμένου και στυλιζάτε την
        watermark = TextWatermark("Top Secret", Font("Arial", 36.0))
        watermark.foreground_color = Color.red
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER
        watermark.rotate_angle = 45.0
        watermark.opacity = 0.4

        watermarker.add(watermark)
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    add_text_watermark()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` είναι το αρχείο δείγμα που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-text/sample.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 313 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/add-text/add_text_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Εκτελέστε το πρόγραμμα. Ένα νέο έγγραφο με υδατογραφία εμφανίζεται στη καθορισμένη διαδρομή.

## What's next

Το GroupDocs.Watermark προσφέρει πολλές ακόμη δυνατότητες για υδατογραφίες κειμένου — χρώματα φόντου και προσκηνίου, προσαρμοσμένες γραμματοσειρές, διαφάνεια, περιστροφή, επικάλυψη, και απόλυτη ή σχετική τοποθέτηση. Δείτε [Adding text watermarks](https://docs.groupdocs.com/watermark/python-net/adding-text-watermarks/) στον προχωρημένο οδηγό.
