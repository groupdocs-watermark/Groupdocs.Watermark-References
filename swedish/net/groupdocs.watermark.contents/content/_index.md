---
title: "Innehåll"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar ett innehåll där ett vattenmärke kan placeras."
type: docs
weight: 150
url: /sv/net/groupdocs.watermark.contents/content/
---
## Content class

Representerar ett innehåll där ett vattenmärke kan placeras.

```csharp
public abstract class Content : ContentPart, IDisposable
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Avslutar den aktuella instansen. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Hittar alla bilder i innehållet. Sökningen utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Hittar bilder enligt de angivna sökkriterierna. Sökningen utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Hittar alla möjliga vattenstämplar i innehållet. Sökningen utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Hittar möjliga vattenmärken enligt angivna sökkriterier. Söket utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Se även

* class [ContentPart](../contentpart)
* namespace [GroupDocs.Watermark.Contents](../../groupdocs.watermark.contents)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
