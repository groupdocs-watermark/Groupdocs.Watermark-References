---
title: "ImageDctHashSearchCriteria"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Stelt een zoekcriteria voor het vinden van afbeeldingen in een document voor."
type: docs
weight: 2630
url: /nl/net/groupdocs.watermark.search.searchcriteria/imagedcthashsearchcriteria/
---
## ImageDctHashSearchCriteria class

Stelt een zoekcriteria voor het vinden van afbeeldingen in een document voor.

```csharp
public class ImageDctHashSearchCriteria : ImageSearchCriteria
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [ImageDctHashSearchCriteria](imagedcthashsearchcriteria#constructor)(Stream) | Initialiseert een nieuw exemplaar van de [`ImageDctHashSearchCriteria`](../imagedcthashsearchcriteria) klasse met een opgegeven stream. |
| [ImageDctHashSearchCriteria](imagedcthashsearchcriteria#constructor_1)(string) | Initialiseert een nieuw exemplaar van de [`ImageDctHashSearchCriteria`](../imagedcthashsearchcriteria) klasse met een opgegeven bestandspad. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [MaxDifference](../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria/maxdifference) { get; set; } | Haalt op of stelt het maximaal toegestane verschil tussen afbeeldingen in. |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | Haalt de lijst met specifieke paginanummers op of stelt deze in |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | Combineert deze [`SearchCriteria`](../searchcriteria) met andere criteria met behulp van de logische EN-operator. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | Negereert deze [`SearchCriteria`](../searchcriteria). |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | Combineert deze [`SearchCriteria`](../searchcriteria) met andere criteria met behulp van de logische OF-operator. |

### Opmerkingen

Deze zoekcriteria gebruikt DCT-gebaseerde perceptuele afbeeldingshash voor het berekenen van afbeeldingsgelijkenis. **Meer info:**

* [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

### Voorbeelden

Zoek naar afbeeldingen in de bijgevoegde bestanden (pdf).

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    PdfSearchableObjects = PdfSearchableObjects.All
};
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf", loadOptions, settings))
{
    // Geef een voorbeeldafbeelding op om documentafbeeldingen mee te vergelijken
    ImageSearchCriteria criteria = new ImageDctHashSearchCriteria(@"D:\sample.png");
    // Zoek naar vergelijkbare afbeeldingen
    PossibleWatermarkCollection possibleWatermarks = watermarker.Search(criteria);
    // Verwijder of wijzig gevonden afbeeldingswatermerken
    // ...
}
```

### Zie ook

* class [ImageSearchCriteria](../imagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
