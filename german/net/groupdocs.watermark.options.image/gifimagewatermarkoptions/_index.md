---
title: "GifImageWatermarkOptions"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt Optionen zum Hinzufügen von Wasserzeichen dar, wenn ein Wasserzeichen zu einem GIF‑Bild hinzugefügt wird."
type: docs
weight: 1830
url: /de/net/groupdocs.watermark.options.image/gifimagewatermarkoptions/
---
## GifImageWatermarkOptions class

Stellt Optionen zum Hinzufügen von Wasserzeichen dar, wenn ein Wasserzeichen zu einem GIF‑Bild hinzugefügt wird.

```csharp
public sealed class GifImageWatermarkOptions : MultiframeImageWatermarkOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [GifImageWatermarkOptions](gifimagewatermarkoptions#constructor)() | Initialisiert eine neue Instanz der [`GifImageWatermarkOptions`](../gifimagewatermarkoptions) Klasse. |
| [GifImageWatermarkOptions](gifimagewatermarkoptions#constructor_1)(int) | Initialisiert eine neue Instanz der [`GifImageWatermarkOptions`](../gifimagewatermarkoptions) Klasse mit einem angegebenen Index eines Frames. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [FrameIndex](../../groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frameindex) { get; set; } | Liest oder setzt den Index des Frames, dem das Wasserzeichen hinzugefügt wird. |

### Hinweise

**Learn more:**

* [Add watermarks to images](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images)

### Beispiele

Fügt einem bestimmten Frame eines GIF-Bildes ein Wasserzeichen hinzu.

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

### Siehe auch

* class [MultiframeImageWatermarkOptions](../multiframeimagewatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Image](../../groupdocs.watermark.options.image)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
