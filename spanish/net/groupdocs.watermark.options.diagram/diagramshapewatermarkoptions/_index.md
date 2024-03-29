---
title: DiagramShapeWatermarkOptions
second_title: Referencia de API de GroupDocs.Watermark para .NET
description: Representa las opciones de adición de marca de agua al agregar una marca de agua de forma a un documento de Visio.
type: docs
weight: 1680
url: /es/net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/
---
## DiagramShapeWatermarkOptions class

Representa las opciones de adición de marca de agua al agregar una marca de agua de forma a un documento de Visio.

```csharp
public sealed class DiagramShapeWatermarkOptions : DiagramWatermarkOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DiagramShapeWatermarkOptions](diagramshapewatermarkoptions)() | Inicializa una nueva instancia del[`DiagramShapeWatermarkOptions`](../diagramshapewatermarkoptions) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [IsLocked](../../groupdocs.watermark.options.diagram/diagramwatermarkoptions/islocked) { get; set; } | Obtiene o establece un valor que indica si está prohibida la edición de la forma en Visio. |
| [PlacementType](../../groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/placementtype) { get; set; } | Obtiene o establece un valor que especifica en qué páginas se debe agregar una marca de agua. |

### Observaciones

**Aprende más:**

* [Agregar marcas de agua a los documentos de diagrama](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents)

### Ejemplos

Agregar marca de agua protegida a todas las páginas del documento de Visio.

```csharp
DiagramLoadOptions loadOptions = new DiagramLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.vsdx", loadOptions))
{
    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));

    DiagramShapeWatermarkOptions options = new DiagramShapeWatermarkOptions();
    options.IsLocked = true;
    options.PlacementType = DiagramWatermarkPlacementType.AllPages; // por defecto

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Ver también

* class [DiagramWatermarkOptions](../diagramwatermarkoptions)
* espacio de nombres [GroupDocs.Watermark.Options.Diagram](../../groupdocs.watermark.options.diagram)
* asamblea [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
