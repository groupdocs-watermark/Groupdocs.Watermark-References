---
title: "PresentationBaseSlide"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Tillhandahåller den abstrakta basklassen för bilder av alla typer i ett PowerPoint-dokument."
type: docs
weight: 870
url: /sv/net/groupdocs.watermark.contents.presentation/presentationbaseslide/
---
## PresentationBaseSlide class

Tillhandahåller den abstrakta basklassen för bilder av alla typer i ett PowerPoint-dokument.

```csharp
public abstract class PresentationBaseSlide : ContentPart
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Charts](../../groupdocs.watermark.contents.presentation/presentationbaseslide/charts) { get; } | Hämtar samlingen av alla diagram i presentationen. |
| [ImageFillFormat](../../groupdocs.watermark.contents.presentation/presentationbaseslide/imagefillformat) { get; } | Hämtar bildfyllnadsformatinställningarna för presentationen. |
| [Shapes](../../groupdocs.watermark.contents.presentation/presentationbaseslide/shapes) { get; } | Hämtar samlingen av alla former i presentationen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Hittar alla bilder i innehållet. Sökningen utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Hittar bilder enligt de angivna sökkriterierna. Sökningen utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Hittar alla möjliga vattenstämplar i innehållet. Sökningen utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Hittar möjliga vattenmärken enligt angivna sökkriterier. Söket utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Se även

* class [ContentPart](../../groupdocs.watermark.contents/contentpart)
* namespace [GroupDocs.Watermark.Contents.Presentation](../../groupdocs.watermark.contents.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
