---
title: "Ενημέρωση υδατογραφιών"
linkTitle: "Update watermarks"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Αναζητήστε υπάρχουσες υδατογραφίες κειμένου ή εικόνας και ενημερώστε τις χρησιμοποιώντας το GroupDocs.Watermark για Python μέσω .NET."
type: docs
url: /el/python-net/guides/update/
is_root: false
weight: 90
---


Μπορείτε να αναζητήσετε σε ένα έγγραφο υπάρχουσες υδατογραφίες και να τις τροποποιήσετε επί τόπου — για παράδειγμα, να αντικαταστήσετε το κείμενο μιας υδατογραφίας κειμένου ή να ανταλλάξετε την εικόνα μιας υδατογραφίας εικόνας.

## Update text watermarks

Αναζητήστε μια υδατογραφία με βάση το κειμενικό της περιεχόμενο, στη συνέχεια εκχωρήστε μια νέα τιμή σε κάθε αντιστοίχιση. Το παρακάτω παράδειγμα ανοίγει ένα έγγραφο που ήδη περιέχει μια υδατογραφία "CONFIDENTIAL" και την αντικαθιστά με "APPROVED".

{{< tabs "code-example-update">}}
{{< tab "update_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def update_watermark():
    with Watermarker("./watermarked-document.pdf") as watermarker:
        # Βρείτε τις υδατογραφίες των οποίων το κείμενο ταιριάζει με τα κριτήρια
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        print("Found", len(possible), "possible watermark(s).")
        for watermark in possible:
            try:
                watermark.text = "APPROVED"
            except Exception:
                # Ορισμένες εντοπισμένες οντότητες δεν υποστηρίζουν επεξεργασία κειμένου — παραλείψτε τις
                pass
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    update_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.pdf" >}}

`watermarked-document.pdf` είναι το αρχείο δείγμα που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/watermarked-document.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 444 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/update/update_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

## Update image watermarks

Οι υδατογραφίες εικόνας μπορούν να εντοπιστούν με αντιληπτικό hashing ([`ImageDctHashSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/)) και να ενημερωθούν εκχωρώντας νέα bytes στο `image_data`. Το παρακάτω παράδειγμα εντοπίζει την υδατογραφία λογότυπου και την αντικαθιστά με μια σφραγίδα "APPROVED".

{{< tabs "code-example-update-image">}}
{{< tab "update_image_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

def update_image_watermark():
    with Watermarker("./watermarked-document.docx") as watermarker:
        criteria = ImageDctHashSearchCriteria("./logo.png")
        criteria.max_difference = 0.9
        possible = watermarker.search(criteria)
        with open("./stamp.png", "rb") as f:
            image_data = f.read()
        for watermark in possible:
            try:
                watermark.image_data = image_data
            except Exception:
                # Ορισμένες εντοπισμένες οντότητες δεν υποστηρίζουν επεξεργασία εικόνας — παραλείψτε τις
                pass
        watermarker.save("./output.docx")

if __name__ == "__main__":
    update_image_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.docx" >}}

`watermarked-document.docx`, `logo.png` και `stamp.png` είναι τα δείγμα αρχεία που χρησιμοποιούνται σε αυτό το παράδειγμα. Κατεβάστε [watermarked-document.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/watermarked-document.docx), [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/logo.png) και [stamp.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/stamp.png).

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 19 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/update/update_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}
