---
title: "TiffImageWatermarkOptions"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt Optionen zum Hinzufügen von Wasserzeichen dar, wenn ein Wasserzeichen zu einem TIFF‑Bild hinzugefügt wird."
type: docs
weight: 1900
url: /de/net/groupdocs.watermark.options.image/tiffimagewatermarkoptions/
---
## TiffImageWatermarkOptions class

Stellt Optionen zum Hinzufügen von Wasserzeichen dar, wenn ein Wasserzeichen zu einem TIFF‑Bild hinzugefügt wird.

```csharp
public sealed class TiffImageWatermarkOptions : MultiframeImageWatermarkOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TiffImageWatermarkOptions](tiffimagewatermarkoptions#constructor)() | Initialisiert eine neue Instanz der [`TiffImageWatermarkOptions`](../tiffimagewatermarkoptions) Klasse. |
| [TiffImageWatermarkOptions](tiffimagewatermarkoptions#constructor_1)(int) | Initialisiert eine neue Instanz der [`TiffImageWatermarkOptions`](../tiffimagewatermarkoptions) Klasse mit einem angegebenen Index des Frames. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [FrameIndex](../../groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frameindex) { get; set; } | Liest oder setzt den Index des Frames, dem das Wasserzeichen hinzugefügt wird. |

### Hinweise

**Learn more:**

* [Add watermarks to images](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images)

### Beispiele

Fügt einem bestimmten Frame eines TIFF-Bildes ein Wasserzeichen hinzu.

```csharp
TiffImageLoadOptions loadOptions = new TiffImageLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\test.tiff", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));

    TiffImageWatermarkOptions options = new TiffImageWatermarkOptions();
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
