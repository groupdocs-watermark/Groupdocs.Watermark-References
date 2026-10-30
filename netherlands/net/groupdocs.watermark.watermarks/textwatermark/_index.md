---
title: "TextWatermark"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Stelt een tekstwatermerk voor."
type: docs
weight: 3320
url: /nl/net/groupdocs.watermark.watermarks/textwatermark/
---
## TextWatermark class

Stelt een tekstwatermerk voor.

```csharp
public class TextWatermark : Watermark
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [TextWatermark](textwatermark)(string, Font) | Initialiseert een nieuw exemplaar van de [`TextWatermark`](../textwatermark) klasse met een opgegeven tekst en een lettertype. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BackgroundColor](../../groupdocs.watermark.watermarks/textwatermark/backgroundcolor) { get; set; } | Gets of sets de achtergrondkleur van de tekst. |
| [ConsiderParentMargins](../../groupdocs.watermark/watermark/considerparentmargins) { get; set; } | Haalt op of stelt een waarde in die aangeeft of de grootte en coördinaten van het watermerk worden berekend met inachtneming van de marges van de bovenliggende container. |
| [Font](../../groupdocs.watermark.watermarks/textwatermark/font) { get; set; } | Gets of sets het lettertype van de tekst. |
| [ForegroundColor](../../groupdocs.watermark.watermarks/textwatermark/foregroundcolor) { get; set; } | Gets of sets de voorgrondkleur van de tekst. |
| [Height](../../groupdocs.watermark/watermark/height) { get; set; } | Gets of sets de gewenste hoogte van deze [`Watermark`](../../groupdocs.watermark/watermark). |
| [HorizontalAlignment](../../groupdocs.watermark/watermark/horizontalalignment) { get; set; } | Gets of sets de horizontale uitlijning van deze [`Watermark`](../../groupdocs.watermark/watermark). |
| [IsBackground](../../groupdocs.watermark/watermark/isbackground) { get; set; } | Haalt op of stelt een waarde in die aangeeft of het watermerk op de achtergrond moet worden geplaatst. |
| [Margins](../../groupdocs.watermark/watermark/margins) { get; set; } | Gets of sets de marge-instellingen van deze [`Watermark`](../../groupdocs.watermark/watermark). |
| [Opacity](../../groupdocs.watermark/watermark/opacity) { get; set; } | Gets of sets de doorzichtigheid van deze [`Watermark`](../../groupdocs.watermark/watermark). |
| [Padding](../../groupdocs.watermark.watermarks/textwatermark/padding) { get; set; } | Gets of sets de opvulinstellingen van deze [`TextWatermark`](../textwatermark). Deze eigenschap is alleen van toepassing op afbeeldingsbestanden. |
| [PagesSetup](../../groupdocs.watermark/watermark/pagessetup) { get; set; } | Gets of sets de pagina-instellingsinstellingen van deze [`Watermark`](../../groupdocs.watermark/watermark). |
| [RotateAngle](../../groupdocs.watermark/watermark/rotateangle) { get; set; } | Haalt op of stelt de rotatiehoek van deze [`Watermark`](../../groupdocs.watermark/watermark) in graden in. |
| [SaveResultInMetadata](../../groupdocs.watermark/watermark/saveresultinmetadata) { get; set; } | Haalt op of stelt een waarde in die aangeeft of informatie over toegevoegde watermerken moet worden opgeslagen in de documentmetadata. |
| [ScaleFactor](../../groupdocs.watermark/watermark/scalefactor) { get; set; } | Haalt op of stelt een waarde in die bepaalt hoe de grootte van het watermerk afhangt van de grootte van het bovenliggende element. |
| [SizingType](../../groupdocs.watermark/watermark/sizingtype) { get; set; } | Haalt op of stelt een waarde in die een manier specificeert waarop het watermerk moet worden geschaald. |
| [Text](../../groupdocs.watermark.watermarks/textwatermark/text) { get; set; } | Haalt op of stelt de tekst in die als watermerk wordt gebruikt. |
| [TextAlignment](../../groupdocs.watermark.watermarks/textwatermark/textalignment) { get; set; } | Haalt op of stelt de uitlijning van de watermerktekst in. |
| [TileOptions](../../groupdocs.watermark/watermark/tileoptions) { get; set; } | Haalt op of stelt opties in om een herhaald watermerk te definiëren |
| [VerticalAlignment](../../groupdocs.watermark/watermark/verticalalignment) { get; set; } | Haalt op of stelt de verticale uitlijning van deze [`Watermark`](../../groupdocs.watermark/watermark) in. |
| [Width](../../groupdocs.watermark/watermark/width) { get; set; } | Haalt op of stelt de gewenste breedte van deze [`Watermark`](../../groupdocs.watermark/watermark) in. |
| [X](../../groupdocs.watermark/watermark/x) { get; set; } | Haalt op of stelt de x-coördinaat van deze [`Watermark`](../../groupdocs.watermark/watermark) in. |
| [Y](../../groupdocs.watermark/watermark/y) { get; set; } | Haalt op of stelt de y-coördinaat van deze [`Watermark`](../../groupdocs.watermark/watermark) in. |

### Opmerkingen

**Learn more:**

* [Adding text watermarks](https://docs.groupdocs.com/display/watermarknet/Adding+text+watermarks)

### Voorbeelden

Schaal het tekstwatermerk afhankelijk van de grootte van de ouder.

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

### Zie ook

* class [Watermark](../../groupdocs.watermark/watermark)
* namespace [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
