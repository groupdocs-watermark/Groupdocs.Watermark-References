---
title: "Προεπισκόπηση εγγράφου"
linkTitle: "Document preview"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Δημιουργήστε εικόνες προεπισκόπησης (PNG/JPG/BMP) για τις σελίδες εγγράφου χρησιμοποιώντας το GroupDocs.Watermark για Python μέσω .NET."
type: docs
url: /el/python-net/guides/preview/
is_root: false
weight: 110
---


GroupDocs.Watermark μπορεί να αποδίδει τις σελίδες του εγγράφου ως εικόνες ώστε να μπορείτε να εμφανίζετε μικρογραφίες σελίδων χωρίς να ανοίγετε πλήρως το έγγραφο σε προβολέα. Ελέγχετε την απόδοση με μια κλήση επιστροφής `create_page_stream` που παρέχει ένα εγγράψιμο ρεύμα αρχείου για κάθε σελίδα — η βιβλιοθήκη γράφει την εικόνα της σελίδας σε αυτό και το κλείνει για εσάς.

## Generate a document preview

Ορίστε το [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/) με μια κλήση επιστροφής `create_page_stream`, επιλέξτε το `preview_format` και παραθέστε τα `page_numbers` για απόδοση.

{{< tabs \"code-example-preview\">}}
{{< tab \"generate_preview.py\" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # Παρέχετε ένα εγγράψιμο ρεύμα αρχείου για κάθε σελίδα προς απόδοση.
    def create_page_stream(page_number):
        return open(f"./output-page-{page_number}.png", "wb")

    with Watermarker("./sample.pdf") as watermarker:
        options = PreviewOptions(create_page_stream)
        options.preview_format = PreviewFormats.PNG
        options.page_numbers = [1, 2]
        watermarker.generate_preview(options)

if __name__ == "__main__":
    generate_preview()
```
{{< /tab >}}
{{< tab \"sample.pdf\" >}}

`sample.pdf` είναι το δείγμα αρχείου δύο σελίδων που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/preview/sample.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab \"generate-preview-outputs.zip\" >}}
```text
output-page-1.png (600 KB)
output-page-2.png (94 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/preview/generate_preview/generate-preview-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

Οι εικόνες των σελίδων γράφονται στον τρέχοντα φάκελο — ένα PNG ανά ζητούμενη σελίδα. Χρησιμοποιήστε `PreviewFormats.JPEG` ή `PreviewFormats.BMP` για άλλες μορφές και ορίστε `options.width` / `options.height` για να ελέγξετε το μέγεθος απόδοσης.

Η βιβλιοθήκη κλείνει κάθε αρχείο που επιστρέφει το `create_page_stream` μόλις γραφτεί η σελίδα. Για να ενεργήσετε σε μια σελίδα μόλις είναι έτοιμη, περάστε μια δεύτερη κλήση επιστροφής: `PreviewOptions(create_page_stream, release_page_stream)` καλεί το `release_page_stream(page_number, stream)` με το αντικείμενο `create_page_stream` που επιστράφηκε για εκείνη τη σελίδα, μετά τη μεταφορά ολόκληρης της εικόνας. Μια κλήση με ένα όρισμα `release_page_stream(page_number)` λειτουργεί επίσης. Το `create_page_stream` μπορεί επίσης να επιστρέψει ένα `io.BytesIO`: παραμένει ανοιχτό και κρατά την εικόνα της σελίδας μέχρι να το πάρει το `release_page_stream`.

**Use case:** Generate page previews to display in a web app, dashboard, or document-management system without requiring users to download the full file.
