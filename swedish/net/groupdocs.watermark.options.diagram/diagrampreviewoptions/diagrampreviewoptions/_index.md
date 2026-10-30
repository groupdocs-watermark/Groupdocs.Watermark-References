---
title: "DiagramPreviewOptions"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Initierar en ny instans av DiagramPreviewOptionsgroupdocs.watermark.options.diagram/diagrampreviewoptions-klassen som orsakar att utdataflödet stängs."
type: docs
weight: 10
url: /sv/net/groupdocs.watermark.options.diagram/diagrampreviewoptions/diagrampreviewoptions/
---
## DiagramPreviewOptions(CreatePageStream) {#constructor}

Initierar en ny instans av klassen [`DiagramPreviewOptions`](../../diagrampreviewoptions) vilket får att utdataflödet stängs.

```csharp
public DiagramPreviewOptions(CreatePageStream createPageStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | CreatePageStream | Skapar ett flöde för en specifik sidoförhandsgranskning. |

### Se även

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [DiagramPreviewOptions](../../diagrampreviewoptions)
* namespace [GroupDocs.Watermark.Options.Diagram](../../../groupdocs.watermark.options.diagram)
* assembly [GroupDocs.Watermark](../../../)

---

## DiagramPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Initierar en ny instans av klassen [`DiagramPreviewOptions`](../../diagrampreviewoptions) vilket får att utdataflödet returneras till klienten för vidare användning.

```csharp
public DiagramPreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | CreatePageStream | Skapar ett flöde för en specifik sidoförhandsgranskning. |
| releasePageStream | ReleasePageStream | Meddelar att sidoförhandsgranskningens generering är klar och hämtar utdataflödet. |

### Se även

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [DiagramPreviewOptions](../../diagrampreviewoptions)
* namespace [GroupDocs.Watermark.Options.Diagram](../../../groupdocs.watermark.options.diagram)
* assembly [GroupDocs.Watermark](../../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
