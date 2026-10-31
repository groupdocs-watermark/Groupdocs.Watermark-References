---
title: "Αναζήτηση υδατογραφιών"
linkTitle: "Searching watermarks"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Βρείτε πιθανά κειμενικά και εικόνα υδατογραφήματα με ισχυρά κριτήρια — κείμενο, regex, ομοιότητα εικόνας, μορφοποίηση και συνδυασμένα κριτήρια — χρησιμοποιώντας το GroupDocs.Watermark για Python μέσω .NET."
type: docs
url: /el/python-net/guides/searching-watermarks/
is_root: false
weight: 80
---


Χρησιμοποιήστε `Watermarker.search()` για να σαρώσετε ένα έγγραφο για αντικείμενα που μπορούν να θεωρηθούν υδατογραφήματα — συμπεριλαμβανομένων των υδατογραφημάτων που προστέθηκαν από εργαλεία τρίτων. Χωρίς κριτήρια, η `search()` επιστρέφει ένα υποσύνολο όπως φόντα και αιωρούμενα αντικείμενα· περάστε ένα αντικείμενο κριτηρίων για να περιορίσετε τα αποτελέσματα.

## Search for possible watermarks

Το παρακάτω παράδειγμα αναζητά ένα PDF με υδατογράφημα και εκτυπώνει το κείμενο, τη σελίδα και το μέγεθος κάθε πιθανής υδατογραφίας.

{{< tabs "code-example-searching-watermarks">}}
{{< tab "search_watermarks.py" >}}
```python
from groupdocs.watermark import Watermarker

def search_watermarks():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search()
        print(f"Found {len(possible)} possible watermark(s).")
        for wm in possible:
            text = (wm.text or "").strip()
            print(f"- page={wm.page_number} text={text!r} size={round(wm.width)}x{round(wm.height)}")

if __name__ == "__main__":
    search_watermarks()
```
{{< /tab >}}
{{< tab "document.pdf" >}}

`document.pdf` είναι το δείγμα αρχείου που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "search-watermarks.txt" >}}
```text
Found 14 possible watermark(s).
- page=1 text='CONFIDENTIAL' size=268x36
- page=1 text='' size=135x40
- page=1 text='' size=230x69
- page=1 text='' size=460x287
- page=2 text='CONFIDENTIAL' size=268x36
- page=2 text='' size=135x40
- page=3 text='CONFIDENTIAL' size=268x36
- page=3 text='' size=135x40
- page=4 text='CONFIDENTIAL' size=268x36
[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_watermarks/search-watermarks.txt)
{{< /tab >}}
{{< /tabs >}}

Κάθε πιθανή υδατογραφία εκθέτει τα `text`, `image_data`, `x`, `y`, `width`, `height`, `rotate_angle` και `page_number`.

## Search criteria

Μεγάλα έγγραφα μπορεί να περιέχουν πολλούς υποψήφιους. Χρησιμοποιήστε ειδικά κριτήρια για να βρείτε ακριβώς αυτό που χρειάζεστε.

### Text search criteria

Βρείτε υδατογραφήματα με ακριβές κείμενο.

{{< tabs "code-example-search-by-text">}}
{{< tab "search_by_text.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def search_by_text():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_text()
```
{{< /tab >}}
{{< tab "document.pdf" >}}

`document.pdf` είναι το δείγμα αρχείου που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "search-by-text.txt" >}}
```text
Found 8 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_by_text/search-by-text.txt)
{{< /tab >}}
{{< /tabs >}}

### Regular expression search criteria

Περάστε μια συναρτημένη κανονική έκφραση στο [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/).

{{< tabs "code-example-search-by-regex">}}
{{< tab "search_by_regex.py" >}}
```python
import re
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def search_by_regex():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search(TextSearchCriteria(re.compile(r"^CONFIDENTIAL$")))
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_regex()
```
{{< /tab >}}
{{< tab "document.pdf" >}}

`document.pdf` είναι το δείγμα αρχείου που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "search-by-regex.txt" >}}
```text
Found 8 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_by_regex/search-by-regex.txt)
{{< /tab >}}
{{< /tabs >}}

