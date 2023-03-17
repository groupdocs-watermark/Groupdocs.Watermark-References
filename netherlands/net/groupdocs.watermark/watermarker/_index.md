---
title: Watermarker
second_title: GroupDocs.Watermark voor .NET API-referentie
description: Vertegenwoordigt een klasse voor watermerkbeheer in een document.
type: docs
weight: 3060
url: /nl/net/groupdocs.watermark/watermarker/
---
## Watermarker class

Vertegenwoordigt een klasse voor watermerkbeheer in een document.

```csharp
public class Watermarker : IDisposable
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [Watermarker](watermarker#constructor)(Stream) | Initialiseert een nieuw exemplaar van het[`Watermarker`](../watermarker) klasse met de opgegeven stream. |
| [Watermarker](watermarker#constructor_4)(string) | Initialiseert een nieuw exemplaar van het[`Watermarker`](../watermarker) klasse met het opgegeven documentpad. |
| [Watermarker](watermarker#constructor_1)(Stream, LoadOptions) | Initialiseert een nieuw exemplaar van het[`Watermarker`](../watermarker) klasse met de opgegeven stream en laadopties. |
| [Watermarker](watermarker#constructor_3)(Stream, WatermarkerSettings) | Initialiseert een nieuw exemplaar van het[`Watermarker`](../watermarker) klasse met de opgegeven stream en instellingen. |
| [Watermarker](watermarker#constructor_5)(string, LoadOptions) | Initialiseert een nieuw exemplaar van het[`Watermarker`](../watermarker)klasse met het opgegeven documentpad en laadopties. |
| [Watermarker](watermarker#constructor_7)(string, WatermarkerSettings) | Initialiseert een nieuw exemplaar van het[`Watermarker`](../watermarker) klasse met het opgegeven documentpad en instellingen. |
| [Watermarker](watermarker#constructor_2)(Stream, LoadOptions, WatermarkerSettings) | Initialiseert een nieuw exemplaar van het[`Watermarker`](../watermarker) klasse met de opgegeven stream, laadopties en instellingen. |
| [Watermarker](watermarker#constructor_6)(string, LoadOptions, WatermarkerSettings) | Initialiseert een nieuw exemplaar van het[`Watermarker`](../watermarker) klasse met het opgegeven documentpad, laadopties en instellingen. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [SearchableObjects](../../groupdocs.watermark/watermarker/searchableobjects) { get; set; } | Haalt of stelt de inhoudsobjecten op die moeten worden opgenomen in een watermerkzoekopdracht. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Add](../../groupdocs.watermark/watermarker/add#add)(Watermark) | Voegt een watermerk toe aan het geladen document. |
| [Add](../../groupdocs.watermark/watermarker/add#add_1)(Watermark, WatermarkOptions) | Voegt een watermerk toe aan het geladen document met watermerkopties. |
| [Dispose](../../groupdocs.watermark/watermarker/dispose)() | Verwijdert de huidige instantie. |
| [GeneratePreview](../../groupdocs.watermark/watermarker/generatepreview)(PreviewOptions) | Genereert voorbeeldafbeeldingen voor het document. |
| [GetContent&lt;T&gt;](../../groupdocs.watermark/watermarker/getcontent)() | Retourneert de[`Content`](../../groupdocs.watermark.contents/content) object voor het geladen document. |
| [GetDocumentInfo](../../groupdocs.watermark/watermarker/getdocumentinfo)() | Krijgt de informatie over de indeling van het geladen document. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages)() | Vindt alle afbeeldingen in het document. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages_1)(ImageSearchCriteria) | Vindt afbeeldingen volgens opgegeven zoekcriteria. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove)(PossibleWatermark) | Verwijdert watermerk uit het document. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove_1)(PossibleWatermarkCollection) | Verwijdert alle watermerken in de verzameling uit het document. |
| [Save](../../groupdocs.watermark/watermarker/save#save)() | Slaat de documentgegevens op in de onderliggende stream. |
| [Save](../../groupdocs.watermark/watermarker/save#save_1)(SaveOptions) | Slaat de documentgegevens op in de onderliggende stroom met behulp van opslagopties. |
| [Save](../../groupdocs.watermark/watermarker/save#save_2)(Stream) | Slaat het document op in de opgegeven stream. |
| [Save](../../groupdocs.watermark/watermarker/save#save_4)(string) | Slaat het document op de opgegeven bestandslocatie op. |
| [Save](../../groupdocs.watermark/watermarker/save#save_3)(Stream, SaveOptions) | Slaat het document op in de opgegeven stream met behulp van opslagopties. |
| [Save](../../groupdocs.watermark/watermarker/save#save_5)(string, SaveOptions) | Slaat het document op de gespecificeerde bestandslocatie op met behulp van opslagopties. |
| [Search](../../groupdocs.watermark/watermarker/search#search)() | Zoekt alle mogelijke watermerken in het document. |
| [Search](../../groupdocs.watermark/watermarker/search#search_1)(SearchCriteria) | Zoekt mogelijke watermerken volgens gespecificeerde zoekcriteria. |

### Voorbeelden

Laad en bewaar inhoud van elk ondersteund formaat.

```csharp
// Laad een inhoud uit een bestand.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Gebruik methoden van de klasse Watermarker om watermerken toe te voegen, te zoeken of te verwijderen.

    // Wijzigingen opslaan.
    watermarker.Save("D:\\output.pdf");
}
```

### Zie ook

* naamruimte [GroupDocs.Watermark](../../groupdocs.watermark)
* montage [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
