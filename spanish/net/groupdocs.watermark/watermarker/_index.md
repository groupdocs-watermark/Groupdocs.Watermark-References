---
title: Watermarker
second_title: Referencia de API de GroupDocs.Watermark para .NET
description: Representa una clase para la gestión de marcas de agua en un documento.
type: docs
weight: 3060
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
| [Watermarker](watermarker#constructor)(Stream) | Inicializa una nueva instancia del[`Watermarker`](../watermarker) clase con el flujo especificado. |
| [Watermarker](watermarker#constructor_4)(string) | Inicializa una nueva instancia del[`Watermarker`](../watermarker) clase con la ruta del documento especificado. |
| [Watermarker](watermarker#constructor_1)(Stream, LoadOptions) | Inicializa una nueva instancia del[`Watermarker`](../watermarker) clase con el stream especificado y las opciones de carga. |
| [Watermarker](watermarker#constructor_3)(Stream, WatermarkerSettings) | Inicializa una nueva instancia del[`Watermarker`](../watermarker) clase con el stream y settings. especificados |
| [Watermarker](watermarker#constructor_5)(string, LoadOptions) | Inicializa una nueva instancia del[`Watermarker`](../watermarker)clase con la ruta del documento especificada y opciones de carga. |
| [Watermarker](watermarker#constructor_7)(string, WatermarkerSettings) | Inicializa una nueva instancia del[`Watermarker`](../watermarker) clase con la configuración y la ruta del documento especificados. |
| [Watermarker](watermarker#constructor_2)(Stream, LoadOptions, WatermarkerSettings) | Inicializa una nueva instancia del[`Watermarker`](../watermarker) clase con el flujo especificado, cargar opciones y configuraciones. |
| [Watermarker](watermarker#constructor_6)(string, LoadOptions, WatermarkerSettings) | Inicializa una nueva instancia del[`Watermarker`](../watermarker) clase con la ruta del documento especificada , las opciones de carga y la configuración. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [SearchableObjects](../../groupdocs.watermark/watermarker/searchableobjects) { get; set; } | Obtiene o establece los objetos de contenido que se incluirán en una búsqueda de marca de agua. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Add](../../groupdocs.watermark/watermarker/add#add)(Watermark) | Agrega una marca de agua al documento cargado. |
| [Add](../../groupdocs.watermark/watermarker/add#add_1)(Watermark, WatermarkOptions) | Agrega una marca de agua al documento cargado usando las opciones de marca de agua. |
| [Dispose](../../groupdocs.watermark/watermarker/dispose)() | Elimina la instancia actual. |
| [GeneratePreview](../../groupdocs.watermark/watermarker/generatepreview)(PreviewOptions) | Genera imágenes de vista previa del documento. |
| [GetContent&lt;T&gt;](../../groupdocs.watermark/watermarker/getcontent)() | Devuelve el[`Content`](../../groupdocs.watermark.contents/content) objeto para el documento cargado. |
| [GetDocumentInfo](../../groupdocs.watermark/watermarker/getdocumentinfo)() | Obtiene la información sobre el formato del documento cargado. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages)() | Encuentra todas las imágenes en el documento. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages_1)(ImageSearchCriteria) | Encuentra imágenes de acuerdo con los criterios de búsqueda especificados. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove)(PossibleWatermark) | Elimina la marca de agua del documento. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove_1)(PossibleWatermarkCollection) | Elimina todas las marcas de agua de la colección del documento. |
| [Save](../../groupdocs.watermark/watermarker/save#save)() | Guarda los datos del documento en el flujo subyacente. |
| [Save](../../groupdocs.watermark/watermarker/save#save_1)(SaveOptions) | Guarda los datos del documento en la secuencia subyacente usando las opciones de guardado. |
| [Save](../../groupdocs.watermark/watermarker/save#save_2)(Stream) | Guarda el documento en el flujo especificado. |
| [Save](../../groupdocs.watermark/watermarker/save#save_4)(string) | Guarda el documento en la ubicación de archivo especificada. |
| [Save](../../groupdocs.watermark/watermarker/save#save_3)(Stream, SaveOptions) | Guarda el documento en la secuencia especificada utilizando las opciones de guardado. |
| [Save](../../groupdocs.watermark/watermarker/save#save_5)(string, SaveOptions) | Guarda el documento en la ubicación de archivo especificada utilizando las opciones de guardado. |
| [Search](../../groupdocs.watermark/watermarker/search#search)() | Busca todas las marcas de agua posibles en el documento. |
| [Search](../../groupdocs.watermark/watermarker/search#search_1)(SearchCriteria) | Busca posibles marcas de agua de acuerdo con los criterios de búsqueda especificados. |

### Ejemplos

Cargue y guarde un contenido de cualquier formato compatible.

```csharp
// Carga un contenido de un archivo.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Usar métodos de la clase Watermarker para agregar, buscar o eliminar marcas de agua.

    // Guardar cambios.
    watermarker.Save("D:\\output.pdf");
}
```

### Ver también

* espacio de nombres [GroupDocs.Watermark](../../groupdocs.watermark)
* asamblea [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
