---
title: "Clase SpreadsheetContent"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa un documento de Excel donde se puede colocar una marca de agua."
type: docs
url: /es/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/
is_root: false
weight: 80
---


## SpreadsheetContent class

Representa un documento de Excel donde se puede colocar una marca de agua.

Aprende más:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents
- https://docs.groupdocs.com/display/watermarknet/Shapes+in+spreadsheet+document
- https://docs.groupdocs.com/display/watermarknet/Working+with+spreadsheet+document+attachments
- https://docs.groupdocs.com/display/watermarknet/Working+with+worksheet+backgrounds
- https://docs.groupdocs.com/display/watermarknet/Working+with+worksheet+headers+and+footers

El tipo SpreadsheetContent expone los siguientes miembros:

### Métodos
| Método | Descripción |
| :- | :- |
| [decrypt](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/decrypt/) | Descifra el documento. |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/encrypt/#password) | Encripta el contenido. |
| [encrypt_file](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/encrypt_file/) |  |
| [encrypt_string](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/encrypt_string/) |  |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | Libera la instancia actual. (heredado de [`Content`](/watermark/python-net/groupdocs.watermark.contents/content/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Encuentra imágenes según los criterios de búsqueda especificados. La búsqueda se realiza en los objetos especificados en [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (heredado de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (heredado de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Encuentra posibles marcas de agua según los criterios de búsqueda especificados. La búsqueda se realiza en los objetos enumerados en [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (heredado de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (heredado de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [worksheets](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/worksheets/) | La colección de todas las hojas de cálculo de este [`SpreadsheetContent`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/). |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions

load_options = SpreadsheetLoadOptions()
with Watermarker(r"D:\input.xls", load_options) as watermarker:
    # Utilice el método add para agregar una marca de agua a una hoja de cálculo específica o a todas.
    watermarker.save(r"D:\output.xls")
```

### Ver también
* module [`groupdocs.watermark.contents.spreadsheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/)
