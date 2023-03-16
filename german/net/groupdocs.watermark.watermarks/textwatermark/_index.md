---
title: TextWatermark
second_title: GroupDocs.Watermark für .NET-API-Referenz
description: Stellt ein Textwasserzeichen dar.
type: docs
weight: 3160
url: /de/net/groupdocs.watermark.watermarks/textwatermark/
---
## TextWatermark class

Stellt ein Textwasserzeichen dar.

```csharp
public class TextWatermark : Watermark
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [TextWatermark](textwatermark)(string, Font) | Initialisiert eine neue Instanz von[`TextWatermark`](../textwatermark)Klasse mit einem bestimmten Text und einer Schriftart. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BackgroundColor](../../groupdocs.watermark.watermarks/textwatermark/backgroundcolor) { get; set; } | Liest oder setzt die Hintergrundfarbe des Textes. |
| [ConsiderParentMargins](../../groupdocs.watermark/watermark/considerparentmargins) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Größe und die Koordinaten des Wasserzeichens unter Berücksichtigung der übergeordneten Ränder berechnet werden. |
| [Font](../../groupdocs.watermark.watermarks/textwatermark/font) { get; set; } | Ruft die Schriftart des Textes ab oder legt sie fest. |
| [ForegroundColor](../../groupdocs.watermark.watermarks/textwatermark/foregroundcolor) { get; set; } | Ermittelt oder setzt die Vordergrundfarbe des Textes. |
| [Height](../../groupdocs.watermark/watermark/height) { get; set; } | Holt oder setzt die gewünschte Höhe davon[`Watermark`](../../groupdocs.watermark/watermark) . |
| [HorizontalAlignment](../../groupdocs.watermark/watermark/horizontalalignment) { get; set; } | Ermittelt oder setzt die horizontale Ausrichtung davon[`Watermark`](../../groupdocs.watermark/watermark) . |
| [IsBackground](../../groupdocs.watermark/watermark/isbackground) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob das Wasserzeichen im Hintergrund platziert werden soll. |
| [Margins](../../groupdocs.watermark/watermark/margins) { get; set; } | Holt oder setzt die Randeinstellungen davon[`Watermark`](../../groupdocs.watermark/watermark) . |
| [Opacity](../../groupdocs.watermark/watermark/opacity) { get; set; } | Ermittelt oder setzt die Deckkraft davon[`Watermark`](../../groupdocs.watermark/watermark) . |
| [Padding](../../groupdocs.watermark.watermarks/textwatermark/padding) { get; set; } | Holt oder setzt die Padding-Einstellungen davon[`TextWatermark`](../textwatermark) . Diese Eigenschaft gilt nur für Bilddateien. |
| [RotateAngle](../../groupdocs.watermark/watermark/rotateangle) { get; set; } | Holt oder setzt den Rotationswinkel davon[`Watermark`](../../groupdocs.watermark/watermark) in Grad. |
| [ScaleFactor](../../groupdocs.watermark/watermark/scalefactor) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der definiert, wie die Größe des Wasserzeichens von der Größe des übergeordneten Elements abhängt. |
| [SizingType](../../groupdocs.watermark/watermark/sizingtype) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der die Größe des Wasserzeichens angibt. |
| [Text](../../groupdocs.watermark.watermarks/textwatermark/text) { get; set; } | Ruft den als Wasserzeichen zu verwendenden Text ab oder legt ihn fest. |
| [TextAlignment](../../groupdocs.watermark.watermarks/textwatermark/textalignment) { get; set; } | Ruft die Textausrichtung des Wasserzeichens ab oder legt sie fest. |
| [VerticalAlignment](../../groupdocs.watermark/watermark/verticalalignment) { get; set; } | Ermittelt oder setzt die vertikale Ausrichtung davon[`Watermark`](../../groupdocs.watermark/watermark) . |
| [Width](../../groupdocs.watermark/watermark/width) { get; set; } | Ermittelt oder setzt die gewünschte Breite davon[`Watermark`](../../groupdocs.watermark/watermark) . |
| [X](../../groupdocs.watermark/watermark/x) { get; set; } | Holt oder setzt die x-Koordinate davon[`Watermark`](../../groupdocs.watermark/watermark) . |
| [Y](../../groupdocs.watermark/watermark/y) { get; set; } | Holt oder setzt die y-Koordinate davon[`Watermark`](../../groupdocs.watermark/watermark) . |

### Bemerkungen

**Erfahren Sie mehr:**

* [Hinzufügen von Textwasserzeichen](https://docs.groupdocs.com/display/watermarknet/Adding+text+watermarks)

### Beispiele

Skalieren Sie das Textwasserzeichen abhängig von der übergeordneten Größe.

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

### Siehe auch

* class [Watermark](../../groupdocs.watermark/watermark)
* namensraum [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* Montage [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
