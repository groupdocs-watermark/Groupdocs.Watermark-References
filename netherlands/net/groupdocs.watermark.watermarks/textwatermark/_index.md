---
title: TextWatermark
second_title: GroupDocs.Watermark voor .NET API-referentie
description: Vertegenwoordigt een tekstwatermerk.
type: docs
weight: 3160
url: /nl/net/groupdocs.watermark.watermarks/textwatermark/
---
## TextWatermark class

Vertegenwoordigt een tekstwatermerk.

```csharp
public class TextWatermark : Watermark
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [TextWatermark](textwatermark)(string, Font) | Initialiseert een nieuw exemplaar van het[`TextWatermark`](../textwatermark)klasse met een opgegeven tekst en een lettertype. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BackgroundColor](../../groupdocs.watermark.watermarks/textwatermark/backgroundcolor) { get; set; } | Haalt de achtergrondkleur van de tekst op of stelt deze in. |
| [ConsiderParentMargins](../../groupdocs.watermark/watermark/considerparentmargins) { get; set; } | Haalt of stelt een waarde in die aangeeft of de watermerkgrootte en coördinaten berekend zijn rekening houdend met bovenliggende marges. |
| [Font](../../groupdocs.watermark.watermarks/textwatermark/font) { get; set; } | Hiermee wordt het lettertype van de tekst opgehaald of ingesteld. |
| [ForegroundColor](../../groupdocs.watermark.watermarks/textwatermark/foregroundcolor) { get; set; } | Haalt de voorgrondkleur van de tekst op of stelt deze in. |
| [Height](../../groupdocs.watermark/watermark/height) { get; set; } | Haalt of stelt de gewenste hoogte hiervan in[`Watermark`](../../groupdocs.watermark/watermark) . |
| [HorizontalAlignment](../../groupdocs.watermark/watermark/horizontalalignment) { get; set; } | Haalt of stelt de horizontale uitlijning hiervan in[`Watermark`](../../groupdocs.watermark/watermark) . |
| [IsBackground](../../groupdocs.watermark/watermark/isbackground) { get; set; } | Haalt of stelt een waarde in die aangeeft of het watermerk op de achtergrond moet worden geplaatst. |
| [Margins](../../groupdocs.watermark/watermark/margins) { get; set; } | Haalt of stelt de marge-instellingen hiervan in[`Watermark`](../../groupdocs.watermark/watermark) . |
| [Opacity](../../groupdocs.watermark/watermark/opacity) { get; set; } | Haalt of stelt de dekking hiervan in[`Watermark`](../../groupdocs.watermark/watermark) . |
| [Padding](../../groupdocs.watermark.watermarks/textwatermark/padding) { get; set; } | Haalt of stelt de padding-instellingen hiervan in[`TextWatermark`](../textwatermark) . Deze eigenschap is alleen van toepassing op afbeeldingsbestanden. |
| [RotateAngle](../../groupdocs.watermark/watermark/rotateangle) { get; set; } | Haalt of stelt de draaihoek hiervan in[`Watermark`](../../groupdocs.watermark/watermark) in graden. |
| [ScaleFactor](../../groupdocs.watermark/watermark/scalefactor) { get; set; } | Hiermee wordt een waarde opgehaald of ingesteld die bepaalt hoe de watermerkgrootte afhangt van de bovenliggende grootte. |
| [SizingType](../../groupdocs.watermark/watermark/sizingtype) { get; set; } | Haalt of stelt een waarde in die specificeert hoe watermerk moet worden aangepast. |
| [Text](../../groupdocs.watermark.watermarks/textwatermark/text) { get; set; } | Haalt de tekst op of stelt deze in om als watermerk te gebruiken. |
| [TextAlignment](../../groupdocs.watermark.watermarks/textwatermark/textalignment) { get; set; } | Haalt of stelt de tekstuitlijning van het watermerk in. |
| [VerticalAlignment](../../groupdocs.watermark/watermark/verticalalignment) { get; set; } | Haalt of stelt de verticale uitlijning hiervan in[`Watermark`](../../groupdocs.watermark/watermark) . |
| [Width](../../groupdocs.watermark/watermark/width) { get; set; } | Haalt of stelt de gewenste breedte hiervan in[`Watermark`](../../groupdocs.watermark/watermark) . |
| [X](../../groupdocs.watermark/watermark/x) { get; set; } | Haalt of stelt de x-coördinaat hiervan in[`Watermark`](../../groupdocs.watermark/watermark) . |
| [Y](../../groupdocs.watermark/watermark/y) { get; set; } | Haalt of stelt de y-coördinaat hiervan in[`Watermark`](../../groupdocs.watermark/watermark) . |

### Opmerkingen

**Kom meer te weten:**

* [Tekstwatermerken toevoegen](https://docs.groupdocs.com/display/watermarknet/Adding+text+watermarks)

### Voorbeelden

Schaal het tekstwatermerk afhankelijk van de bovenliggende grootte.

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
* naamruimte [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* montage [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
