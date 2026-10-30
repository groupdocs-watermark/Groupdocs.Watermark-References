---
title: "PresentationContent"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar ett PowerPoint-dokument där en vattenstämpel kan placeras."
type: docs
weight: 900
url: /sv/net/groupdocs.watermark.contents.presentation/presentationcontent/
---
## PresentationContent class

Representerar ett PowerPoint-dokument där en vattenstämpel kan placeras.

```csharp
public class PresentationContent : Content
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [LayoutSlides](../../groupdocs.watermark.contents.presentation/presentationcontent/layoutslides) { get; } | Hämtar samlingen av alla layoutbilder för detta [`PresentationContent`](../presentationcontent). |
| [MasterHandoutSlide](../../groupdocs.watermark.contents.presentation/presentationcontent/masterhandoutslide) { get; } | Hämtar masterhandoutsbilden för detta [`PresentationContent`](../presentationcontent). |
| [MasterNotesSlide](../../groupdocs.watermark.contents.presentation/presentationcontent/masternotesslide) { get; } | Hämtar mastersliden för alla notes-bilder för detta [`PresentationContent`](../presentationcontent). |
| [MasterSlides](../../groupdocs.watermark.contents.presentation/presentationcontent/masterslides) { get; } | Hämtar samlingen av alla masterslides för detta [`PresentationContent`](../presentationcontent). |
| [NotesSlideHeight](../../groupdocs.watermark.contents.presentation/presentationcontent/notesslideheight) { get; } | Hämtar höjden på en notes-slide i punkter. |
| [NotesSlideWidth](../../groupdocs.watermark.contents.presentation/presentationcontent/notesslidewidth) { get; } | Hämtar bredden på en notsbild i punkter. |
| [SlideHeight](../../groupdocs.watermark.contents.presentation/presentationcontent/slideheight) { get; } | Hämtar höjden på en bild i punkter. |
| [Slides](../../groupdocs.watermark.contents.presentation/presentationcontent/slides) { get; } | Hämtar samlingen av alla bilder i detta [`PresentationContent`](../presentationcontent). |
| [SlideWidth](../../groupdocs.watermark.contents.presentation/presentationcontent/slidewidth) { get; } | Hämtar bredden på en bild i punkter. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Decrypt](../../groupdocs.watermark.contents.presentation/presentationcontent/decrypt)() | Dekrypterar dokumentet. |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Avslutar den aktuella instansen. |
| [Encrypt](../../groupdocs.watermark.contents.presentation/presentationcontent/encrypt)(string) | Krypterar dokumentet. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Hittar alla bilder i innehållet. Sökningen utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Hittar bilder enligt de angivna sökkriterierna. Sökningen utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Hittar alla möjliga vattenstämplar i innehållet. Sökningen utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Hittar möjliga vattenmärken enligt angivna sökkriterier. Söket utförs i de objekt som anges i [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Anmärkningar

**Learn more:**

* [Add watermarks to presentation documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents)
* [Working with slide backgrounds](https://docs.groupdocs.com/display/watermarknet/Working+with+slide+backgrounds)

### Exempel

Ladda och spara PowerPoint-dokument av någon som helst stödd typ.

```csharp
PresentationLoadOptions loadOptions = new PresentationLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\input.ppt", loadOptions))
{
    // Använd Add-metoden för att lägga till en vattenstämpel på en specifik bild eller alla bilder.

    // Spara ändringar.
    watermarker.Save(@"D:\output.ppt");
}
```

### Se även

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Presentation](../../groupdocs.watermark.contents.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
