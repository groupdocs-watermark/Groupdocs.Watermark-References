---
title: TiffImageWatermarkOptions
second_title: Referencia de API de GroupDocs.Watermark para .NET
description: Representa las opciones de adición de marca de agua al agregar una marca de agua a una imagen TIFF.
type: docs
weight: 1830
url: /es/net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/
---
## TiffImageWatermarkOptions class

Representa las opciones de adición de marca de agua al agregar una marca de agua a una imagen TIFF.

```csharp
public sealed class TiffImageWatermarkOptions : MultiframeImageWatermarkOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TiffImageWatermarkOptions](tiffimagewatermarkoptions#constructor)() | Inicializa una nueva instancia del[`TiffImageWatermarkOptions`](../tiffimagewatermarkoptions) clase. |
| [TiffImageWatermarkOptions](tiffimagewatermarkoptions#constructor_1)(int) | Inicializa una nueva instancia del[`TiffImageWatermarkOptions`](../tiffimagewatermarkoptions) class con un índice especificado del marco. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [FrameIndex](../../groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frameindex) { get; set; } | Obtiene o establece el índice del marco para agregar la marca de agua. |

### Observaciones

**Aprende más:**

* [Agregar marcas de agua a las imágenes](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images)

### Ejemplos

Agregar marca de agua a un marco particular de imagen TIFF.

```csharp
TiffImageLoadOptions loadOptions = new TiffImageLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\test.tiff", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));

    TiffImageWatermarkOptions options = new TiffImageWatermarkOptions();
    options.FrameIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Ver también

* class [MultiframeImageWatermarkOptions](../multiframeimagewatermarkoptions)
* espacio de nombres [GroupDocs.Watermark.Options.Image](../../groupdocs.watermark.options.image)
* asamblea [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
