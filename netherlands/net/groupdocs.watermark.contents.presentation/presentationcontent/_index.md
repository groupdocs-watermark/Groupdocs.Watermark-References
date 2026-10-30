---
title: "PresentationContent"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Stelt een PowerPoint-document voor waarin een watermerk kan worden geplaatst."
type: docs
weight: 900
url: /nl/net/groupdocs.watermark.contents.presentation/presentationcontent/
---
## PresentationContent class

Stelt een PowerPoint-document voor waarin een watermerk kan worden geplaatst.

```csharp
public class PresentationContent : Content
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [LayoutSlides](../../groupdocs.watermark.contents.presentation/presentationcontent/layoutslides) { get; } | Haalt de collectie op van alle lay-outdia's van dit [`PresentationContent`](../presentationcontent). |
| [MasterHandoutSlide](../../groupdocs.watermark.contents.presentation/presentationcontent/masterhandoutslide) { get; } | Haalt de masterhand-outdia op van dit [`PresentationContent`](../presentationcontent). |
| [MasterNotesSlide](../../groupdocs.watermark.contents.presentation/presentationcontent/masternotesslide) { get; } | Haalt de masterdia op voor alle notitieslides van deze [`PresentationContent`](../presentationcontent). |
| [MasterSlides](../../groupdocs.watermark.contents.presentation/presentationcontent/masterslides) { get; } | Haalt de collectie van alle masterdia's van deze [`PresentationContent`](../presentationcontent) op. |
| [NotesSlideHeight](../../groupdocs.watermark.contents.presentation/presentationcontent/notesslideheight) { get; } | Haalt de hoogte van een notitieslide op in punten. |
| [NotesSlideWidth](../../groupdocs.watermark.contents.presentation/presentationcontent/notesslidewidth) { get; } | Haalt de breedte van een notitieslide op in punten. |
| [SlideHeight](../../groupdocs.watermark.contents.presentation/presentationcontent/slideheight) { get; } | Haalt de hoogte van een dia op in punten. |
| [Slides](../../groupdocs.watermark.contents.presentation/presentationcontent/slides) { get; } | Haalt de collectie van alle dia's van deze [`PresentationContent`](../presentationcontent) op. |
| [SlideWidth](../../groupdocs.watermark.contents.presentation/presentationcontent/slidewidth) { get; } | Haalt de breedte van een dia op in punten. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Decrypt](../../groupdocs.watermark.contents.presentation/presentationcontent/decrypt)() | Ontsleutelt het document. |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Verwijdert de huidige instantie. |
| [Encrypt](../../groupdocs.watermark.contents.presentation/presentationcontent/encrypt)(string) | Versleutelt het document. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Vindt alle afbeeldingen in de inhoud. Het zoeken wordt uitgevoerd in de objecten die zijn gespecificeerd in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Vindt afbeeldingen volgens de opgegeven zoekcriteria. Het zoeken wordt uitgevoerd in de objecten die zijn gespecificeerd in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Vindt alle mogelijke watermerken in de inhoud. Het zoeken wordt uitgevoerd in de objecten die zijn gespecificeerd in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Zoekt mogelijke watermerken volgens de opgegeven zoekcriteria. De zoekopdracht wordt uitgevoerd in de objecten die zijn gespecificeerd in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Opmerkingen

**Learn more:**

* [Add watermarks to presentation documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents)
* [Working with slide backgrounds](https://docs.groupdocs.com/display/watermarknet/Working+with+slide+backgrounds)

### Voorbeelden

Laad en sla PowerPoint-document op van elk ondersteund type.

```csharp
PresentationLoadOptions loadOptions = new PresentationLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\input.ppt", loadOptions))
{
    // Gebruik de Add-methode om een watermerk toe te voegen aan een specifieke dia of aan alle dia's.

    // Sla wijzigingen op.
    watermarker.Save(@"D:\output.ppt");
}
```

### Zie ook

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Presentation](../../groupdocs.watermark.contents.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
