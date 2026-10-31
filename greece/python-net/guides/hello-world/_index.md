---
title: "Hello, World!"
linkTitle: "Hello, World!"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Ξεκινήστε γρήγορα με το GroupDocs.Watermark για Python μέσω .NET δημιουργώντας και εκτελώντας ένα απλό παράδειγμα."
type: docs
url: /el/python-net/guides/hello-world/
is_root: false
weight: 20
---


## Introduction
Ένα παράδειγμα \"Hello, World!\" είναι συχνά το πρώτο βήμα όταν εξερευνάτε το GroupDocs.Watermark για Python μέσω .NET. Λειτουργεί ως απλό τεστ για να επιβεβαιώσετε ότι το περιβάλλον ανάπτυξής σας είναι σωστά ρυθμισμένο και ότι η βιβλιοθήκη λειτουργεί όπως αναμένεται.

## Overview
Το GroupDocs.Watermark για Python μέσω .NET σας επιτρέπει να προσθέτετε, να αναζητάτε και να αφαιρείτε υδατογραφίες σε διάφορες μορφές εγγράφων. Ένα ευρύ φάσμα [supported formats](https://docs.groupdocs.com/watermark/python-net/getting-started/supported-document-formats/) το καθιστά ευέλικτο για διαφορετικές περιπτώσεις χρήσης.

## How to add a watermark
Τα παρακάτω βήματα δείχνουν πώς να προσθέσετε ένα υδατογράφημα κειμένου σε ένα έγγραφο χρησιμοποιώντας το GroupDocs.Watermark για Python μέσω .NET:

1. Εισάγετε τις κλάσεις `groupdocs.watermark` που χρειάζεστε.
2. Ανοίξτε ένα [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) με τη διαδρομή προς το δείγμα εγγράφου.
3. Δημιουργήστε ένα [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) με το επιθυμητό κείμενο και γραμματοσειρά, και μορφοποιήστε το.
4. Εφαρμόστε το υδατογράφημα με την `add()`.
5. Αποθηκεύστε το αποτέλεσμα.

## Complete example
Το παρακάτω παράδειγμα προσθέτει ένα ημιδιαφανές, διαγώνιο υδατογράφημα κειμένου "Hello, Watermark!" και αποθηκεύει το αποτέλεσμα:

{{< tabs "code-example-hello-world" >}}
{{< tab "hello_world.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

def hello_world():
    # `sample.pdf` είναι το αρχείο δείγμα που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/watermark/python-net/_sample_files/getting-started/hello-world/sample.pdf) για να το κατεβάσετε.
    with Watermarker("./sample.pdf") as watermarker:
        watermark = TextWatermark("Hello, Watermark!", Font("Arial", 36.0))
        watermark.foreground_color = Color.red
        watermark.opacity = 0.5
        watermark.rotate_angle = 45.0
        watermarker.add(watermark)
        watermarker.save("./output.pdf")

    print("Watermark added successfully. Output saved to ./output.pdf.")

if __name__ == "__main__":
    hello_world()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

Το υδατογράφημα αποθηκεύεται ξανά στην ίδια μορφή PDF όπως το `output.pdf`. Για να σφραγίσετε ένα διαφορετικό έγγραφο, αλλάξτε τη διαδρομή εισόδου και την επέκταση εξόδου — το GroupDocs.Watermark αποθηκεύει στη μορφή του εισερχόμενου εγγράφου.

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 315 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/getting-started/hello-world/hello_world/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Αυτή η παρουσίαση αναφέρει το GroupDocs.Watermark για Python μέσω .NET [δείγματα κώδικα](https://github.com/groupdocs-watermark/GroupDocs.Watermark-for-Python-via-.NET/).

## Additional resources
Επισκόπηση Χαρακτηριστικών
