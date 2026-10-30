---
title: "ImageContent"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar en bild där en vattenstämpel kan placeras."
type: docs
weight: 400
url: /sv/net/groupdocs.watermark.contents.image/imagecontent/
---
## ImageContent class

Representerar en bild där en vattenstämpel kan placeras.

```csharp
public class ImageContent : Content
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
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

### Anmärkningar

**Learn more:**

* [Add watermarks to images](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images)

### Se även

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Image](../../groupdocs.watermark.contents.image)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
