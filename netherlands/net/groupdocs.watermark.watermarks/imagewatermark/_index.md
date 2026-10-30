---
title: "ImageWatermark"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Stelt een afbeeldingwatermerk voor."
type: docs
weight: 3190
url: /nl/net/groupdocs.watermark.watermarks/imagewatermark/
---
## ImageWatermark class

Stelt een afbeeldingwatermerk voor.

```csharp
public sealed class ImageWatermark : Watermark, IDisposable
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [ImageWatermark](imagewatermark#constructor)(Stream) | Initialiseert een nieuw exemplaar van de [`ImageWatermark`](../imagewatermark) klasse met een opgegeven stream. |
| [ImageWatermark](imagewatermark#constructor_1)(string) | Initialiseert een nieuw exemplaar van de [`ImageWatermark`](../imagewatermark) klasse met een opgegeven bestandspad. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ConsiderParentMargins](../../groupdocs.watermark/watermark/considerparentmargins) { get; set; } | Haalt op of stelt een waarde in die aangeeft of de grootte en coördinaten van het watermerk worden berekend met inachtneming van de marges van de bovenliggende container. |
| [Height](../../groupdocs.watermark/watermark/height) { get; set; } | Gets of sets de gewenste hoogte van deze [`Watermark`](../../groupdocs.watermark/watermark). |
| [HorizontalAlignment](../../groupdocs.watermark/watermark/horizontalalignment) { get; set; } | Gets of sets de horizontale uitlijning van deze [`Watermark`](../../groupdocs.watermark/watermark). |
| [IsBackground](../../groupdocs.watermark/watermark/isbackground) { get; set; } | Haalt op of stelt een waarde in die aangeeft of het watermerk op de achtergrond moet worden geplaatst. |
| [Margins](../../groupdocs.watermark/watermark/margins) { get; set; } | Gets of sets de marge-instellingen van deze [`Watermark`](../../groupdocs.watermark/watermark). |
| [Opacity](../../groupdocs.watermark/watermark/opacity) { get; set; } | Gets of sets de doorzichtigheid van deze [`Watermark`](../../groupdocs.watermark/watermark). |
| [PagesSetup](../../groupdocs.watermark/watermark/pagessetup) { get; set; } | Gets of sets de pagina-instellingsinstellingen van deze [`Watermark`](../../groupdocs.watermark/watermark). |
| [RotateAngle](../../groupdocs.watermark/watermark/rotateangle) { get; set; } | Haalt op of stelt de rotatiehoek van deze [`Watermark`](../../groupdocs.watermark/watermark) in graden in. |
| [SaveResultInMetadata](../../groupdocs.watermark/watermark/saveresultinmetadata) { get; set; } | Haalt op of stelt een waarde in die aangeeft of informatie over toegevoegde watermerken moet worden opgeslagen in de documentmetadata. |
| [ScaleFactor](../../groupdocs.watermark/watermark/scalefactor) { get; set; } | Haalt op of stelt een waarde in die bepaalt hoe de grootte van het watermerk afhangt van de grootte van het bovenliggende element. |
| [SizingType](../../groupdocs.watermark/watermark/sizingtype) { get; set; } | Haalt op of stelt een waarde in die een manier specificeert waarop het watermerk moet worden geschaald. |
| [TileOptions](../../groupdocs.watermark/watermark/tileoptions) { get; set; } | Haalt op of stelt opties in om een herhaald watermerk te definiëren |
| [VerticalAlignment](../../groupdocs.watermark/watermark/verticalalignment) { get; set; } | Haalt op of stelt de verticale uitlijning van deze [`Watermark`](../../groupdocs.watermark/watermark) in. |
| [Width](../../groupdocs.watermark/watermark/width) { get; set; } | Haalt op of stelt de gewenste breedte van deze [`Watermark`](../../groupdocs.watermark/watermark) in. |
| [X](../../groupdocs.watermark/watermark/x) { get; set; } | Haalt op of stelt de x-coördinaat van deze [`Watermark`](../../groupdocs.watermark/watermark) in. |
| [Y](../../groupdocs.watermark/watermark/y) { get; set; } | Haalt op of stelt de y-coördinaat van deze [`Watermark`](../../groupdocs.watermark/watermark) in. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Dispose](../../groupdocs.watermark.watermarks/imagewatermark/dispose)() | Verwijdert de huidige instantie. |

### Opmerkingen

**Learn more:**

* [Adding image watermarks](https://docs.groupdocs.com/display/watermarknet/Adding+image+watermarks)

### Voorbeelden

Voeg een afbeelding-watermerk toe aan een document van elk ondersteund type.

```csharp
foreach (string filePath in Directory.GetFiles(@"C:\Documents"))
{
    using (Watermarker watermarker = new Watermarker(filePath))
    {
        using (ImageWatermark watermark = new ImageWatermark(@"C:\watermark.png"))
        {
            watermark.HorizontalAlignment = HorizontalAlignment.Center;
            watermark.VerticalAlignment = VerticalAlignment.Center;
            watermarker.Add(watermark);
        }

        watermarker.Save();
    }
}
```

### Zie ook

* class [Watermark](../../groupdocs.watermark/watermark)
* namespace [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
