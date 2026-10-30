---
title: "PreviewOptions"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Initialiseert een nieuw exemplaar van de PreviewOptionsgroupdocs.watermark.options/previewoptions klasse waardoor de uitvoerstroom wordt gesloten."
type: docs
weight: 10
url: /nl/net/groupdocs.watermark.options/previewoptions/previewoptions/
---
## PreviewOptions(CreatePageStream) {#constructor}

Initialiseert een nieuw exemplaar van de [`PreviewOptions`](../../previewoptions) klasse waardoor de uitvoerstroom wordt gesloten.

```csharp
public PreviewOptions(CreatePageStream createPageStream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createPageStream | CreatePageStream | Maakt een stroom voor een specifieke paginavoorvertoning. |

### Zie ook

* delegate [CreatePageStream](../../createpagestream)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Watermark.Options](../../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Initialiseert een nieuw exemplaar van de [`PreviewOptions`](../../previewoptions) klasse waardoor de uitvoerstroom wordt teruggegeven aan de client voor verder gebruik.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createPageStream | CreatePageStream | Maakt een stroom voor een specifieke paginavoorvertoning. |
| releasePageStream | ReleasePageStream | Geeft aan dat de generatie van de paginavoorvertoning is voltooid en haalt de uitvoerstroom op. |

### Zie ook

* delegate [CreatePageStream](../../createpagestream)
* delegate [ReleasePageStream](../../releasepagestream)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Watermark.Options](../../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
