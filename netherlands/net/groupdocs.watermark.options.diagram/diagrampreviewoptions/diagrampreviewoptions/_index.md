---
title: DiagramPreviewOptions
second_title: GroupDocs.Watermark voor .NET API-referentie
description: Initialiseert een nieuw exemplaar van hetDiagramPreviewOptionsgroupdocs.watermark.options.diagram/diagrampreviewoptions klasse waardoor de uitvoerstroom wordt gesloten.
type: docs
weight: 10
url: /nl/net/groupdocs.watermark.options.diagram/diagrampreviewoptions/diagrampreviewoptions/
---
## DiagramPreviewOptions(CreatePageStream) {#constructor}

Initialiseert een nieuw exemplaar van het[`DiagramPreviewOptions`](../../diagrampreviewoptions) klasse waardoor de uitvoerstroom wordt gesloten.

```csharp
public DiagramPreviewOptions(CreatePageStream createPageStream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createPageStream | CreatePageStream | Creëert een stream voor een specifiek paginavoorbeeld. |

### Zie ook

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [DiagramPreviewOptions](../../diagrampreviewoptions)
* naamruimte [GroupDocs.Watermark.Options.Diagram](../../diagrampreviewoptions)
* montage [GroupDocs.Watermark](../../../)

---

## DiagramPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Initialiseert een nieuw exemplaar van[`DiagramPreviewOptions`](../../diagrampreviewoptions) class waardoor de uitvoerstroom wordt teruggestuurd naar de client voor verder gebruik.

```csharp
public DiagramPreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createPageStream | CreatePageStream | Creëert een stream voor een specifiek paginavoorbeeld. |
| releasePageStream | ReleasePageStream | Geeft aan dat het genereren van het paginavoorbeeld is voltooid en ontvangt de uitvoerstroom. |

### Zie ook

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [DiagramPreviewOptions](../../diagrampreviewoptions)
* naamruimte [GroupDocs.Watermark.Options.Diagram](../../diagrampreviewoptions)
* montage [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->