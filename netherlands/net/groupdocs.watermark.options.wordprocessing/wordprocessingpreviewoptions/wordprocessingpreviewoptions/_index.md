---
title: "WordProcessingPreviewOptions"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Initialiseert een nieuw exemplaar van de WordProcessingPreviewOptionsgroupdocs.watermark.options.wordprocessing/wordprocessingpreviewoptions klasse waardoor de uitvoerstroom wordt gesloten."
type: docs
weight: 10
url: /nl/net/groupdocs.watermark.options.wordprocessing/wordprocessingpreviewoptions/wordprocessingpreviewoptions/
---
## WordProcessingPreviewOptions(CreatePageStream) {#constructor}

Initialiseert een nieuw exemplaar van de [`WordProcessingPreviewOptions`](../../wordprocessingpreviewoptions) klasse waardoor de uitvoerstroom wordt gesloten.

```csharp
public WordProcessingPreviewOptions(CreatePageStream createPageStream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createPageStream | CreatePageStream | Maakt een stroom voor een specifieke paginavoorvertoning. |

### Zie ook

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [WordProcessingPreviewOptions](../../wordprocessingpreviewoptions)
* namespace [GroupDocs.Watermark.Options.WordProcessing](../../../groupdocs.watermark.options.wordprocessing)
* assembly [GroupDocs.Watermark](../../../)

---

## WordProcessingPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Initialiseert een nieuw exemplaar van de [`WordProcessingPreviewOptions`](../../wordprocessingpreviewoptions) klasse waardoor de uitvoerstroom wordt geretourneerd aan de client voor verder gebruik.

```csharp
public WordProcessingPreviewOptions(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createPageStream | CreatePageStream | Maakt een stroom voor een specifieke paginavoorvertoning. |
| releasePageStream | ReleasePageStream | Geeft aan dat de generatie van de paginavoorvertoning is voltooid en haalt de uitvoerstroom op. |

### Zie ook

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [WordProcessingPreviewOptions](../../wordprocessingpreviewoptions)
* namespace [GroupDocs.Watermark.Options.WordProcessing](../../../groupdocs.watermark.options.wordprocessing)
* assembly [GroupDocs.Watermark](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
