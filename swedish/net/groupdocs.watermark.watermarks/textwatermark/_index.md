---
title: "TextWatermark"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar en textvattenstämpel."
type: docs
weight: 3320
url: /sv/net/groupdocs.watermark.watermarks/textwatermark/
---
## TextWatermark class

Representerar en textvattenstämpel.

```csharp
public class TextWatermark : Watermark
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextWatermark](textwatermark)(string, Font) | Initierar en ny instans av klassen [`TextWatermark`](../textwatermark) med en specificerad text och ett teckensnitt. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BackgroundColor](../../groupdocs.watermark.watermarks/textwatermark/backgroundcolor) { get; set; } | Hämtar eller anger bakgrundsfärgen för texten. |
| [ConsiderParentMargins](../../groupdocs.watermark/watermark/considerparentmargins) { get; set; } | Hämtar eller anger ett värde som indikerar om vattenmärkets storlek och koordinater beräknas med hänsyn till föräldramarginaler. |
| [Font](../../groupdocs.watermark.watermarks/textwatermark/font) { get; set; } | Hämtar eller anger teckensnittet för texten. |
| [ForegroundColor](../../groupdocs.watermark.watermarks/textwatermark/foregroundcolor) { get; set; } | Hämtar eller anger förgrundsfärgen för texten. |
| [Height](../../groupdocs.watermark/watermark/height) { get; set; } | Hämtar eller anger önskad höjd för denna [`Watermark`](../../groupdocs.watermark/watermark). |
| [HorizontalAlignment](../../groupdocs.watermark/watermark/horizontalalignment) { get; set; } | Hämtar eller anger den horisontella justeringen för denna [`Watermark`](../../groupdocs.watermark/watermark). |
| [IsBackground](../../groupdocs.watermark/watermark/isbackground) { get; set; } | Hämtar eller anger ett värde som indikerar om vattenmärket ska placeras i bakgrunden. |
| [Margins](../../groupdocs.watermark/watermark/margins) { get; set; } | Hämtar eller anger marginalinställningarna för denna [`Watermark`](../../groupdocs.watermark/watermark). |
| [Opacity](../../groupdocs.watermark/watermark/opacity) { get; set; } | Hämtar eller anger opaciteten för denna [`Watermark`](../../groupdocs.watermark/watermark). |
| [Padding](../../groupdocs.watermark.watermarks/textwatermark/padding) { get; set; } | Hämtar eller anger utfyllnadsinställningarna för denna [`TextWatermark`](../textwatermark). Denna egenskap gäller endast för bildfiler. |
| [PagesSetup](../../groupdocs.watermark/watermark/pagessetup) { get; set; } | Hämtar eller anger sidinställningarna för denna [`Watermark`](../../groupdocs.watermark/watermark). |
| [RotateAngle](../../groupdocs.watermark/watermark/rotateangle) { get; set; } | Hämtar eller anger rotationsvinkeln för denna [`Watermark`](../../groupdocs.watermark/watermark) i grader. |
| [SaveResultInMetadata](../../groupdocs.watermark/watermark/saveresultinmetadata) { get; set; } | Hämtar eller anger ett värde som indikerar om information om tillagda vattenmärken ska sparas i dokumentets metadata. |
| [ScaleFactor](../../groupdocs.watermark/watermark/scalefactor) { get; set; } | Hämtar eller anger ett värde som definierar hur vattenmärkesstorleken beror på förälderns storlek. |
| [SizingType](../../groupdocs.watermark/watermark/sizingtype) { get; set; } | Hämtar eller anger ett värde som specificerar hur vattenmärket ska storleksanpassas. |
| [Text](../../groupdocs.watermark.watermarks/textwatermark/text) { get; set; } | Hämtar eller anger texten som ska användas som vattenstämpel. |
| [TextAlignment](../../groupdocs.watermark.watermarks/textwatermark/textalignment) { get; set; } | Hämtar eller anger justeringen av vattenstämpeltexten. |
| [TileOptions](../../groupdocs.watermark/watermark/tileoptions) { get; set; } | Hämtar eller anger alternativ för att definiera upprepade vattenmärken |
| [VerticalAlignment](../../groupdocs.watermark/watermark/verticalalignment) { get; set; } | Hämtar eller anger den vertikala justeringen för detta [`Watermark`](../../groupdocs.watermark/watermark). |
| [Width](../../groupdocs.watermark/watermark/width) { get; set; } | Hämtar eller anger den önskade bredden för detta [`Watermark`](../../groupdocs.watermark/watermark). |
| [X](../../groupdocs.watermark/watermark/x) { get; set; } | Hämtar eller anger x-koordinaten för detta [`Watermark`](../../groupdocs.watermark/watermark). |
| [Y](../../groupdocs.watermark/watermark/y) { get; set; } | Hämtar eller anger y-koordinaten för detta [`Watermark`](../../groupdocs.watermark/watermark). |

### Anmärkningar

**Learn more:**

* [Adding text watermarks](https://docs.groupdocs.com/display/watermarknet/Adding+text+watermarks)

### Exempel

Skala textvattenstämpeln beroende på förälderns storlek.

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

### Se även

* class [Watermark](../../groupdocs.watermark/watermark)
* namespace [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
