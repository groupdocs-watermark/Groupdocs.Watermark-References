---
title: "Buscar marcas de agua"
linkTitle: "Searching watermarks"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Encuentra posibles marcas de agua de texto e imagen con criterios potentes — texto, expresiones regulares, similitud de imagen, formato y criterios combinados — usando GroupDocs.Watermark para Python a través de .NET."
type: docs
url: /es/python-net/guides/searching-watermarks/
is_root: false
weight: 80
---


Utiliza `Watermarker.search()` para escanear un documento en busca de objetos que pueden tratarse como marcas de agua — incluidas las marcas de agua añadidas por herramientas de terceros. Sin criterios, `search()` devuelve un subconjunto como fondos y objetos flotantes; pasa un objeto de criterios para limitar los resultados.

## Search for possible watermarks

El ejemplo a continuación busca en un PDF con marca de agua y muestra el texto, la página y el tamaño de cada posible marca de agua.

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

`document.pdf` es el archivo de muestra utilizado en este ejemplo. Haz clic [aquí](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) para descargarlo.

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

Cada posible marca de agua expone `text`, `image_data`, `x`, `y`, `width`, `height`, `rotate_angle` y `page_number`.

## Search criteria

Los documentos grandes pueden contener muchos candidatos. Utiliza criterios dedicados para encontrar exactamente lo que necesitas.

### Text search criteria

Encuentra marcas de agua por texto exacto.

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

`document.pdf` es el archivo de muestra utilizado en este ejemplo. Haz clic [aquí](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) para descargarlo.

{{< /tab >}}
{{< tab "search-by-text.txt" >}}
```text
Found 8 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_by_text/search-by-text.txt)
{{< /tab >}}
{{< /tabs >}}

### Regular expression search criteria

Pasa una expresión regular compilada a [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/).

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

`document.pdf` es el archivo de muestra utilizado en este ejemplo. Haz clic [aquí](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) para descargarlo.

{{< /tab >}}
{{< tab "search-by-regex.txt" >}}
```text
Found 8 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_by_regex/search-by-regex.txt)
{{< /tab >}}
{{< /tabs >}}

Cuando se proporciona un [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/), la API también escanea el texto principal del documento junto con formas, XObjects, anotaciones y otros objetos.

### Image search criteria

Encuentra marcas de agua de imagen que sean visualmente similares a una imagen de muestra usando hashing perceptual (hash DCT). Controla la sensibilidad con `max_difference` (0–1).

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

`document.pdf` y `logo.png` son los archivos de muestra utilizados en este ejemplo. Descargue [document.pdf](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) y [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/logo.png).

{{< /tab >}}
{{< tab "search-by-image.txt" >}}
```text
Found 6 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_by_image/search-by-image.txt)
{{< /tab >}}
{{< /tabs >}}

Otros criterios de imagen:

- [`ImageColorHistogramSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagecolorhistogramsearchcriteria/) — robust to rotation, scaling, and translation.
- [`ImageThumbnailSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagethumbnailsearchcriteria/) — robust to rotation, scaling, and minor color changes.

### Combined search criteria

Combine criterios con `and_()`, `or_()`, y `not_()`.

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

`document.pdf` y `logo.png` son los archivos de muestra utilizados en este ejemplo. Descargue [document.pdf](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) y [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/logo.png).

{{< /tab >}}
{{< tab "search-combined.txt" >}}
```text
Found 4 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_combined/search-combined.txt)
{{< /tab >}}
{{< /tabs >}}

### Text formatting search criteria

Encuentre marcas de agua por formato de texto como fuente, tamaño y rangos de color.

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

`document.pdf` es el archivo de muestra utilizado en este ejemplo. Haz clic [aquí](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) para descargarlo.

{{< /tab >}}
{{< tab "search-by-formatting.txt" >}}
```text
Found 4 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_by_formatting/search-by-formatting.txt)
{{< /tab >}}
{{< /tabs >}}

Buscar por **color y tamaño** es la forma más robusta de coincidir con una marca de agua de texto. Puede
también restrinja `font_name` y `font_bold`, pero las fuentes en negrita a menudo están incrustadas bajo un nombre combinado
de subconjunto (por ejemplo `ArialBold`) en lugar de `Arial` con una bandera de negrita separada, por lo que un
el filtro `font_name = \"Arial\"` puede omitirlos.

## Search watermarks in particular objects

Limite la búsqueda a tipos de objetos específicos para mejorar el rendimiento — ya sea globalmente a través de `WatermarkerSettings.searchable_objects`, o por instancia mediante `Watermarker.searchable_objects`. Las banderas se encuentran en `groupdocs.watermark.search.objects`.

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

`document.pdf` es el archivo de muestra utilizado en este ejemplo. Haz clic [aquí](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) para descargarlo.

{{< /tab >}}
{{< tab "search-in-objects.txt" >}}
```text
Found 14 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_in_objects/search-in-objects.txt)
{{< /tab >}}
{{< /tabs >}}

### Search for hyperlink watermarks

Restrinja la búsqueda a hipervínculos para una única instancia de [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/):

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

`document.pdf` es el archivo de muestra utilizado en este ejemplo. Haz clic [aquí](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) para descargarlo.

{{< /tab >}}
{{< tab "search-hyperlinks.txt" >}}
```text
Found 4 hyperlink watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_hyperlinks/search-hyperlinks.txt)
{{< /tab >}}
{{< /tabs >}}

## Search text while skipping unreadable characters

Habilitar la coincidencia tolerante cuando el texto contiene caracteres ilegibles entre letras.

{{< tabs \"code-example-search-skip-unreadable\">}}
{{< tab \"search_skip_unreadable.py\" >}}
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

`document.pdf` es el archivo de muestra utilizado en este ejemplo. Haz clic [aquí](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) para descargarlo.

{{< /tab >}}
{{< tab \"search-skip-unreadable.txt\" >}}
```text
Found 8 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_skip_unreadable/search-skip-unreadable.txt)
{{< /tab >}}
{{< /tabs >}}
