---
title: "Clase DiagramContent"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa un documento Visio."
type: docs
url: /es/python-net/groupdocs.watermark.contents.diagram/diagramcontent/
is_root: false
weight: 10
---


## DiagramContent class

Representa un documento Visio.

Aprende más:
- Add watermarks to diagram documents https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents
- Existing objects in diagram document https://docs.groupdocs.com/display/watermarknet/Existing+objects+in+diagram+document

El tipo DiagramContent expone los siguientes miembros:

### Métodos
| Método | Descripción |
| :- | :- |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | Libera la instancia actual. (heredado de [`Content`](/watermark/python-net/groupdocs.watermark.contents/content/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Encuentra imágenes según los criterios de búsqueda especificados. La búsqueda se realiza en los objetos especificados en [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (heredado de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (heredado de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Encuentra posibles marcas de agua según los criterios de búsqueda especificados. La búsqueda se realiza en los objetos enumerados en [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (heredado de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (heredado de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [header_footer](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramcontent/header_footer/) | El encabezado y pie de página de este DiagramContent. |
| [pages](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramcontent/pages/) | La colección de todas las páginas de este [`DiagramContent`](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramcontent/). |

### Ejemplo

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.diagram import DiagramLoadOptions
import groupdocs.watermark.contents.diagram as gwc_vsdx

load_options = DiagramLoadOptions()
with gw.Watermarker("diagram.vsdx", load_options) as watermarker:
    content = watermarker.get_content()
    for shape in content.pages[0].shapes:
        if shape.text and "© Aspose 2016" in shape.text:
            shape.text = "© GroupDocs 2017"
    watermarker.save("output.vsdx")
```

### Ver también
* module [`groupdocs.watermark.contents.diagram`](/watermark/python-net/groupdocs.watermark.contents.diagram/)
