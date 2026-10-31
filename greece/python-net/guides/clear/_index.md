---
title: "Καθαρισμός υδατογραφιών"
linkTitle: "Clear watermarks"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αναζητήστε και αφαιρέστε υπάρχουσες υδατογραφίες κειμένου ή εικόνας χρησιμοποιώντας το GroupDocs.Watermark για Python μέσω .NET."
type: docs
url: /el/python-net/guides/clear/
is_root: false
weight: 100
---


Μπορείτε να αναζητήσετε σε ένα έγγραφο υπάρχουσες υδατογραφίες και να τις αφαιρέσετε. Το παρακάτω παράδειγμα εντοπίζει μια υδατογραφία κειμένου "CONFIDENTIAL" και την αφαιρεί, δημιουργώντας ένα καθαρό έγγραφο.

## Remove text watermarks

Επανάληψη των αποτελεσμάτων αναζήτησης σε αντίστροφη σειρά ώστε η αφαίρεση ενός στοιχείου να μην μετατοπίζει τους δείκτες που απομένουν, και κλήση της `remove()` για κάθε αντιστοίχιση.

{{< tabs "code-example-clear">}}
{{< tab "clear_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def clear_watermark():
    with Watermarker("./watermarked-document.pdf") as watermarker:
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        # Αφαιρέστε σε αντίστροφη σειρά ώστε οι δείκτες να παραμένουν έγκυροι καθώς τα στοιχεία διαγράφονται
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    clear_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.pdf" >}}

`watermarked-document.pdf` είναι το αρχείο δείγμα που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/watermarked-document.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 360 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/clear/clear_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

**Use case:** Remove outdated labels such as "Draft" or "Internal Use Only" before sharing a document externally.

## Remove image watermarks

Οι υδατογραφίες εικόνας μπορούν να εντοπιστούν με αντιληπτικό hashing και να αφαιρεθούν με τον ίδιο τρόπο:

{{< tabs "code-example-clear-image">}}
{{< tab "clear_image_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

def clear_image_watermark():
    with Watermarker("./watermarked-document.docx") as watermarker:
        criteria = ImageDctHashSearchCriteria("./logo.png")
        criteria.max_difference = 0.9
        possible = watermarker.search(criteria)
        # Αφαιρέστε σε αντίστροφη σειρά ώστε οι δείκτες να παραμένουν έγκυροι καθώς τα στοιχεία διαγράφονται
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.docx")

if __name__ == "__main__":
    clear_image_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.docx" >}}

`watermarked-document.docx` και `logo.png` είναι τα αρχεία δείγμα που χρησιμοποιούνται σε αυτό το παράδειγμα. Κατεβάστε το [watermarked-document.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/watermarked-document.docx) και το [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/logo.png).

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 13 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/clear/clear_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}
