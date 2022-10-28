---
title: DiagramPageWatermarkOptions
second_title: Referencia de API de GroupDocs.Watermark para .NET
description: Representa las opciones de adición de marca de agua al agregar una marca de agua de forma a una página particular de un documento de Visio.
type: docs
weight: 1650
url: /es/net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/
---
## DiagramPageWatermarkOptions class

Representa las opciones de adición de marca de agua al agregar una marca de agua de forma a una página particular de un documento de Visio.

```csharp
public sealed class DiagramPageWatermarkOptions : DiagramWatermarkOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DiagramPageWatermarkOptions](diagrampagewatermarkoptions)() | Inicializa una nueva instancia del[`DiagramPageWatermarkOptions`](../diagrampagewatermarkoptions) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [IsLocked](../../groupdocs.watermark.options.diagram/diagramwatermarkoptions/islocked) { get; set; } | Obtiene o establece un valor que indica si está prohibida la edición de la forma en Visio. |
| [PageIndex](../../groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/pageindex) { get; set; } | Obtiene o establece el índice de la página para agregarle una marca de agua. |

### Observaciones

**Aprende más:**

* [Agregar marcas de agua a los documentos de diagrama](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents)

### Ejemplos

Agregue una marca de agua protegida a la primera página de un documento de Visio.

```csharp
DiagramLoadOptions loadOptions = new DiagramLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.vsdx", loadOptions))
{
    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));

    DiagramPageWatermarkOptions options = new DiagramPageWatermarkOptions();
    options.IsLocked = true;
    options.PageIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Ver también

* class [DiagramWatermarkOptions](../diagramwatermarkoptions)
* espacio de nombres [GroupDocs.Watermark.Options.Diagram](../../groupdocs.watermark.options.diagram)
* asamblea [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->