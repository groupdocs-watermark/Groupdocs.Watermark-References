---
title: "Watermarker"
second_title: "GroupDocs.Watermark para la referencia de API de .NET"
description: "Representa una clase para la gestión de marcas de agua en un documento."
type: docs
weight: 3140
url: /es/net/groupdocs.watermark/watermarker/
---
## Watermarker class

Representa una clase para la gestión de marcas de agua en un documento.

```csharp
public class Watermarker : IDisposable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Watermarker](watermarker#constructor)(Stream) | Inicializa una nueva instancia de la clase [`Watermarker`](../watermarker) con el flujo especificado. |
| [Watermarker](watermarker#constructor_4)(string) | Inicializa una nueva instancia de la clase [`Watermarker`](../watermarker) con la ruta del documento especificada. |
| [Watermarker](watermarker#constructor_1)(Stream, LoadOptions) | Inicializa una nueva instancia de la clase [`Watermarker`](../watermarker) con el flujo especificado y las opciones de carga. |
| [Watermarker](watermarker#constructor_3)(Stream, WatermarkerSettings) | Inicializa una nueva instancia de la clase [`Watermarker`](../watermarker) con el flujo especificado y la configuración. |
| [Watermarker](watermarker#constructor_5)(string, LoadOptions) | Inicializa una nueva instancia de la clase [`Watermarker`](../watermarker) con la ruta del documento especificada y las opciones de carga. |
| [Watermarker](watermarker#constructor_7)(string, WatermarkerSettings) | Inicializa una nueva instancia de la clase [`Watermarker`](../watermarker) con la ruta del documento especificada y la configuración. |
| [Watermarker](watermarker#constructor_2)(Stream, LoadOptions, WatermarkerSettings) | Inicializa una nueva instancia de la clase [`Watermarker`](../watermarker) con el flujo especificado, las opciones de carga y la configuración. |
| [Watermarker](watermarker#constructor_6)(string, LoadOptions, WatermarkerSettings) | Inicializa una nueva instancia de la clase [`Watermarker`](../watermarker) con la ruta del documento especificada, las opciones de carga y la configuración. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [SearchableObjects](../../groupdocs.watermark/watermarker/searchableobjects) { get; set; } | Obtiene o establece los objetos de contenido que se incluirán en una búsqueda de marca de agua. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Add](../../groupdocs.watermark/watermarker/add#add)(Watermark) | Agrega una marca de agua al documento cargado. |
| [Add](../../groupdocs.watermark/watermarker/add#add_1)(Watermark, WatermarkOptions) | Agrega una marca de agua al documento cargado usando opciones de marca de agua. |
| [Dispose](../../groupdocs.watermark/watermarker/dispose)() | Elimina la instancia actual. |
| [GeneratePreview](../../groupdocs.watermark/watermarker/generatepreview)(PreviewOptions) | Genera imágenes de vista previa para el documento. |
| [GetContent&lt;T&gt;](../../groupdocs.watermark/watermarker/getcontent)() | Devuelve el objeto [`Content`](../../groupdocs.watermark.contents/content) para el documento cargado. |
| [GetDocumentInfo](../../groupdocs.watermark/watermarker/getdocumentinfo)() | Obtiene la información sobre el formato del documento cargado. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages)() | Encuentra todas las imágenes en el documento. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages_1)(ImageSearchCriteria) | Encuentra imágenes según los criterios de búsqueda especificados. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove)(PossibleWatermark) | Elimina la marca de agua del documento. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove_1)(PossibleWatermarkCollection) | Elimina todas las marcas de agua de la colección del documento. |
| [Save](../../groupdocs.watermark/watermarker/save#save)() | Guarda los datos del documento en el flujo subyacente. |
| [Save](../../groupdocs.watermark/watermarker/save#save_1)(SaveOptions) | Guarda los datos del documento en el flujo subyacente usando opciones de guardado. |
| [Save](../../groupdocs.watermark/watermarker/save#save_2)(Stream) | Guarda el documento en el flujo especificado. |
| [Save](../../groupdocs.watermark/watermarker/save#save_4)(string) | Guarda el documento en la ubicación de archivo especificada. |
| [Save](../../groupdocs.watermark/watermarker/save#save_3)(Stream, SaveOptions) | Guarda el documento en el flujo especificado usando opciones de guardado. |
| [Save](../../groupdocs.watermark/watermarker/save#save_5)(string, SaveOptions) | Guarda el documento en la ubicación de archivo especificada usando opciones de guardado. |
| [Search](../../groupdocs.watermark/watermarker/search#search)() | Busca todas las marcas de agua posibles en el documento. |
| [Search](../../groupdocs.watermark/watermarker/search#search_1)(SearchCriteria) | Busca marcas de agua posibles según los criterios de búsqueda especificados. |

### Ejemplos

Carga y guarda un contenido de cualquier formato compatible.

```csharp
// Carga un contenido desde un archivo.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Utiliza los métodos de la clase Watermarker para añadir, buscar o eliminar marcas de agua.

    // Guarda los cambios.
    watermarker.Save("D:\\output.pdf");
}
```

### Ver también

* namespace [GroupDocs.Watermark](../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.watermark.dll -->
