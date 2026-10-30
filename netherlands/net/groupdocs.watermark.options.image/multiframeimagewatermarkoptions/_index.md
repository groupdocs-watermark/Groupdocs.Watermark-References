---
title: "MultiframeImageWatermarkOptions"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Stelt opties voor het toevoegen van een watermerk voor wanneer een watermerk wordt toegevoegd aan een multiframe-afbeelding."
type: docs
weight: 1870
url: /nl/net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/
---
## MultiframeImageWatermarkOptions class

Stelt opties voor het toevoegen van een watermerk voor wanneer een watermerk wordt toegevoegd aan een afbeelding met meerdere frames voor.

```csharp
public class MultiframeImageWatermarkOptions : WatermarkOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [MultiframeImageWatermarkOptions](multiframeimagewatermarkoptions#constructor)() | Initialiseert een nieuw exemplaar van de [`MultiframeImageWatermarkOptions`](../multiframeimagewatermarkoptions) klasse. |
| [MultiframeImageWatermarkOptions](multiframeimagewatermarkoptions#constructor_1)(int) | Initialiseert een nieuw exemplaar van de [`MultiframeImageWatermarkOptions`](../multiframeimagewatermarkoptions) klasse met een opgegeven index van het frame. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [FrameIndex](../../groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frameindex) { get; set; } | Haalt op of stelt de index van het frame in om een watermerk toe te voegen. |

### Opmerkingen

**Learn more:**

* [Add watermarks to images](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images)

### Voorbeelden

Voeg een watermerk toe aan een specifiek frame van een multi-frame afbeelding.

```csharp
ImageLoadOptions loadOptions = new ImageLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\test.gif", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));

    MultiframeImageWatermarkOptions options = new MultiframeImageWatermarkOptions();
    options.FrameIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Zie ook

* class [WatermarkOptions](../../groupdocs.watermark.options/watermarkoptions)
* namespace [GroupDocs.Watermark.Options.Image](../../groupdocs.watermark.options.image)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
