---
title: "Ricerca dei filigrane"
linkTitle: "Searching watermarks"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Trova possibili filigrane di testo e immagine con criteri potenti — testo, regex, somiglianza delle immagini, formattazione e criteri combinati — utilizzando GroupDocs.Watermark per Python tramite .NET."
type: docs
url: /it/python-net/guides/searching-watermarks/
is_root: false
weight: 80
---


Usa `Watermarker.search()` per analizzare un documento alla ricerca di oggetti che possono essere trattati come filigrane — incluse le filigrane aggiunte da strumenti di terze parti. Senza criteri, `search()` restituisce un sottoinsieme come sfondi e oggetti fluttuanti; passa un oggetto criterio per restringere i risultati.

## Search for possible watermarks

L'esempio seguente ricerca un PDF con filigrana e stampa il testo, la pagina e le dimensioni di ogni possibile filigrana.

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

`document.pdf` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) per scaricarlo.

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

Ogni possibile filigrana espone `text`, `image_data`, `x`, `y`, `width`, `height`, `rotate_angle` e `page_number`.

## Search criteria

I documenti di grandi dimensioni possono contenere molti candidati. Usa criteri dedicati per trovare esattamente ciò di cui hai bisogno.

### Text search criteria

Trova le filigrane per testo esatto.

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

`document.pdf` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) per scaricarlo.

{{< /tab >}}
{{< tab "search-by-text.txt" >}}
```text
Found 8 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_by_text/search-by-text.txt)
{{< /tab >}}
{{< /tabs >}}

### Regular expression search criteria

Passa un'espressione regolare compilata a [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/).

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

`document.pdf` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) per scaricarlo.

{{< /tab >}}
{{< tab "search-by-regex.txt" >}}
```text
Found 8 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_by_regex/search-by-regex.txt)
{{< /tab >}}
{{< /tabs >}}

Quando viene fornito un [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/), l'API analizza anche il testo principale del documento insieme a forme, XObject, annotazioni e altri oggetti.

### Image search criteria

Trova le filigrane immagine che sono visivamente simili a un'immagine di esempio usando l'hashing percettivo (hash DCT). Controlla la sensibilità con `max_difference` (0–1).

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

`document.pdf` e `logo.png` sono i file di esempio utilizzati in questo esempio. Scarica [document.pdf](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) e [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/logo.png).

{{< /tab >}}
{{< tab "search-by-image.txt" >}}
```text
Found 6 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_by_image/search-by-image.txt)
{{< /tab >}}
{{< /tabs >}}

Altri criteri immagine:

- [`ImageColorHistogramSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagecolorhistogramsearchcriteria/) — robust to rotation, scaling, and translation.
- [`ImageThumbnailSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagethumbnailsearchcriteria/) — robust to rotation, scaling, and minor color changes.

### Combined search criteria

Combina i criteri con `and_()`, `or_()`, e `not_()`.

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

`document.pdf` e `logo.png` sono i file di esempio utilizzati in questo esempio. Scarica [document.pdf](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) e [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/logo.png).

{{< /tab >}}
{{< tab "search-combined.txt" >}}
```text
Found 4 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_combined/search-combined.txt)
{{< /tab >}}
{{< /tabs >}}

### Text formatting search criteria

Trova le filigrane tramite la formattazione del testo, come carattere, dimensione e intervalli di colore.

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

`document.pdf` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) per scaricarlo.

{{< /tab >}}
{{< tab "search-by-formatting.txt" >}}
```text
Found 4 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_by_formatting/search-by-formatting.txt)
{{< /tab >}}
{{< /tabs >}}

La ricerca per **colore e dimensione** è il metodo più robusto per corrispondere a una filigrana di testo. È possibile
restringere anche `font_name` e `font_bold`, ma i caratteri in grassetto sono spesso incorporati sotto un nome di sottoinsieme fuso
nome di sottoinsieme (ad esempio `ArialBold`) anziché `Arial` con un flag di grassetto separato, quindi un
Il filtro `font_name = "Arial"` potrebbe non rilevarli.

## Search watermarks in particular objects

Limita la ricerca a tipi di oggetto specifici per migliorare le prestazioni — sia globalmente tramite `WatermarkerSettings.searchable_objects`, sia per istanza tramite `Watermarker.searchable_objects`. I flag si trovano in `groupdocs.watermark.search.objects`.

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

`document.pdf` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) per scaricarlo.

{{< /tab >}}
{{< tab "search-in-objects.txt" >}}
```text
Found 14 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_in_objects/search-in-objects.txt)
{{< /tab >}}
{{< /tabs >}}

### Search for hyperlink watermarks

Limita la ricerca ai collegamenti ipertestuali per una singola istanza di [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/):

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

`document.pdf` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) per scaricarlo.

{{< /tab >}}
{{< tab "search-hyperlinks.txt" >}}
```text
Found 4 hyperlink watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_hyperlinks/search-hyperlinks.txt)
{{< /tab >}}
{{< /tabs >}}

## Search text while skipping unreadable characters

Abilita la corrispondenza tollerante quando il testo contiene caratteri illeggibili tra le lettere.

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

`document.pdf` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) per scaricarlo.

{{< /tab >}}
{{< tab "search-skip-unreadable.txt" >}}
```text
Found 8 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_skip_unreadable/search-skip-unreadable.txt)
{{< /tab >}}
{{< /tabs >}}
