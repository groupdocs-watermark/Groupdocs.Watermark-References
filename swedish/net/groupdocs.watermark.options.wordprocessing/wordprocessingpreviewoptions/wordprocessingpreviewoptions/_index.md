---
title: "WordProcessingPreviewOptions"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Initierar en ny instans av klassen WordProcessingPreviewOptionsgroupdocs.watermark.options.wordprocessing/wordprocessingpreviewoptions som stänger utdataströmmen."
type: docs
weight: 10
url: /sv/net/groupdocs.watermark.options.wordprocessing/wordprocessingpreviewoptions/wordprocessingpreviewoptions/
---
## WordProcessingPreviewOptions(CreatePageStream) {#constructor}

Initierar en ny instans av klassen [`WordProcessingPreviewOptions`](../../wordprocessingpreviewoptions) som stänger utdataströmmen.

```csharp
public WordProcessingPreviewOptions(CreatePageStream createPageStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | CreatePageStream | Skapar ett flöde för en specifik sidoförhandsgranskning. |

### Se även

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [WordProcessingPreviewOptions](../../wordprocessingpreviewoptions)
* namespace [GroupDocs.Watermark.Options.WordProcessing](../../../groupdocs.watermark.options.wordprocessing)
* assembly [GroupDocs.Watermark](../../../)

---

## WordProcessingPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Initierar en ny instans av [`WordProcessingPreviewOptions`](../../wordprocessingpreviewoptions) som returnerar utdataströmmen till klienten för vidare användning.

```csharp
public WordProcessingPreviewOptions(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | CreatePageStream | Skapar ett flöde för en specifik sidoförhandsgranskning. |
| releasePageStream | ReleasePageStream | Meddelar att sidoförhandsgranskningens generering är klar och hämtar utdataflödet. |

### Se även

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [WordProcessingPreviewOptions](../../wordprocessingpreviewoptions)
* namespace [GroupDocs.Watermark.Options.WordProcessing](../../../groupdocs.watermark.options.wordprocessing)
* assembly [GroupDocs.Watermark](../../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
