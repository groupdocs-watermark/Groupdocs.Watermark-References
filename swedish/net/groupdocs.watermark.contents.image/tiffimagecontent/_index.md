---
title: "TiffImageContent"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar en TIFF-bild där en vattenstämpel kan placeras."
type: docs
weight: 460
url: /sv/net/groupdocs.watermark.contents.image/tiffimagecontent/
---
## TiffImageContent class

Representerar en TIFF-bild där en vattenstämpel kan placeras.

```csharp
public class TiffImageContent : MultiframeImageContent
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Frames](../../groupdocs.watermark.contents.image/multiframeimagecontent/frames) { get; } | Hämtar samlingen av alla bildramar. |
| virtual [Height](../../groupdocs.watermark.contents.image/imagecontent/height) { get; } | Hämtar höjden för detta [`ImageContent`](../imagecontent) i pixlar. |
| virtual [Width](../../groupdocs.watermark.contents.image/imagecontent/width) { get; } | Hämtar bredden för detta [`ImageContent`](../imagecontent) i pixlar. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Avslutar den aktuella instansen. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Hittar alla bilder i innehållet. Sökningen utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Hittar bilder enligt de angivna sökkriterierna. Sökningen utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Hittar alla möjliga vattenstämplar i innehållet. Sökningen utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Hittar möjliga vattenmärken enligt angivna sökkriterier. Söket utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Se även

* class [MultiframeImageContent](../multiframeimagecontent)
* namespace [GroupDocs.Watermark.Contents.Image](../../groupdocs.watermark.contents.image)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
