---
title: "WordProcessingContent clase"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa un documento Word (doc, docx, etc.) donde se puede colocar una marca de agua."
type: docs
url: /es/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/
is_root: false
weight: 10
---


## WordProcessingContent class

Representa un documento Word (doc, docx, etc.) donde se puede colocar una marca de agua.

Aprende más:
- Add watermarks to word processing documents: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents
- Existing objects in word processing document: https://docs.groupdocs.com/display/watermarknet/Existing+objects+in+word+processing+document
- Locking watermark in word processing document: https://docs.groupdocs.com/display/watermarknet/Locking+watermark+in+word+processing+document
- Protecting word processing documents: https://docs.groupdocs.com/display/watermarknet/Protecting+word+processing+documents
- Watermarks in word processing document: https://docs.groupdocs.com/display/watermarknet/Watermarks+in+word+processing+document

El tipo WordProcessingContent expone los siguientes miembros:

### Métodos
| Método | Descripción |
| :- | :- |
| [decrypt](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/decrypt/) | Descifra el documento. |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/encrypt/#password) | Encripta el documento. |
| [encrypt_file](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/encrypt_file/) |  |
| [encrypt_string](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/encrypt_string/) |  |
| [protect](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect/#protection_type-password) | Protege el documento de cambios y establece una contraseña de protección. |
| [protect_file](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect_file/) |  |
| [protect_string](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect_string/) |  |
| [protect_word_processing_protection_type](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect_word_processing_protection_type/) |  |
| [unprotect](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/unprotect/) | Elimina la protección del documento sin importar la contraseña. |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | Libera la instancia actual. (heredado de [`Content`](/watermark/python-net/groupdocs.watermark.contents/content/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Encuentra imágenes según los criterios de búsqueda especificados. La búsqueda se realiza en los objetos especificados en [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (heredado de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (heredado de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Encuentra posibles marcas de agua según los criterios de búsqueda especificados. La búsqueda se realiza en los objetos enumerados en [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (heredado de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (heredado de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [page_count](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/page_count/) | El número de páginas en el documento. |
| [sections](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/sections/) | La colección de todas las secciones de este [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/). |

### Ejemplo

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

load_options = WordProcessingLoadOptions()
with Watermarker("input.docx", load_options) as watermarker:
    # Agregue una marca de agua a una sección en particular o a todas las secciones aquí si es necesario.
    watermarker.save("output.docx")
```

### Ver también
* module [`groupdocs.watermark.contents.word_processing`](/watermark/python-net/groupdocs.watermark.contents.word_processing/)
