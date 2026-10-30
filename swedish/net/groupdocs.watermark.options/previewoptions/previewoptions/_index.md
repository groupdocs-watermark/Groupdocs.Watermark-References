---
title: "PreviewOptions"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Initierar en ny instans av klassen PreviewOptionsgroupdocs.watermark.options/previewoptions som gör att utdata‑strömmen stängs."
type: docs
weight: 10
url: /sv/net/groupdocs.watermark.options/previewoptions/previewoptions/
---
## PreviewOptions(CreatePageStream) {#constructor}

Initierar en ny instans av klassen [`PreviewOptions`](../../previewoptions) som gör att utdata‑strömmen stängs.

```csharp
public PreviewOptions(CreatePageStream createPageStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | CreatePageStream | Skapar ett flöde för en specifik sidoförhandsgranskning. |

### Se även

* delegate [CreatePageStream](../../createpagestream)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Watermark.Options](../../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Initierar en ny instans av [`PreviewOptions`](../../previewoptions)‑klassen som gör att utdata‑strömmen returneras till klienten för vidare användning.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | CreatePageStream | Skapar ett flöde för en specifik sidoförhandsgranskning. |
| releasePageStream | ReleasePageStream | Meddelar att sidoförhandsgranskningens generering är klar och hämtar utdataflödet. |

### Se även

* delegate [CreatePageStream](../../createpagestream)
* delegate [ReleasePageStream](../../releasepagestream)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Watermark.Options](../../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