Όταν παρέχεται ένα [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/), το API σαρώσει επίσης το κύριο κείμενο του εγγράφου μαζί με σχήματα, XObjects, σημειώσεις και άλλα αντικείμενα.

### Image search criteria

Βρείτε εικόνα υδατογραφήματα που είναι οπτικά παρόμοια με ένα δείγμα εικόνας χρησιμοποιώντας αντιληπτικό hashing (DCT hash). Ελέγξτε την ευαισθησία με `max_difference` (0–1).

{{< tabs "code-example-search-by-image">}}
{{< tab "search_by_image.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

def search_by_image():
    with Watermarker("./document.pdf") as watermarker:
        criteria = ImageDctHashSearchCriteria("./logo.png")
        criteria.max_difference = 0.9
        possible = watermarker.search(criteria)
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_image()
```
{{< /tab >}}
{{< tab "document.pdf" >}}

`document.pdf` και `logo.png` είναι τα δείγμα αρχεία που χρησιμοποιούνται σε αυτό το παράδειγμα. Κατεβάστε [document.pdf](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) και [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/logo.png).

{{< /tab >}}
{{< tab "search-by-image.txt" >}}
```text
Found 6 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_by_image/search-by-image.txt)
{{< /tab >}}
{{< /tabs >}}

Άλλα κριτήρια εικόνας:

- [`ImageColorHistogramSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagecolorhistogramsearchcriteria/) — robust to rotation, scaling, and translation.
- [`ImageThumbnailSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagethumbnailsearchcriteria/) — robust to rotation, scaling, and minor color changes.

### Combined search criteria

Συνδυάστε κριτήρια με `and_()`, `or_()`, και `not_()`.

{{< tabs "code-example-search-combined">}}
{{< tab "search_combined.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import (
    ImageDctHashSearchCriteria, TextSearchCriteria, RotateAngleSearchCriteria,
)

def search_combined():
    with Watermarker("./document.pdf") as watermarker:
        image_criteria = ImageDctHashSearchCriteria("./logo.png")
        image_criteria.max_difference = 0.9
        text_criteria = TextSearchCriteria("CONFIDENTIAL")
        angle_criteria = RotateAngleSearchCriteria(30, 60)

        combined = image_criteria.or_(text_criteria).and_(angle_criteria)
        possible = watermarker.search(combined)
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_combined()
```
{{< /tab >}}
{{< tab "document.pdf" >}}

`document.pdf` και `logo.png` είναι τα δείγμα αρχεία που χρησιμοποιούνται σε αυτό το παράδειγμα. Κατεβάστε [document.pdf](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) και [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/logo.png).

{{< /tab >}}
{{< tab "search-combined.txt" >}}
```text
Found 4 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_combined/search-combined.txt)
{{< /tab >}}
{{< /tabs >}}

### Text formatting search criteria

Βρείτε υδατογραφήματα με μορφοποίηση κειμένου όπως γραμματοσειρά, μέγεθος και εύρη χρώματος.

{{< tabs "code-example-search-by-formatting">}}
{{< tab "search_by_formatting.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextFormattingSearchCriteria, ColorRange

def search_by_formatting():
    with Watermarker("./document.pdf") as watermarker:
        criteria = TextFormattingSearchCriteria()
        criteria.foreground_color_range = ColorRange()
        criteria.foreground_color_range.min_hue = -15
        criteria.foreground_color_range.max_hue = 15
        criteria.foreground_color_range.min_brightness = 0.01
        criteria.foreground_color_range.max_brightness = 0.99
        criteria.min_font_size = 19
        criteria.max_font_size = 42

        possible = watermarker.search(criteria)
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_formatting()
```
{{< /tab >}}
{{< tab "document.pdf" >}}

`document.pdf` είναι το δείγμα αρχείου που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "search-by-formatting.txt" >}}
```text
Found 4 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_by_formatting/search-by-formatting.txt)
{{< /tab >}}
{{< /tabs >}}

Η αναζήτηση με **color and size** είναι ο πιο αξιόπιστος τρόπος για να ταιριάξετε ένα υδατογράφημα κειμένου. Μπορείτε
επίσης περιορίζετε `font_name` και `font_bold`, αλλά οι έντονες γραμματοσειρές συχνά είναι ενσωματωμένες κάτω από ένα συγχωνευμένο
όνομα υποσυνόλου (για παράδειγμα `ArialBold`) αντί για `Arial` με ξεχωριστή έντονη σημαία, έτσι ένα
Το φίλτρο `font_name = "Arial"` μπορεί να τα παραλείψει.

## Search watermarks in particular objects

Περιορίστε την αναζήτηση σε συγκεκριμένους τύπους αντικειμένων για να βελτιώσετε την απόδοση — είτε παγκοσμίως μέσω `WatermarkerSettings.searchable_objects`, είτε ανά εμφάνιση μέσω `Watermarker.searchable_objects`. Οι σημαίες βρίσκονται στο `groupdocs.watermark.search.objects`.

{{< tabs "code-example-search-in-objects">}}
{{< tab "search_in_objects.py" >}}
```python
from groupdocs.watermark import Watermarker, WatermarkerSettings
from groupdocs.watermark.search.objects import (
    SearchableObjects, WordProcessingSearchableObjects, PdfSearchableObjects,
)

def search_in_objects():
    settings = WatermarkerSettings()
    settings.searchable_objects = SearchableObjects(
        word_processing_searchable_objects=WordProcessingSearchableObjects.HYPERLINKS | WordProcessingSearchableObjects.TEXT,
        pdf_searchable_objects=PdfSearchableObjects.ALL,
    )

    with Watermarker("./document.pdf", settings) as watermarker:
        possible = watermarker.search()
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_in_objects()
```
{{< /tab >}}
{{< tab "document.pdf" >}}

`document.pdf` είναι το δείγμα αρχείου που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "search-in-objects.txt" >}}
```text
Found 14 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_in_objects/search-in-objects.txt)
{{< /tab >}}
{{< /tabs >}}

### Search for hyperlink watermarks

Περιορίστε την αναζήτηση σε υπερσυνδέσμους για μια μοναδική παρουσία [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) .

{{< tabs "code-example-search-hyperlinks">}}
{{< tab "search_hyperlinks.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.objects import PdfSearchableObjects

def search_hyperlinks():
    with Watermarker("./document.pdf") as watermarker:
        watermarker.searchable_objects.pdf_searchable_objects = PdfSearchableObjects.HYPERLINKS
        possible = watermarker.search()
        print("Found", len(possible), "hyperlink watermark(s)")

if __name__ == "__main__":
    search_hyperlinks()
```
{{< /tab >}}
{{< tab "document.pdf" >}}

