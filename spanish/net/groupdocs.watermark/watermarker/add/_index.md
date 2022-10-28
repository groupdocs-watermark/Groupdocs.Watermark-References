---
title: Add
second_title: Referencia de API de GroupDocs.Watermark para .NET
description: Agrega una marca de agua al documento cargado.
type: docs
weight: 30
url: /es/net/groupdocs.watermark/watermarker/add/
---
## Add(Watermark) {#add}

Agrega una marca de agua al documento cargado.

```csharp
public void Add(Watermark watermark)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| watermark | Watermark | La marca de agua que se agregará al documento. |

### Observaciones

Más información sobre cómo agregar marcas de agua: [Agregar marcas de agua](https://docs.groupdocs.com/display/watermarknet/Adding+watermarks) .

### Ejemplos

Agregar imagen y marca de agua de texto a un documento de cualquier tipo compatible.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.pdf"))
{
    TextWatermark textWatermark = new TextWatermark("DRAFT", new Font("Arial", 19));
    textWatermark.HorizontalAlignment = HorizontalAlignment.Center;
    textWatermark.VerticalAlignment = VerticalAlignment.Top;
    textWatermark.ConsiderParentMargins = true;
    textWatermark.ForegroundColor = Color.Red;
    textWatermark.IsBackground = true;
    textWatermark.Opacity = 0.5;
    watermarker.Add(textWatermark);

    using (ImageWatermark imageWatermark = new ImageWatermark(@"D:\draft.png"))
    {
        imageWatermark.HorizontalAlignment = HorizontalAlignment.Center;
        imageWatermark.VerticalAlignment = VerticalAlignment.Bottom;
        imageWatermark.ConsiderParentMargins = true;
        imageWatermark.IsBackground = true;
        imageWatermark.Opacity = 0.5;
        watermarker.Add(imageWatermark);
    }

    watermarker.Save(@"D:\output.pdf");
}
```

### Ver también

* class [Watermark](../../watermark)
* class [Watermarker](../../watermarker)
* espacio de nombres [GroupDocs.Watermark](../../watermarker)
* asamblea [GroupDocs.Watermark](../../../)

---

## Add(Watermark, WatermarkOptions) {#add_1}

Agrega una marca de agua al documento cargado usando las opciones de marca de agua.

```csharp
public void Add(Watermark watermark, WatermarkOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| watermark | Watermark | La marca de agua que se agregará al documento. |
| options | WatermarkOptions | Opciones adicionales para usar al agregar la marca de agua. |

### Observaciones

Obtenga más información sobre cómo agregar marcas de agua [Agregar marcas de agua](https://docs.groupdocs.com/display/watermarknet/Adding+watermarks) .

### Ejemplos

Agregue una marca de agua de imagen a una página particular de un documento pdf.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\doc.pdf", loadOptions))
using (ImageWatermark watermark = new ImageWatermark(@"C:\watermark.png"))
{
    PdfXObjectWatermarkOptions options = new PdfXObjectWatermarkOptions();
    options.PageIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Ver también

* class [Watermark](../../watermark)
* class [WatermarkOptions](../../../groupdocs.watermark.options/watermarkoptions)
* class [Watermarker](../../watermarker)
* espacio de nombres [GroupDocs.Watermark](../../watermarker)
* asamblea [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->