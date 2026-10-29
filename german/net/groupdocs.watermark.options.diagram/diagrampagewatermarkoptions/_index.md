---
title: "DiagramPageWatermarkOptions"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt Optionen zum Hinzufügen von Wasserzeichen dar, wenn ein Form‑Wasserzeichen zu einer bestimmten Seite eines Visio‑Dokuments hinzugefügt wird."
type: docs
weight: 1720
url: /de/net/groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/
---
## DiagramPageWatermarkOptions class

Stellt Optionen zum Hinzufügen von Wasserzeichen dar, wenn ein Form‑Wasserzeichen zu einer bestimmten Seite eines Visio‑Dokuments hinzugefügt wird.

```csharp
public sealed class DiagramPageWatermarkOptions : DiagramWatermarkOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [DiagramPageWatermarkOptions](diagrampagewatermarkoptions)() | Initialisiert eine neue Instanz der Klasse [`DiagramPageWatermarkOptions`](../diagrampagewatermarkoptions). |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [IsLocked](../../groupdocs.watermark.options.diagram/diagramwatermarkoptions/islocked) { get; set; } | Liefert oder setzt einen Wert, der angibt, ob das Bearbeiten der Form in Visio verboten ist. |
| [PageIndex](../../groupdocs.watermark.options.diagram/diagrampagewatermarkoptions/pageindex) { get; set; } | Liest oder setzt den Seitenindex, zu dem das Wasserzeichen hinzugefügt werden soll. |

### Hinweise

**Learn more:**

* [Add watermarks to diagram documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents)

### Beispiele

Fügt ein geschütztes Wasserzeichen zur ersten Seite eines Visio-Dokuments hinzu.

```csharp
DiagramLoadOptions loadOptions = new DiagramLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.vsdx", loadOptions))
{
    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));

    DiagramPageWatermarkOptions options = new DiagramPageWatermarkOptions();
    options.IsLocked = true;
    options.PageIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Siehe auch

* class [DiagramWatermarkOptions](../diagramwatermarkoptions)
* namespace [GroupDocs.Watermark.Options.Diagram](../../groupdocs.watermark.options.diagram)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
