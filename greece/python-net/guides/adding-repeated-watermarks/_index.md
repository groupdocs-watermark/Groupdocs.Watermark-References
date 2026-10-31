---
title: "Προσθήκη επαναλαμβανόμενων υδατογραφιών"
linkTitle: "Repeated watermarks"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Προσθέστε επαναλαμβανόμενες (πλακιδωτές) υδατογραφίες κειμένου ή εικόνας με απόσταση, περιστροφή και μοτίβα χρησιμοποιώντας το GroupDocs.Watermark για Python μέσω .NET."
type: docs
url: /el/python-net/guides/adding-repeated-watermarks/
is_root: false
weight: 70
---


Οι επαναλαμβανόμενες (πλακιδωτές) υδατογραφίες σας επιτρέπουν να καλύψετε ολόκληρες σελίδες με ένα μοτίβο κειμένου ή εικόνων. Μπορείτε να ελέγξετε την απόσταση, την περιστροφή, τις μετατοπίσεις και να επιλέξετε διαφορετικά πρότυπα πλακιδώματος ορίζοντας το `tile_options` στην υδατογραφία.

## Add a repeated text watermark

Το παρακάτω παράδειγμα πλακιδώνει μια διαγώνια υδατογραφία κειμένου σε ολόκληρη τη σελίδα. Τα `line_spacing` και `watermark_spacing` εκφράζονται ως ποσοστό της σελίδας, και το `tile_type` επιλέγει το πρότυπο πλακιδώματος.

{{< tabs \"code-example-adding-repeated-watermarks\">}}
{{< tab \"add_repeated_watermark.py\" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import (
    TextWatermark, Font, Color, TextAlignment,
    TileOptions, TileType, MeasureValue, TileMeasureType,
)

def add_repeated_watermark():
    with Watermarker("./sample.pdf") as watermarker:
        watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 19.0))
        watermark.foreground_color = Color.gray
        watermark.opacity = 0.3
        watermark.rotate_angle = -45.0
        watermark.text_alignment = TextAlignment.CENTER

        # Απόσταση μεταξύ γραμμών και μεταξύ επαναλαμβανόμενων υδατογραφιών, ως ποσοστό της σελίδας
        line_spacing = MeasureValue()
        line_spacing.measure_type = TileMeasureType.PERCENT
        line_spacing.value = 12.0
        watermark_spacing = MeasureValue()
        watermark_spacing.measure_type = TileMeasureType.PERCENT
        watermark_spacing.value = 10.0

        # Πλακιδώστε την υδατογραφία σε ολόκληρη τη σελίδα
        tile_options = TileOptions()
        tile_options.tile_type = TileType.ONE_THIRD_OFFSET
        tile_options.line_spacing = line_spacing
        tile_options.watermark_spacing = watermark_spacing
        watermark.tile_options = tile_options

        watermarker.add(watermark)
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    add_repeated_watermark()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` είναι το αρχείο δείγμα που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/adding-repeated-watermarks/sample.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 379 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/adding-repeated-watermarks/add_repeated_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

Μπορείτε να αντικαταστήσετε το [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) με ένα [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/) για να πλακιδώσετε ένα λογότυπο ή σφραγίδα σε όλη τη σελίδα με τον ίδιο τρόπο — ορίστε το ίδιο `tile_options` στην υδατογραφία εικόνας.

**Use case:** Protect sensitive PDFs by overlaying a tiled "Confidential" text across every page, or reinforce branding by repeating a logo in the background.
