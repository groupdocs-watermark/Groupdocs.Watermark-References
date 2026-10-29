---
title: "ImageWatermark"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt ein Bild‑Wasserzeichen dar."
type: docs
weight: 3190
url: /de/net/groupdocs.watermark.watermarks/imagewatermark/
---
## ImageWatermark class

Stellt ein Bild‑Wasserzeichen dar.

```csharp
public sealed class ImageWatermark : Watermark, IDisposable
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ImageWatermark](imagewatermark#constructor)(Stream) | Initialisiert eine neue Instanz der [`ImageWatermark`](../imagewatermark)-Klasse mit einem angegebenen Stream. |
| [ImageWatermark](imagewatermark#constructor_1)(string) | Initialisiert eine neue Instanz der [`ImageWatermark`](../imagewatermark)-Klasse mit einem angegebenen Dateipfad. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ConsiderParentMargins](../../groupdocs.watermark/watermark/considerparentmargins) { get; set; } | Liest oder setzt einen Wert, der angibt, ob die Größe und Koordinaten des Wasserzeichens unter Berücksichtigung der übergeordneten Ränder berechnet werden. |
| [Height](../../groupdocs.watermark/watermark/height) { get; set; } | Liest oder setzt die gewünschte Höhe dieses [`Watermark`](../../groupdocs.watermark/watermark). |
| [HorizontalAlignment](../../groupdocs.watermark/watermark/horizontalalignment) { get; set; } | Liest oder setzt die horizontale Ausrichtung dieses [`Watermark`](../../groupdocs.watermark/watermark). |
| [IsBackground](../../groupdocs.watermark/watermark/isbackground) { get; set; } | Liest oder setzt einen Wert, der angibt, ob das Wasserzeichen im Hintergrund platziert werden soll. |
| [Margins](../../groupdocs.watermark/watermark/margins) { get; set; } | Liest oder setzt die Rand‑Einstellungen dieses [`Watermark`](../../groupdocs.watermark/watermark). |
| [Opacity](../../groupdocs.watermark/watermark/opacity) { get; set; } | Liest oder setzt die Deckkraft dieses [`Watermark`](../../groupdocs.watermark/watermark). |
| [PagesSetup](../../groupdocs.watermark/watermark/pagessetup) { get; set; } | Liest oder setzt die Seiteneinrichtungs‑Einstellungen dieses [`Watermark`](../../groupdocs.watermark/watermark). |
| [RotateAngle](../../groupdocs.watermark/watermark/rotateangle) { get; set; } | Liest oder setzt den Rotationswinkel dieses [`Watermark`](../../groupdocs.watermark/watermark) in Grad. |
| [SaveResultInMetadata](../../groupdocs.watermark/watermark/saveresultinmetadata) { get; set; } | Liest oder setzt einen Wert, der angibt, ob Informationen über hinzugefügte Wasserzeichen in den Dokumentmetadaten gespeichert werden sollen. |
| [ScaleFactor](../../groupdocs.watermark/watermark/scalefactor) { get; set; } | Liest oder setzt einen Wert, der definiert, wie die Größe des Wasserzeichens von der übergeordneten Größe abhängt. |
| [SizingType](../../groupdocs.watermark/watermark/sizingtype) { get; set; } | Liest oder setzt einen Wert, der angibt, wie das Wasserzeichen dimensioniert werden soll. |
| [TileOptions](../../groupdocs.watermark/watermark/tileoptions) { get; set; } | Liest oder setzt Optionen zur Definition wiederholter Wasserzeichen |
| [VerticalAlignment](../../groupdocs.watermark/watermark/verticalalignment) { get; set; } | Liest oder setzt die vertikale Ausrichtung dieses [`Watermark`](../../groupdocs.watermark/watermark). |
| [Width](../../groupdocs.watermark/watermark/width) { get; set; } | Liest oder setzt die gewünschte Breite dieses [`Watermark`](../../groupdocs.watermark/watermark). |
| [X](../../groupdocs.watermark/watermark/x) { get; set; } | Liest oder setzt die x-Koordinate dieses [`Watermark`](../../groupdocs.watermark/watermark). |
| [Y](../../groupdocs.watermark/watermark/y) { get; set; } | Liest oder setzt die y-Koordinate dieses [`Watermark`](../../groupdocs.watermark/watermark). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../groupdocs.watermark.watermarks/imagewatermark/dispose)() | Gibt die aktuelle Instanz frei. |

### Hinweise

**Learn more:**

* [Adding image watermarks](https://docs.groupdocs.com/display/watermarknet/Adding+image+watermarks)

### Beispiele

Fügen Sie ein Bildwasserzeichen zu einem Dokument eines beliebigen unterstützten Typs hinzu.

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

### Siehe auch

* class [Watermark](../../groupdocs.watermark/watermark)
* namespace [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
