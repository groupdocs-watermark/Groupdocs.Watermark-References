---
title: "MultiframeImageWatermarkOptions"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt Optionen zum Hinzufügen von Wasserzeichen dar, wenn ein Wasserzeichen zu einem mehrrahmigen Bild hinzugefügt wird."
type: docs
weight: 1870
url: /de/net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/
---
## MultiframeImageWatermarkOptions class

Stellt Optionen zum Hinzufügen von Wasserzeichen dar, wenn ein Wasserzeichen zu einem mehrframe‑Bild hinzugefügt wird.

```csharp
public class MultiframeImageWatermarkOptions : WatermarkOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MultiframeImageWatermarkOptions](multiframeimagewatermarkoptions#constructor)() | Initialisiert eine neue Instanz der [`MultiframeImageWatermarkOptions`](../multiframeimagewatermarkoptions)-Klasse. |
| [MultiframeImageWatermarkOptions](multiframeimagewatermarkoptions#constructor_1)(int) | Initialisiert eine neue Instanz der [`MultiframeImageWatermarkOptions`](../multiframeimagewatermarkoptions)-Klasse mit einem angegebenen Index des Frames. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [FrameIndex](../../groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frameindex) { get; set; } | Liest oder setzt den Index des Frames, dem das Wasserzeichen hinzugefügt wird. |

### Hinweise

**Learn more:**

* [Add watermarks to images](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images)

### Beispiele

Fügt einem bestimmten Frame eines mehrrahmigen Bildes ein Wasserzeichen hinzu.

```csharp
ImageLoadOptions loadOptions = new ImageLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\test.gif", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));

    MultiframeImageWatermarkOptions options = new MultiframeImageWatermarkOptions();
    options.FrameIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Siehe auch

* class [WatermarkOptions](../../groupdocs.watermark.options/watermarkoptions)
* namespace [GroupDocs.Watermark.Options.Image](../../groupdocs.watermark.options.image)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
