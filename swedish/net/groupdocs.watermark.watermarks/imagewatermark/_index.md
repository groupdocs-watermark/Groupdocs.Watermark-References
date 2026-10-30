---
title: "ImageWatermark"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar en bildvattenstämpel."
type: docs
weight: 3190
url: /sv/net/groupdocs.watermark.watermarks/imagewatermark/
---
## ImageWatermark class

Representerar en bildvattenstämpel.

```csharp
public sealed class ImageWatermark : Watermark, IDisposable
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ImageWatermark](imagewatermark#constructor)(Stream) | Initierar en ny instans av klassen [`ImageWatermark`](../imagewatermark) med en specificerad ström. |
| [ImageWatermark](imagewatermark#constructor_1)(string) | Initierar en ny instans av klassen [`ImageWatermark`](../imagewatermark) med en specificerad filsökväg. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ConsiderParentMargins](../../groupdocs.watermark/watermark/considerparentmargins) { get; set; } | Hämtar eller anger ett värde som indikerar om vattenmärkets storlek och koordinater beräknas med hänsyn till föräldramarginaler. |
| [Height](../../groupdocs.watermark/watermark/height) { get; set; } | Hämtar eller anger önskad höjd för denna [`Watermark`](../../groupdocs.watermark/watermark). |
| [HorizontalAlignment](../../groupdocs.watermark/watermark/horizontalalignment) { get; set; } | Hämtar eller anger den horisontella justeringen för denna [`Watermark`](../../groupdocs.watermark/watermark). |
| [IsBackground](../../groupdocs.watermark/watermark/isbackground) { get; set; } | Hämtar eller anger ett värde som indikerar om vattenmärket ska placeras i bakgrunden. |
| [Margins](../../groupdocs.watermark/watermark/margins) { get; set; } | Hämtar eller anger marginalinställningarna för denna [`Watermark`](../../groupdocs.watermark/watermark). |
| [Opacity](../../groupdocs.watermark/watermark/opacity) { get; set; } | Hämtar eller anger opaciteten för denna [`Watermark`](../../groupdocs.watermark/watermark). |
| [PagesSetup](../../groupdocs.watermark/watermark/pagessetup) { get; set; } | Hämtar eller anger sidinställningarna för denna [`Watermark`](../../groupdocs.watermark/watermark). |
| [RotateAngle](../../groupdocs.watermark/watermark/rotateangle) { get; set; } | Hämtar eller anger rotationsvinkeln för denna [`Watermark`](../../groupdocs.watermark/watermark) i grader. |
| [SaveResultInMetadata](../../groupdocs.watermark/watermark/saveresultinmetadata) { get; set; } | Hämtar eller anger ett värde som indikerar om information om tillagda vattenmärken ska sparas i dokumentets metadata. |
| [ScaleFactor](../../groupdocs.watermark/watermark/scalefactor) { get; set; } | Hämtar eller anger ett värde som definierar hur vattenmärkesstorleken beror på förälderns storlek. |
| [SizingType](../../groupdocs.watermark/watermark/sizingtype) { get; set; } | Hämtar eller anger ett värde som specificerar hur vattenmärket ska storleksanpassas. |
| [TileOptions](../../groupdocs.watermark/watermark/tileoptions) { get; set; } | Hämtar eller anger alternativ för att definiera upprepade vattenmärken |
| [VerticalAlignment](../../groupdocs.watermark/watermark/verticalalignment) { get; set; } | Hämtar eller anger den vertikala justeringen för detta [`Watermark`](../../groupdocs.watermark/watermark). |
| [Width](../../groupdocs.watermark/watermark/width) { get; set; } | Hämtar eller anger den önskade bredden för detta [`Watermark`](../../groupdocs.watermark/watermark). |
| [X](../../groupdocs.watermark/watermark/x) { get; set; } | Hämtar eller anger x-koordinaten för detta [`Watermark`](../../groupdocs.watermark/watermark). |
| [Y](../../groupdocs.watermark/watermark/y) { get; set; } | Hämtar eller anger y-koordinaten för detta [`Watermark`](../../groupdocs.watermark/watermark). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../groupdocs.watermark.watermarks/imagewatermark/dispose)() | Avslutar den aktuella instansen. |

### Anmärkningar

**Learn more:**

* [Adding image watermarks](https://docs.groupdocs.com/display/watermarknet/Adding+image+watermarks)

### Exempel

Lägg till bildvattenstämpel i ett dokument av någon stödd typ.

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

### Se även

* class [Watermark](../../groupdocs.watermark/watermark)
* namespace [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
