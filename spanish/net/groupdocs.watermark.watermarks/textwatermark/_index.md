---
title: "TextWatermark"
second_title: "GroupDocs.Watermark para la referencia de API de .NET"
description: "Representa una marca de agua de texto."
type: docs
weight: 3320
url: /es/net/groupdocs.watermark.watermarks/textwatermark/
---
## TextWatermark class

Representa una marca de agua de texto.

```csharp
public class TextWatermark : Watermark
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TextWatermark](textwatermark)(string, Font) | Inicializa una nueva instancia de la clase [`TextWatermark`](../textwatermark) con un texto especificado y una fuente. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BackgroundColor](../../groupdocs.watermark.watermarks/textwatermark/backgroundcolor) { get; set; } | Obtiene o establece el color de fondo del texto. |
| [ConsiderParentMargins](../../groupdocs.watermark/watermark/considerparentmargins) { get; set; } | Obtiene o establece un valor que indica si el tamaño y las coordenadas de la marca de agua se calculan considerando los márgenes del padre. |
| [Font](../../groupdocs.watermark.watermarks/textwatermark/font) { get; set; } | Obtiene o establece la fuente del texto. |
| [ForegroundColor](../../groupdocs.watermark.watermarks/textwatermark/foregroundcolor) { get; set; } | Obtiene o establece el color de primer plano del texto. |
| [Height](../../groupdocs.watermark/watermark/height) { get; set; } | Obtiene o establece la altura deseada de este [`Watermark`](../../groupdocs.watermark/watermark). |
| [HorizontalAlignment](../../groupdocs.watermark/watermark/horizontalalignment) { get; set; } | Obtiene o establece la alineación horizontal de este [`Watermark`](../../groupdocs.watermark/watermark). |
| [IsBackground](../../groupdocs.watermark/watermark/isbackground) { get; set; } | Obtiene o establece un valor que indica si la marca de agua debe colocarse en segundo plano. |
| [Margins](../../groupdocs.watermark/watermark/margins) { get; set; } | Obtiene o establece la configuración de márgenes de este [`Watermark`](../../groupdocs.watermark/watermark). |
| [Opacity](../../groupdocs.watermark/watermark/opacity) { get; set; } | Obtiene o establece la opacidad de este [`Watermark`](../../groupdocs.watermark/watermark). |
| [Padding](../../groupdocs.watermark.watermarks/textwatermark/padding) { get; set; } | Obtiene o establece la configuración de relleno de este [`TextWatermark`](../textwatermark). Esta propiedad solo es aplicable a archivos de imagen. |
| [PagesSetup](../../groupdocs.watermark/watermark/pagessetup) { get; set; } | Obtiene o establece la configuración de páginas de este [`Watermark`](../../groupdocs.watermark/watermark). |
| [RotateAngle](../../groupdocs.watermark/watermark/rotateangle) { get; set; } | Obtiene o establece el ángulo de rotación de este [`Watermark`](../../groupdocs.watermark/watermark) en grados. |
| [SaveResultInMetadata](../../groupdocs.watermark/watermark/saveresultinmetadata) { get; set; } | Obtiene o establece un valor que indica si se debe guardar información sobre las marcas de agua añadidas en los metadatos del documento. |
| [ScaleFactor](../../groupdocs.watermark/watermark/scalefactor) { get; set; } | Obtiene o establece un valor que define cómo el tamaño de la marca de agua depende del tamaño del elemento padre. |
| [SizingType](../../groupdocs.watermark/watermark/sizingtype) { get; set; } | Obtiene o establece un valor que especifica la forma en que debe dimensionarse la marca de agua. |
| [Text](../../groupdocs.watermark.watermarks/textwatermark/text) { get; set; } | Obtiene o establece el texto que se usará como marca de agua. |
| [TextAlignment](../../groupdocs.watermark.watermarks/textwatermark/textalignment) { get; set; } | Obtiene o establece la alineación del texto de la marca de agua. |
| [TileOptions](../../groupdocs.watermark/watermark/tileoptions) { get; set; } | Obtiene o establece opciones para definir la marca de agua repetida |
| [VerticalAlignment](../../groupdocs.watermark/watermark/verticalalignment) { get; set; } | Obtiene o establece la alineación vertical de este [`Watermark`](../../groupdocs.watermark/watermark). |
| [Width](../../groupdocs.watermark/watermark/width) { get; set; } | Obtiene o establece el ancho deseado de este [`Watermark`](../../groupdocs.watermark/watermark). |
| [X](../../groupdocs.watermark/watermark/x) { get; set; } | Obtiene o establece la coordenada x de este [`Watermark`](../../groupdocs.watermark/watermark). |
| [Y](../../groupdocs.watermark/watermark/y) { get; set; } | Obtiene o establece la coordenada y de este [`Watermark`](../../groupdocs.watermark/watermark). |

### Observaciones

**Learn more:**

* [Adding text watermarks](https://docs.groupdocs.com/display/watermarknet/Adding+text+watermarks)

### Ejemplos

Escala la marca de agua de texto según el tamaño del elemento padre.

```csharp
foreach (string file in Directory.GetFiles("C:\\test"))
{
    using (Watermarker watermarker = new Watermarker(file))
    {
        TextWatermark watermark = new TextWatermark("test watermark", new Font("Arial", 36));
        watermark.HorizontalAlignment = HorizontalAlignment.Center;
        watermark.VerticalAlignment = VerticalAlignment.Center;
        watermark.SizingType = SizingType.ScaleToParentDimensions;
        watermark.RotateAngle = 45;
        watermark.ScaleFactor = 0.4;

        watermarker.Add(watermark);
        watermarker.Save();
    }
}
```

### Ver también

* class [Watermark](../../groupdocs.watermark/watermark)
* namespace [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.watermark.dll -->
