---
title: PdfWatermarkableImage
second_title: Referencia de API de GroupDocs.Watermark para .NET
description: Representa una imagen dentro de un documento Pdf.
type: docs
weight: 730
url: /es/net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/
---
## PdfWatermarkableImage class

Representa una imagen dentro de un documento Pdf.

```csharp
public class PdfWatermarkableImage : WatermarkableImage
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfWatermarkableImage](pdfwatermarkableimage)(byte[]) | Inicializa una nueva instancia del[`PdfWatermarkableImage`](../pdfwatermarkableimage) clase usando datos de imagen especificados. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Height](../../groupdocs.watermark.contents.image/watermarkableimage/height) { get; } | Obtiene la altura de este[`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) en píxeles. |
| [Width](../../groupdocs.watermark.contents.image/watermarkableimage/width) { get; } | Obtiene el ancho de este[`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) en píxeles. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.image/watermarkableimage/add)(Watermark) | Agrega una marca de agua a esto[`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) . Este método asume que el desplazamiento y el tamaño de la marca de agua se miden en píxeles (si están asignados). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Encuentra todas las imágenes en el contenido. La búsqueda se realiza en los objetos especificados en[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Encuentra imágenes de acuerdo con los criterios de búsqueda especificados. La búsqueda se realiza en los objetos especificados en[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [GetBytes](../../groupdocs.watermark.contents.image/watermarkableimage/getbytes)() | Obtiene la imagen como matriz de bytes. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Encuentra todas las marcas de agua posibles en el contenido. La búsqueda se realiza en los objetos especificados en[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Encuentra posibles marcas de agua de acuerdo con los criterios de búsqueda especificados. La búsqueda se realiza en los objetos especificados en[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |

### Ver también

* class [WatermarkableImage](../../groupdocs.watermark.contents.image/watermarkableimage)
* espacio de nombres [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* asamblea [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
