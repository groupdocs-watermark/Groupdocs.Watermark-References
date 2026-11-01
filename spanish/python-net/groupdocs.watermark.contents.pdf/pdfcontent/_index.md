---
title: "Clase PdfContent"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa un documento PDF donde se puede colocar una marca de agua."
type: docs
url: /es/python-net/groupdocs.watermark.contents.pdf/pdfcontent/
is_root: false
weight: 100
---


## PdfContent class

Representa un documento PDF donde se puede colocar una marca de agua.

Aprende más:
- [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)
- [Existing objects in PDF document](https://docs.groupdocs.com/display/watermarknet/Existing+objects+in+PDF+document)
- [Rasterize document or page](https://docs.groupdocs.com/display/watermarknet/Rasterize+document+or+page)
- [Watermarks in PDF document](https://docs.groupdocs.com/display/watermarknet/Watermarks+in+PDF+document)

El tipo PdfContent expone los siguientes miembros:

### Métodos
| Método | Descripción |
| :- | :- |
| [decrypt](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/decrypt/) | Descifra el contenido. |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/#password) | Encripta el documento usando la misma contraseña que la contraseña de usuario y la contraseña del propietario. |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/#user_password-owner_password-permissions-crypto_algorithm) | Encripta el contenido. |
| [encrypt_file](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt_file/) |  |
| [encrypt_string](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt_string/) |  |
| [rasterize](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/rasterize/#horizontal_resolution-vertical_resolution-image_format) | Convierte todas las páginas de contenido en imágenes. |
| [rasterize_int32](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/rasterize_int32/) |  |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | Libera la instancia actual. (heredado de [`Content`](/watermark/python-net/groupdocs.watermark.contents/content/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Encuentra imágenes según los criterios de búsqueda especificados. La búsqueda se realiza en los objetos especificados en [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (heredado de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (heredado de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Encuentra posibles marcas de agua según los criterios de búsqueda especificados. La búsqueda se realiza en los objetos enumerados en [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (heredado de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (heredado de [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [attachments](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/attachments/) | La colección de todos los adjuntos de este [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/). |
| [page_margin_type](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/page_margin_type/) | Los márgenes de página pdf que se usarán al añadir la marca de agua. |
| [pages](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/pages/) | La colección de todas las páginas de este [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/). |

### Ejemplo

```python
from groupdocs.watermark import Watermarker

# Cargar un archivo PDF
watermarker = Watermarker("sample.pdf")

# Recuperar el árbol de contenido del PDF
pdf_content = watermarker.get_content()

# Iterar sobre las páginas e imprimir sus tamaños
for page in pdf_content.pages:
    print(page.width, page.height)
```

### Ver también
* module [`groupdocs.watermark.contents.pdf`](/watermark/python-net/groupdocs.watermark.contents.pdf/)
