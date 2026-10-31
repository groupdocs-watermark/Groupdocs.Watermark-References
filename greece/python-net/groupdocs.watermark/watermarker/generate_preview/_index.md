---
title: "generate_preview μέθοδος"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Δημιουργεί εικόνες προεπισκόπησης για το έγγραφο."
type: docs
url: /el/python-net/groupdocs.watermark/watermarker/generate_preview/
is_root: false
weight: 1040
---


## generate_preview {#preview_options}

Δημιουργεί εικόνες προεπισκόπησης για το έγγραφο.

```python
def generate_preview(self, preview_options):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| preview_options | `PreviewOptions` | Πρόσθετες επιλογές για χρήση κατά τη δημιουργία εικόνων προεπισκόπησης. |

### Παράδειγμα

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

### Δείτε επίσης
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
