---
title: "MultiframeImageContent"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Stelt een multiframe-afbeelding voor waarop een watermerk kan worden geplaatst."
type: docs
weight: 430
url: /nl/net/groupdocs.watermark.contents.image/multiframeimagecontent/
---
## MultiframeImageContent class

Stelt een multiframe-afbeelding voor waarop een watermerk kan worden geplaatst.

```csharp
public abstract class MultiframeImageContent : ImageContent
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Frames](../../groupdocs.watermark.contents.image/multiframeimagecontent/frames) { get; } | Haalt de collectie van alle frames van de afbeelding op. |
| virtual [Height](../../groupdocs.watermark.contents.image/imagecontent/height) { get; } | Haalt de hoogte van deze [`ImageContent`](../imagecontent) op in pixels. |
| virtual [Width](../../groupdocs.watermark.contents.image/imagecontent/width) { get; } | Haalt de breedte van deze [`ImageContent`](../imagecontent) op in pixels. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Verwijdert de huidige instantie. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Vindt alle afbeeldingen in de inhoud. Het zoeken wordt uitgevoerd in de objecten die zijn gespecificeerd in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Vindt afbeeldingen volgens de opgegeven zoekcriteria. Het zoeken wordt uitgevoerd in de objecten die zijn gespecificeerd in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Vindt alle mogelijke watermerken in de inhoud. Het zoeken wordt uitgevoerd in de objecten die zijn gespecificeerd in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Zoekt mogelijke watermerken volgens de opgegeven zoekcriteria. De zoekopdracht wordt uitgevoerd in de objecten die zijn gespecificeerd in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Zie ook

* class [ImageContent](../imagecontent)
* namespace [GroupDocs.Watermark.Contents.Image](../../groupdocs.watermark.contents.image)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
