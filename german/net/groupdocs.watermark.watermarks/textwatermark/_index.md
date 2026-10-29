---
title: "TextWatermark"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt ein Text‑Wasserzeichen dar."
type: docs
weight: 3320
url: /de/net/groupdocs.watermark.watermarks/textwatermark/
---
## TextWatermark class

Stellt ein Text‑Wasserzeichen dar.

```csharp
public class TextWatermark : Watermark
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TextWatermark](textwatermark)(string, Font) | Initialisiert eine neue Instanz der [`TextWatermark`](../textwatermark)-Klasse mit einem angegebenen Text und einer Schriftart. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BackgroundColor](../../groupdocs.watermark.watermarks/textwatermark/backgroundcolor) { get; set; } | Liest oder setzt die Hintergrundfarbe des Textes. |
| [ConsiderParentMargins](../../groupdocs.watermark/watermark/considerparentmargins) { get; set; } | Liest oder setzt einen Wert, der angibt, ob die Größe und Koordinaten des Wasserzeichens unter Berücksichtigung der übergeordneten Ränder berechnet werden. |
| [Font](../../groupdocs.watermark.watermarks/textwatermark/font) { get; set; } | Liest oder setzt die Schriftart des Textes. |
| [ForegroundColor](../../groupdocs.watermark.watermarks/textwatermark/foregroundcolor) { get; set; } | Liest oder setzt die Vordergrundfarbe des Textes. |
| [Height](../../groupdocs.watermark/watermark/height) { get; set; } | Liest oder setzt die gewünschte Höhe dieses [`Watermark`](../../groupdocs.watermark/watermark). |
| [HorizontalAlignment](../../groupdocs.watermark/watermark/horizontalalignment) { get; set; } | Liest oder setzt die horizontale Ausrichtung dieses [`Watermark`](../../groupdocs.watermark/watermark). |
| [IsBackground](../../groupdocs.watermark/watermark/isbackground) { get; set; } | Liest oder setzt einen Wert, der angibt, ob das Wasserzeichen im Hintergrund platziert werden soll. |
| [Margins](../../groupdocs.watermark/watermark/margins) { get; set; } | Liest oder setzt die Rand‑Einstellungen dieses [`Watermark`](../../groupdocs.watermark/watermark). |
| [Opacity](../../groupdocs.watermark/watermark/opacity) { get; set; } | Liest oder setzt die Deckkraft dieses [`Watermark`](../../groupdocs.watermark/watermark). |
| [Padding](../../groupdocs.watermark.watermarks/textwatermark/padding) { get; set; } | Liest oder setzt die Innenabstand‑Einstellungen dieses [`TextWatermark`](../textwatermark). Diese Eigenschaft gilt nur für Bilddateien. |
| [PagesSetup](../../groupdocs.watermark/watermark/pagessetup) { get; set; } | Liest oder setzt die Seiteneinrichtungs‑Einstellungen dieses [`Watermark`](../../groupdocs.watermark/watermark). |
| [RotateAngle](../../groupdocs.watermark/watermark/rotateangle) { get; set; } | Liest oder setzt den Rotationswinkel dieses [`Watermark`](../../groupdocs.watermark/watermark) in Grad. |
| [SaveResultInMetadata](../../groupdocs.watermark/watermark/saveresultinmetadata) { get; set; } | Liest oder setzt einen Wert, der angibt, ob Informationen über hinzugefügte Wasserzeichen in den Dokumentmetadaten gespeichert werden sollen. |
| [ScaleFactor](../../groupdocs.watermark/watermark/scalefactor) { get; set; } | Liest oder setzt einen Wert, der definiert, wie die Größe des Wasserzeichens von der übergeordneten Größe abhängt. |
| [SizingType](../../groupdocs.watermark/watermark/sizingtype) { get; set; } | Liest oder setzt einen Wert, der angibt, wie das Wasserzeichen dimensioniert werden soll. |
| [Text](../../groupdocs.watermark.watermarks/textwatermark/text) { get; set; } | Liest oder setzt den Text, der als Wasserzeichen verwendet wird. |
| [TextAlignment](../../groupdocs.watermark.watermarks/textwatermark/textalignment) { get; set; } | Liest oder setzt die Ausrichtung des Wasserzeichentextes. |
| [TileOptions](../../groupdocs.watermark/watermark/tileoptions) { get; set; } | Liest oder setzt Optionen zur Definition wiederholter Wasserzeichen |
| [VerticalAlignment](../../groupdocs.watermark/watermark/verticalalignment) { get; set; } | Liest oder setzt die vertikale Ausrichtung dieses [`Watermark`](../../groupdocs.watermark/watermark). |
| [Width](../../groupdocs.watermark/watermark/width) { get; set; } | Liest oder setzt die gewünschte Breite dieses [`Watermark`](../../groupdocs.watermark/watermark). |
| [X](../../groupdocs.watermark/watermark/x) { get; set; } | Liest oder setzt die x-Koordinate dieses [`Watermark`](../../groupdocs.watermark/watermark). |
| [Y](../../groupdocs.watermark/watermark/y) { get; set; } | Liest oder setzt die y-Koordinate dieses [`Watermark`](../../groupdocs.watermark/watermark). |

### Hinweise

**Learn more:**

* [Adding text watermarks](https://docs.groupdocs.com/display/watermarknet/Adding+text+watermarks)

### Beispiele

Skaliere das Textwasserzeichen abhängig von der Größe des übergeordneten Elements.

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
* namespace [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
