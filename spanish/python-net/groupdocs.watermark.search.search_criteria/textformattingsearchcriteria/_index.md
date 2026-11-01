---
title: "Clase TextFormattingSearchCriteria"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa criterios que permiten filtrar por formato de texto."
type: docs
url: /es/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/
is_root: false
weight: 150
---


## TextFormattingSearchCriteria class

Representa criterios que permiten filtrar por formato de texto.

Aprende más:
- Searching watermarks (https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

El tipo TextFormattingSearchCriteria expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/__init__/) | Inicializa una nueva instancia de [`TextFormattingSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/). |

### Métodos
| Método | Descripción |
| :- | :- |
| [and_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/) | Combina este SearchCriteria con otros criterios usando el operador lógico AND. (heredado de [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [and_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_search_criteria/) | (heredado de [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [not_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/) | Niega este SearchCriteria. (heredado de [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [or_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/) | Combina este SearchCriteria con otros criterios usando el operador lógico OR. (heredado de [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [or_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_search_criteria/) | (heredado de [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [background_color_range](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/background_color_range/) | El rango de colores que se utilizan para filtrar marcas de agua por el color de fondo del texto. |
| [font_bold](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/font_bold/) | La fuente utilizada en el formato de texto de marca de agua es negrita. |
| [font_italic](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/font_italic/) | La propiedad font_italic indica si la fuente del texto de marca de agua es cursiva. |
| [font_name](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/font_name/) | El nombre de la fuente utilizada en el posible formato de texto de marca de agua. |
| [font_strikeout](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/font_strikeout/) | La bandera de tachado de fuente para el formato de texto de marca de agua. |
| [font_underline](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/font_underline/) | La bandera de subrayado de fuente que indica si el texto de marca de agua usa subrayado. |
| [foreground_color_range](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/foreground_color_range/) | El rango de colores utilizado para filtrar marcas de agua por el color de primer plano del texto. |
| [max_font_size](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/max_font_size/) | El valor final del tamaño de fuente. |
| [min_font_size](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/min_font_size/) | El valor inicial del tamaño de fuente. |

### Ejemplo

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

### Guides
Guías de tareas que usan `TextFormattingSearchCriteria`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Ver también
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
