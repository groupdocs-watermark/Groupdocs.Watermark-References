---
title: "GifImageWatermarkOptions"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Geeft opties voor het toevoegen van een watermerk weer bij het toevoegen van een watermerk aan een GIF-afbeelding."
type: docs
weight: 1830
url: /nl/net/groupdocs.watermark.options.image/gifimagewatermarkoptions/
---
## GifImageWatermarkOptions class

Geeft opties voor het toevoegen van een watermerk weer bij het toevoegen van een watermerk aan een GIF-afbeelding.

```csharp
public sealed class GifImageWatermarkOptions : MultiframeImageWatermarkOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [GifImageWatermarkOptions](gifimagewatermarkoptions#constructor)() | Initialiseert een nieuw exemplaar van de [`GifImageWatermarkOptions`](../gifimagewatermarkoptions) klasse. |
| [GifImageWatermarkOptions](gifimagewatermarkoptions#constructor_1)(int) | Initialiseert een nieuw exemplaar van de [`GifImageWatermarkOptions`](../gifimagewatermarkoptions) klasse met een opgegeven index van een frame. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [FrameIndex](../../groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frameindex) { get; set; } | Haalt op of stelt de index van het frame in om een watermerk toe te voegen. |

### Opmerkingen

**Learn more:**

* [Add watermarks to images](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images)

### Voorbeelden

Voeg een watermerk toe aan een specifiek frame van een GIF-afbeelding.

```csharp
GifImageLoadOptions loadOptions = new GifImageLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\test.gif", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));

    GifImageWatermarkOptions options = new GifImageWatermarkOptions();
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
