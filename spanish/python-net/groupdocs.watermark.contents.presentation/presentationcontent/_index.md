---
title: "Clase PresentationContent"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa un documento PowerPoint donde se puede colocar una marca de agua."
type: docs
url: /es/python-net/groupdocs.watermark.contents.presentation/presentationcontent/
is_root: false
weight: 60
---


## PresentationContent class

Representa un documento PowerPoint donde se puede colocar una marca de agua.

Aprende más:
- Add watermarks to presentation documents: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents
- Working with slide backgrounds: https://docs.groupdocs.com/display/watermarknet/Working+with+slide+backgrounds

El tipo PresentationContent expone los siguientes miembros:

### Métodos
| Método | Descripción |
| :- | :- |
| [decrypt](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/decrypt/) | Descifra el documento. |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/encrypt/#password) | Encripta el documento. |
| [encrypt_file](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/encrypt_file/) |  |
| [encrypt_string](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/encrypt_string/) |  |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | Libera la instancia actual. (heredado de [`Content`](/watermark/python-net/groupdocs.watermark.contents/content/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Encuentra imágenes según los criterios de búsqueda especificados. La búsqueda se realiza en los objetos especificados en [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (heredado de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (heredado de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Encuentra posibles marcas de agua según los criterios de búsqueda especificados. La búsqueda se realiza en los objetos enumerados en [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (heredado de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (heredado de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [layout_slides](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/layout_slides/) | La colección de todas las diapositivas de diseño de este [`PresentationContent`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/). |
| [master_handout_slide](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/master_handout_slide/) | La diapositiva maestra de folletos de este [`PresentationContent`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/). |
| [master_notes_slide](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/master_notes_slide/) | La diapositiva maestra para todas las diapositivas de notas de este [`PresentationContent`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/). |
| [master_slides](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/master_slides/) | La colección de todas las diapositivas maestras de este PresentationContent. |
| [notes_slide_height](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/notes_slide_height/) | La altura de una diapositiva de notas en puntos. |
| [notes_slide_width](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/notes_slide_width/) | El ancho de una diapositiva de notas en puntos. |
| [slide_height](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/slide_height/) | La altura de una diapositiva en puntos. |
| [slide_width](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/slide_width/) | El ancho de una diapositiva en puntos. |
| [slides](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/slides/) | La colección de todas las diapositivas de este [`PresentationContent`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/). |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.presentation import PresentationLoadOptions

load_options = PresentationLoadOptions()
with Watermarker(r"D:\input.ppt", load_options) as watermarker:
    # Utilice el método add para agregar una marca de agua a una diapositiva específica o a todas las diapositivas.
    watermarker.save(r"D:\output.ppt")
```

### Ver también
* module [`groupdocs.watermark.contents.presentation`](/watermark/python-net/groupdocs.watermark.contents.presentation/)
