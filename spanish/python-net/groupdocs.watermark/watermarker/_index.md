---
title: "Clase Watermarker"
second_title: "Referencias de la API de GroupDocs.Watermark para Python a través de .NET"
description: "Representa una clase para la gestión de marcas de agua en un documento."
type: docs
url: /es/python-net/groupdocs.watermark/watermarker/
is_root: false
weight: 60
---


## Watermarker class

Representa una clase para la gestión de marcas de agua en un documento.

Cargue y guarde el contenido de cualquier formato compatible.

El tipo Watermarker expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#file_path) | Inicializa una nueva instancia de Watermarker con la ruta de documento especificada. |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#file_path-options) | Inicializa una nueva instancia de Watermarker con la ruta de documento especificada y opciones de carga. |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#file_path-settings) | Inicializa un Watermarker con la ruta de documento y la configuración especificadas. |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#file_path-options-settings) | Inicializa una nueva instancia de Watermarker con la ruta de documento, opciones de carga y configuración especificadas. |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#document) | Inicializa una nueva instancia de la clase Watermarker con el flujo especificado. |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#document-options) | Inicializa una nueva instancia de Watermarker con el flujo especificado y opciones de carga. |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#document-settings) | Inicializa una nueva instancia de Watermarker con el flujo especificado y la configuración. |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#document-options-settings) | Inicializa una nueva instancia de la clase [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) con el flujo especificado, opciones de carga y configuración. |

### Métodos
| Método | Descripción |
| :- | :- |
| [add](/watermark/python-net/groupdocs.watermark/watermarker/add/#watermark) | Añade una marca de agua al documento cargado. |
| [add](/watermark/python-net/groupdocs.watermark/watermarker/add/#watermark-options) | Añade una marca de agua al documento cargado usando opciones de marca de agua. |
| [add_watermark](/watermark/python-net/groupdocs.watermark/watermarker/add_watermark/) |  |
| [dispose](/watermark/python-net/groupdocs.watermark/watermarker/dispose/) | Libera la instancia actual. |
| [generate_preview](/watermark/python-net/groupdocs.watermark/watermarker/generate_preview/#preview_options) | Genera imágenes de vista previa para el documento. |
| [generate_preview_preview_options](/watermark/python-net/groupdocs.watermark/watermarker/generate_preview_preview_options/) |  |
| [get_content](/watermark/python-net/groupdocs.watermark/watermarker/get_content/) |  |
| [get_document_info](/watermark/python-net/groupdocs.watermark/watermarker/get_document_info/) | Obtiene la información sobre el formato del documento cargado. |
| [get_images](/watermark/python-net/groupdocs.watermark/watermarker/get_images/#search_criteria) | Encuentra imágenes según los criterios de búsqueda especificados. |
| [get_images](/watermark/python-net/groupdocs.watermark/watermarker/get_images/) | Encuentra todas las imágenes en el documento. |
| [get_images_image_search_criteria](/watermark/python-net/groupdocs.watermark/watermarker/get_images_image_search_criteria/) |  |
| [remove](/watermark/python-net/groupdocs.watermark/watermarker/remove/#possible_watermark) | Elimina una marca de agua del documento. |
| [remove](/watermark/python-net/groupdocs.watermark/watermarker/remove/#possible_watermarks) | Elimina todas las marcas de agua de la colección del documento. |
| [remove_possible_watermark](/watermark/python-net/groupdocs.watermark/watermarker/remove_possible_watermark/) |  |
| [remove_possible_watermark_collection](/watermark/python-net/groupdocs.watermark/watermarker/remove_possible_watermark_collection/) |  |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/) | Guarda los datos del documento en el flujo subyacente. |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/#file_path) | Guarda el documento en la ubicación de archivo especificada. |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/#document) | Guarda el documento en el flujo especificado. |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/#options) | Guarda los datos del documento en el flujo subyacente usando opciones de guardado. |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/#file_path-options) | Guarda el documento en la ubicación de archivo especificada usando opciones de guardado. |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/#document-options) | Guarda el documento en el flujo especificado usando opciones de guardado. |
| [save_file](/watermark/python-net/groupdocs.watermark/watermarker/save_file/) |  |
| [save_save_options](/watermark/python-net/groupdocs.watermark/watermarker/save_save_options/) |  |
| [save_stream](/watermark/python-net/groupdocs.watermark/watermarker/save_stream/) |  |
| [save_streams](/watermark/python-net/groupdocs.watermark/watermarker/save_streams/) |  |
| [save_string](/watermark/python-net/groupdocs.watermark/watermarker/save_string/) |  |
| [search](/watermark/python-net/groupdocs.watermark/watermarker/search/) | Busca todas las marcas de agua posibles en el documento. |
| [search](/watermark/python-net/groupdocs.watermark/watermarker/search/#search_criteria) | Busca marcas de agua posibles según los criterios de búsqueda especificados. |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark/watermarker/search_search_criteria/) |  |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [searchable_objects](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/) | Los objetos que se incluirán en una búsqueda de marcas de agua. |

### Ejemplo

```python
from groupdocs.watermark import Watermarker

with Watermarker("D:\\input.pdf") as watermarker:
    # Utiliza los métodos de `Watermarker` para agregar, buscar o eliminar marcas de agua.
    watermarker.save("D:\\output.pdf")
```

### Guides
Guías de tareas que usan `Watermarker`:

* [Hello, World!](/watermark/python-net/guides/hello-world/)
* [Add text watermarks](/watermark/python-net/guides/add-text/)
* [Add image watermarks](/watermark/python-net/guides/add-image/)
* [Customize watermarks](/watermark/python-net/guides/customize/)
* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)
* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)
* [Update watermarks](/watermark/python-net/guides/update/)
* [Clear watermarks](/watermark/python-net/guides/clear/)
* [Document preview](/watermark/python-net/guides/preview/)
* [Get document info](/watermark/python-net/guides/get-document-info/)

### Ver también
* module [`groupdocs.watermark`](/watermark/python-net/groupdocs.watermark/)
