---
title: "TiffImageWatermarkOptions"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Stelt opties voor het toevoegen van een watermerk voor wanneer een watermerk wordt toegevoegd aan een TIFF-afbeelding voor."
type: docs
weight: 1900
url: /nl/net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/
---
## TiffImageWatermarkOptions class

Stelt opties voor het toevoegen van een watermerk voor wanneer een watermerk wordt toegevoegd aan een TIFF-afbeelding voor.

```csharp
public sealed class TiffImageWatermarkOptions : MultiframeImageWatermarkOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [TiffImageWatermarkOptions](tiffimagewatermarkoptions#constructor)() | Initialiseert een nieuw exemplaar van de [`TiffImageWatermarkOptions`](../tiffimagewatermarkoptions) klasse. |
| [TiffImageWatermarkOptions](tiffimagewatermarkoptions#constructor_1)(int) | Initialiseert een nieuw exemplaar van de [`TiffImageWatermarkOptions`](../tiffimagewatermarkoptions) klasse met een opgegeven index van het frame. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [FrameIndex](../../groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frameindex) { get; set; } | Haalt op of stelt de index van het frame in om een watermerk toe te voegen. |

### Opmerkingen

**Learn more:**

* [Add watermarks to images](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images)

### Voorbeelden

Voeg een watermerk toe aan een specifiek frame van een TIFF-afbeelding.

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

### Zie ook

* class [MultiframeImageWatermarkOptions](../multiframeimagewatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Image](../../groupdocs.watermark.options.image)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
