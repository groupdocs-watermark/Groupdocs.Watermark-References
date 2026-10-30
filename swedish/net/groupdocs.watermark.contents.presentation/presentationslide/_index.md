---
title: "PresentationSlide"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar en slide i ett PowerPoint-dokument."
type: docs
weight: 1060
url: /sv/net/groupdocs.watermark.contents.presentation/presentationslide/
---
## PresentationSlide class

Representerar en slide i ett PowerPoint-dokument.

```csharp
public class PresentationSlide : PresentationBaseSlide
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Charts](../../groupdocs.watermark.contents.presentation/presentationbaseslide/charts) { get; } | Hämtar samlingen av alla diagram i presentationen. |
| [ImageFillFormat](../../groupdocs.watermark.contents.presentation/presentationbaseslide/imagefillformat) { get; } | Hämtar bildfyllnadsformatinställningarna för presentationen. |
| [LayoutSlide](../../groupdocs.watermark.contents.presentation/presentationslide/layoutslide) { get; } | Hämtar layoutbilden för denna [`PresentationSlide`](../presentationslide). |
| [MasterSlide](../../groupdocs.watermark.contents.presentation/presentationslide/masterslide) { get; } | Hämtar masterbilden för denna [`PresentationSlide`](../presentationslide). |
| [NotesSlide](../../groupdocs.watermark.contents.presentation/presentationslide/notesslide) { get; } | Hämtar anteckningsbilden för denna [`PresentationSlide`](../presentationslide). |
| [Shapes](../../groupdocs.watermark.contents.presentation/presentationbaseslide/shapes) { get; } | Hämtar samlingen av alla former i presentationen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Hittar alla bilder i innehållet. Sökningen utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Hittar bilder enligt de angivna sökkriterierna. Sökningen utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Hittar alla möjliga vattenstämplar i innehållet. Sökningen utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Hittar möjliga vattenmärken enligt angivna sökkriterier. Söket utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Se även

* class [PresentationBaseSlide](../presentationbaseslide)
* namespace [GroupDocs.Watermark.Contents.Presentation](../../groupdocs.watermark.contents.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
