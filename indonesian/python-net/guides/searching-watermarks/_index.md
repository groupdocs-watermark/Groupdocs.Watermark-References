---
title: "Mencari watermark"
linkTitle: "Searching watermarks"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Temukan watermark teks dan gambar yang mungkin dengan kriteria yang kuat — teks, regex, kemiripan gambar, pemformatan, dan kriteria gabungan — menggunakan GroupDocs.Watermark untuk Python via .NET."
type: docs
url: /id/python-net/guides/searching-watermarks/
is_root: false
weight: 80
---


Gunakan `Watermarker.search()` untuk memindai dokumen guna menemukan objek yang dapat diperlakukan sebagai watermark — termasuk watermark yang ditambahkan oleh alat pihak ketiga. Tanpa kriteria, `search()` mengembalikan subset seperti latar belakang dan objek mengambang; berikan objek kriteria untuk mempersempit hasil.

## Search for possible watermarks

Contoh di bawah ini mencari PDF yang berwatermark dan mencetak teks, halaman, serta ukuran setiap watermark yang mungkin.

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

`document.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) untuk mengunduhnya.

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

Setiap watermark yang mungkin menampilkan `text`, `image_data`, `x`, `y`, `width`, `height`, `rotate_angle`, dan `page_number`.

## Search criteria

Dokumen besar mungkin berisi banyak kandidat. Gunakan kriteria khusus untuk menemukan tepat apa yang Anda butuhkan.

### Text search criteria

Temukan watermark dengan teks tepat.

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

`document.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) untuk mengunduhnya.

{{< /tab >}}
{{< tab "search-by-text.txt" >}}
```text
Found 8 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_by_text/search-by-text.txt)
{{< /tab >}}
{{< /tabs >}}

### Regular expression search criteria

Berikan ekspresi reguler yang telah dikompilasi ke [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/).

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

`document.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) untuk mengunduhnya.

{{< /tab >}}
{{< tab "search-by-regex.txt" >}}
```text
Found 8 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_by_regex/search-by-regex.txt)
{{< /tab >}}
{{< /tabs >}}

Ketika sebuah [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) disediakan, API juga memindai teks dokumen utama bersama dengan bentuk, XObjects, anotasi, dan objek lainnya.

### Image search criteria

Temukan watermark gambar yang secara visual mirip dengan gambar contoh menggunakan perceptual hashing (hash DCT). Kendalikan sensitivitas dengan `max_difference` (0–1).

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

`document.pdf` dan `logo.png` adalah file contoh yang digunakan dalam contoh ini. Unduh [document.pdf](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) dan [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/logo.png).

{{< /tab >}}
{{< tab "search-by-image.txt" >}}
```text
Found 6 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_by_image/search-by-image.txt)
{{< /tab >}}
{{< /tabs >}}

Kriteria gambar lainnya:

- [`ImageColorHistogramSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagecolorhistogramsearchcriteria/) — robust to rotation, scaling, and translation.
- [`ImageThumbnailSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagethumbnailsearchcriteria/) — robust to rotation, scaling, and minor color changes.

### Combined search criteria

Gabungkan kriteria dengan `and_()`, `or_()`, dan `not_()`.

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

`document.pdf` dan `logo.png` adalah file contoh yang digunakan dalam contoh ini. Unduh [document.pdf](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) dan [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/logo.png).

{{< /tab >}}
{{< tab "search-combined.txt" >}}
```text
Found 4 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_combined/search-combined.txt)
{{< /tab >}}
{{< /tabs >}}

### Text formatting search criteria

Temukan watermark berdasarkan pemformatan teks seperti font, ukuran, dan rentang warna.

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

`document.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) untuk mengunduhnya.

{{< /tab >}}
{{< tab "search-by-formatting.txt" >}}
```text
Found 4 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_by_formatting/search-by-formatting.txt)
{{< /tab >}}
{{< /tabs >}}

Mencari berdasarkan **warna dan ukuran** adalah cara paling kuat untuk mencocokkan watermark teks. Anda dapat
juga membatasi `font_name` dan `font_bold`, tetapi font tebal sering disematkan di bawah nama gabungan
nama subset (misalnya `ArialBold`) daripada `Arial` dengan flag tebal terpisah, sehingga sebuah
filter `font_name = "Arial"` mungkin melewatkannya.

## Search watermarks in particular objects

Batasi pencarian ke tipe objek tertentu untuk meningkatkan kinerja — baik secara global melalui `WatermarkerSettings.searchable_objects`, atau per instance melalui `Watermarker.searchable_objects`. Flag berada di `groupdocs.watermark.search.objects`.

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

`document.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) untuk mengunduhnya.

{{< /tab >}}
{{< tab "search-in-objects.txt" >}}
```text
Found 14 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_in_objects/search-in-objects.txt)
{{< /tab >}}
{{< /tabs >}}

### Search for hyperlink watermarks

Batasi pencarian ke hyperlink untuk satu instance [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) :

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

`document.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) untuk mengunduhnya.

{{< /tab >}}
{{< tab "search-hyperlinks.txt" >}}
```text
Found 4 hyperlink watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_hyperlinks/search-hyperlinks.txt)
{{< /tab >}}
{{< /tabs >}}

## Search text while skipping unreadable characters

Aktifkan pencocokan toleran ketika teks berisi karakter yang tidak dapat dibaca di antara huruf.

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

`document.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) untuk mengunduhnya.

{{< /tab >}}
{{< tab "search-skip-unreadable.txt" >}}
```text
Found 8 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_skip_unreadable/search-skip-unreadable.txt)
{{< /tab >}}
{{< /tabs >}}
