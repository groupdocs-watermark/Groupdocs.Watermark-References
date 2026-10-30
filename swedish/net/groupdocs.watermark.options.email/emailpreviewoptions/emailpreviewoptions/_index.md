---
title: "EmailPreviewOptions"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Initierar en ny instans av EmailPreviewOptionsgroupdocs.watermark.options.email/emailpreviewoptions-klassen som gör att utdataflödet stängs."
type: docs
weight: 10
url: /sv/net/groupdocs.watermark.options.email/emailpreviewoptions/emailpreviewoptions/
---
## EmailPreviewOptions(CreatePageStream) {#constructor}

Initierar en ny instans av [`EmailPreviewOptions`](../../emailpreviewoptions)-klassen som gör att utdataflödet stängs.

```csharp
public EmailPreviewOptions(CreatePageStream createPageStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | CreatePageStream | Skapar ett flöde för en specifik sidoförhandsgranskning. |

### Se även

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [EmailPreviewOptions](../../emailpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Email](../../../groupdocs.watermark.options.email)
* assembly [GroupDocs.Watermark](../../../)

---

## EmailPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Initierar en ny instans av [`EmailPreviewOptions`](../../emailpreviewoptions)-klassen som gör att utdataflödet returneras till klienten för vidare användning.

```csharp
public EmailPreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | CreatePageStream | Skapar ett flöde för en specifik sidoförhandsgranskning. |
| releasePageStream | ReleasePageStream | Meddelar att sidoförhandsgranskningens generering är klar och hämtar utdataflödet. |

### Se även

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [EmailPreviewOptions](../../emailpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Email](../../../groupdocs.watermark.options.email)
* assembly [GroupDocs.Watermark](../../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
