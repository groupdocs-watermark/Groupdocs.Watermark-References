---
title: "Προσαρμογή υδατογραφιών"
linkTitle: "Customize watermarks"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Ρυθμίστε την εμφάνιση και τη θέση της κειμενικής ή εικόνας υδατογραφίας — χρώμα, γραμματοσειρά, περιστροφή, διαφάνεια, μέγεθος και στοίχιση — χρησιμοποιώντας το GroupDocs.Watermark για Python μέσω .NET."
type: docs
url: /el/python-net/guides/customize/
is_root: false
weight: 60
---


Το GroupDocs.Watermark σας επιτρέπει να ελέγχετε πώς φαίνεται μια υδατογραφία και πού εμφανίζεται. Ρυθμίστε το χρώμα, τη γραμματοσειρά, τη στοίχιση, την περιστροφή, τη διαφάνεια και την κλιμάκωση ώστε να ταιριάζει με το στυλ του εγγράφου σας.

## Customize text watermarks

Χρησιμοποιήστε τις ιδιότητες του [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) όπως `foreground_color`, `opacity`, `rotate_angle`, `sizing_type`, `scale_factor`, `horizontal_alignment`, `vertical_alignment`, `x`, `y`, `width`, `height` και `consider_parent_margins`. Το παρακάτω παράδειγμα κλιμακώνει μια υδατογραφία "DRAFT" στη σελίδα, την περιστρέφει 45° και την κάνει ημιδιαφανή.

{{< tabs "code-example-customize">}}
{{< tab "customize_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color, SizingType
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def customize_watermark():
    with Watermarker("./sample.pdf") as watermarker:
        watermark = TextWatermark("DRAFT", Font("Arial", 42.0))
        watermark.foreground_color = Color.dark_orange
        # Κλιμακώστε την υδατογραφία σε σχέση με τη σελίδα και περιστρέψτε την
        watermark.sizing_type = SizingType.SCALE_TO_PARENT_DIMENSIONS
        watermark.scale_factor = 0.7
        watermark.rotate_angle = 45.0
        watermark.opacity = 0.5
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER

        watermarker.add(watermark)
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    customize_watermark()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` είναι το δείγμα αρχείο που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/customize/sample.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 313 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/customize/customize_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

**Use case:** Apply branded or legal disclaimers in a consistent style across pages (for example, "Confidential – Do Not Distribute").

## Customize image watermarks

Τα υδατογραφήματα εικόνας υποστηρίζουν τις ίδιες ιδιότητες τοποθέτησης, περιστροφής και διαφάνειας. Τοποθετήστε ένα λογότυπο, σφραγίδα ή σήμα ακριβώς όπου το χρειάζεστε:

{{< tabs "code-example-customize-image">}}
{{< tab "customize_image_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def customize_image_watermark():
    with Watermarker("./sample.pdf") as watermarker:
        with ImageWatermark("./stamp.png") as watermark:
            watermark.horizontal_alignment = HorizontalAlignment.RIGHT
            watermark.vertical_alignment = VerticalAlignment.TOP
            watermark.rotate_angle = 15.0
            watermark.opacity = 0.8
            watermarker.add(watermark)
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    customize_image_watermark()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` και `stamp.png` είναι τα δείγμα αρχεία που χρησιμοποιούνται σε αυτό το παράδειγμα. Κατεβάστε το [sample.pdf](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/customize/sample.pdf) και το [stamp.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/customize/stamp.png).

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 268 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/customize/customize_image_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}