`document.pdf` είναι το δείγμα αρχείου που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "search-hyperlinks.txt" >}}
```text
Found 4 hyperlink watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_hyperlinks/search-hyperlinks.txt)
{{< /tab >}}
{{< /tabs >}}

## Search text while skipping unreadable characters

Ενεργοποιήστε την ανεκτική αντιστοίχιση όταν το κείμενο περιέχει μη αναγνώσιμους χαρακτήρες μεταξύ των γραμμάτων.

{{< tabs "code-example-search-skip-unreadable">}}
{{< tab "search_skip_unreadable.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def search_skip_unreadable():
    with Watermarker("./document.pdf") as watermarker:
        criterion = TextSearchCriteria("CONFIDENTIAL")
        criterion.skip_unreadable_characters = True
        possible = watermarker.search(criterion)
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_skip_unreadable()
```
{{< /tab >}}
{{< tab "document.pdf" >}}

`document.pdf` είναι το δείγμα αρχείου που χρησιμοποιείται σε αυτό το παράδειγμα. Κάντε κλικ [εδώ](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) για να το κατεβάσετε.

{{< /tab >}}
{{< tab "search-skip-unreadable.txt" >}}
```text
Found 8 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_skip_unreadable/search-skip-unreadable.txt)
{{< /tab >}}
{{< /tabs >}}
