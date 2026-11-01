---
title: "Filigranları arama"
linkTitle: "Searching watermarks"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "GroupDocs.Watermark for Python via .NET kullanarak güçlü kriterlerle olası metin ve görüntü filigranlarını bulun — metin, regex, görüntü benzerliği, biçimlendirme ve birleşik kriterler —."
type: docs
url: /tr/python-net/guides/searching-watermarks/
is_root: false
weight: 80
---


Bir belgeyi filigran olarak değerlendirilebilecek nesneler için taramak üzere `Watermarker.search()` kullanın — üçüncü taraf araçlar tarafından eklenen filigranlar dahil. Kriter olmadan, `search()` arka planlar ve yüzen nesneler gibi bir alt küme döndürür; sonuçları daraltmak için bir kriter nesnesi geçirin.

## Search for possible watermarks

Aşağıdaki örnek, filigranlı bir PDF'i arar ve her olası filigranın metnini, sayfasını ve boyutunu yazdırır.

{{< tabs \"code-example-searching-watermarks\">}}
{{< tab \"search_watermarks.py\" >}}
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
{{< tab \"document.pdf\" >}}

`document.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) tıklayın.

{{< /tab >}}
{{< tab \"search-watermarks.txt\" >}}
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

Her olası filigran `text`, `image_data`, `x`, `y`, `width`, `height`, `rotate_angle` ve `page_number` özelliklerini sunar.

## Search criteria

Büyük belgeler çok sayıda aday içerebilir. Tam olarak ihtiyacınız olanı bulmak için özel kriterler kullanın.

### Text search criteria

Filigranları tam metinle bulun.

{{< tabs \"code-example-search-by-text\">}}
{{< tab \"search_by_text.py\" >}}
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
{{< tab \"document.pdf\" >}}

`document.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) tıklayın.

{{< /tab >}}
{{< tab \"search-by-text.txt\" >}}
```text
Found 8 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_by_text/search-by-text.txt)
{{< /tab >}}
{{< /tabs >}}

### Regular expression search criteria

Derlenmiş bir düzenli ifadeyi [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) öğesine geçirin.

{{< tabs \"code-example-search-by-regex\">}}
{{< tab \"search_by_regex.py\" >}}
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
{{< tab \"document.pdf\" >}}

`document.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) tıklayın.

{{< /tab >}}
{{< tab \"search-by-regex.txt\" >}}
```text
Found 8 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_by_regex/search-by-regex.txt)
{{< /tab >}}
{{< /tabs >}}

Bir [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) sağlandığında, API ana belge metnini şekiller, XObject'ler, ek açıklamalar ve diğer nesnelerle birlikte tarar.

### Image search criteria

Algısal karma (DCT hash) kullanarak örnek bir görüntüye görsel olarak benzer görüntü filigranlarını bulun. Hassasiyeti `max_difference` (0–1) ile kontrol edin.

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
{{< tab \"document.pdf\" >}}

`document.pdf` ve `logo.png` bu örnekte kullanılan örnek dosyalardır. [document.pdf](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) ve [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/logo.png) dosyalarını indirin.

{{< /tab >}}
{{< tab "search-by-image.txt" >}}
```text
Found 6 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_by_image/search-by-image.txt)
{{< /tab >}}
{{< /tabs >}}

Diğer görüntü kriterleri:

- [`ImageColorHistogramSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagecolorhistogramsearchcriteria/) — robust to rotation, scaling, and translation.
- [`ImageThumbnailSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagethumbnailsearchcriteria/) — robust to rotation, scaling, and minor color changes.

### Combined search criteria

Kriterleri `and_()`, `or_()`, ve `not_()` ile birleştirin.

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
{{< tab \"document.pdf\" >}}

`document.pdf` ve `logo.png` bu örnekte kullanılan örnek dosyalardır. [document.pdf](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) ve [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/logo.png) dosyalarını indirin.

{{< /tab >}}
{{< tab "search-combined.txt" >}}
```text
Found 4 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_combined/search-combined.txt)
{{< /tab >}}
{{< /tabs >}}

### Text formatting search criteria

Yazı tipi, boyut ve renk aralıkları gibi metin biçimlendirmesine göre filigranları bulun.

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
{{< tab \"document.pdf\" >}}

`document.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) tıklayın.

{{< /tab >}}
{{< tab "search-by-formatting.txt" >}}
```text
Found 4 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_by_formatting/search-by-formatting.txt)
{{< /tab >}}
{{< /tabs >}}

Metin filigranını eşleştirmenin en sağlam yolu **renk ve boyut** ile aramaktır. Şunu yapabilirsiniz
aynı zamanda `font_name` ve `font_bold` kısıtlamaları ekleyebilirsiniz, ancak kalın yazı tipleri genellikle birleştirilmiş bir
alt küme adı (örneğin `ArialBold`) olarak bulunur, ayrı bir kalın bayrağı olan `Arial` yerine, bu yüzden bir
`font_name = \"Arial\"` filtresi onları kaçırabilir.

## Search watermarks in particular objects

Aramayı belirli nesne türleriyle sınırlayarak performansı artırın — ya `WatermarkerSettings.searchable_objects` aracılığıyla global olarak, ya da `Watermarker.searchable_objects` üzerinden örnek bazında. Bayraklar `groupdocs.watermark.search.objects` içinde bulunur.

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
{{< tab \"document.pdf\" >}}

`document.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) tıklayın.

{{< /tab >}}
{{< tab "search-in-objects.txt" >}}
```text
Found 14 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_in_objects/search-in-objects.txt)
{{< /tab >}}
{{< /tabs >}}

### Search for hyperlink watermarks

Tek bir [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) örneği için aramayı yalnızca köprülerle sınırlayın:

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
{{< tab \"document.pdf\" >}}

`document.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) tıklayın.

{{< /tab >}}
{{< tab "search-hyperlinks.txt" >}}
```text
Found 4 hyperlink watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_hyperlinks/search-hyperlinks.txt)
{{< /tab >}}
{{< /tabs >}}

## Search text while skipping unreadable characters

Metin harfler arasında okunamayan karakterler içerdiğinde toleranslı eşleşmeyi etkinleştirin.

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
{{< tab \"document.pdf\" >}}

`document.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) tıklayın.

{{< /tab >}}
{{< tab "search-skip-unreadable.txt" >}}
```text
Found 8 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_skip_unreadable/search-skip-unreadable.txt)
{{< /tab >}}
{{< /tabs >}}
