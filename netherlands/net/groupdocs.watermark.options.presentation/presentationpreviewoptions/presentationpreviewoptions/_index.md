---
title: "PresentationPreviewOptions"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Initialiseert een nieuw exemplaar van de PresentationPreviewOptionsgroupdocs.watermark.options.presentation/presentationpreviewoptions klasse waardoor de uitvoerstroom wordt gesloten."
type: docs
weight: 10
url: /nl/net/groupdocs.watermark.options.presentation/presentationpreviewoptions/presentationpreviewoptions/
---
## PresentationPreviewOptions(CreatePageStream) {#constructor}

Initialiseert een nieuw exemplaar van de [`PresentationPreviewOptions`](../../presentationpreviewoptions) klasse waardoor de uitvoerstroom wordt gesloten.

```csharp
public PresentationPreviewOptions(CreatePageStream createPageStream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createPageStream | CreatePageStream | Maakt een stroom voor een specifieke paginavoorvertoning. |

### Zie ook

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [PresentationPreviewOptions](../../presentationpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Presentation](../../../groupdocs.watermark.options.presentation)
* assembly [GroupDocs.Watermark](../../../)

---

## PresentationPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Initialiseert een nieuw exemplaar van [`PresentationPreviewOptions`](../../presentationpreviewoptions) klasse waardoor de uitvoerstroom wordt teruggegeven aan de client voor verder gebruik.

```csharp
public PresentationPreviewOptions(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createPageStream | CreatePageStream | Maakt een stroom voor een specifieke paginavoorvertoning. |
| releasePageStream | ReleasePageStream | Geeft aan dat de generatie van de paginavoorvertoning is voltooid en haalt de uitvoerstroom op. |

### Zie ook

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [PresentationPreviewOptions](../../presentationpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Presentation](../../../groupdocs.watermark.options.presentation)
* assembly [GroupDocs.Watermark](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
