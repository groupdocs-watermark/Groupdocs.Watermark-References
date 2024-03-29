---
title: DiagramShapeWatermarkOptions
second_title: GroupDocs.Watermark für .NET-API-Referenz
description: Stellt Optionen zum Hinzufügen von Wasserzeichen dar wenn Formwasserzeichen zu einem VisioDokument hinzugefügt werden.
type: docs
weight: 1680
url: /de/net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/
---
## DiagramShapeWatermarkOptions class

Stellt Optionen zum Hinzufügen von Wasserzeichen dar, wenn Formwasserzeichen zu einem Visio-Dokument hinzugefügt werden.

```csharp
public sealed class DiagramShapeWatermarkOptions : DiagramWatermarkOptions
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [DiagramShapeWatermarkOptions](diagramshapewatermarkoptions)() | Initialisiert eine neue Instanz von[`DiagramShapeWatermarkOptions`](../diagramshapewatermarkoptions) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [IsLocked](../../groupdocs.watermark.options.diagram/diagramwatermarkoptions/islocked) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob eine Bearbeitung der Form in Visio verboten ist. |
| [PlacementType](../../groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/placementtype) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, zu welchen Seiten ein Wasserzeichen hinzugefügt werden soll. |

### Bemerkungen

**Erfahren Sie mehr:**

* [Fügen Sie Diagrammdokumenten Wasserzeichen hinzu](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents)

### Beispiele

Geschütztes Wasserzeichen zu allen Seiten des Visio-Dokuments hinzufügen.

```csharp
DiagramLoadOptions loadOptions = new DiagramLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.vsdx", loadOptions))
{
    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));

    DiagramShapeWatermarkOptions options = new DiagramShapeWatermarkOptions();
    options.IsLocked = true;
    options.PlacementType = DiagramWatermarkPlacementType.AllPages; // Standard

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Siehe auch

* class [DiagramWatermarkOptions](../diagramwatermarkoptions)
* namensraum [GroupDocs.Watermark.Options.Diagram](../../groupdocs.watermark.options.diagram)
* Montage [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
