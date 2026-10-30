---
title: "AttachmentWatermarkableImage"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Stelt een bijgevoegde afbeelding binnen een inhoud van elk ondersteund type voor."
type: docs
weight: 20
url: /nl/net/groupdocs.watermark.common/attachmentwatermarkableimage/
---
## AttachmentWatermarkableImage class

Stelt een bijgevoegde afbeelding binnen een inhoud van elk ondersteund type voor.

```csharp
public class AttachmentWatermarkableImage : WatermarkableImage
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Height](../../groupdocs.watermark.contents.image/watermarkableimage/height) { get; } | Haalt de hoogte op van deze [`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) in pixels. |
| [Width](../../groupdocs.watermark.contents.image/watermarkableimage/width) { get; } | Haalt de breedte op van deze [`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) in pixels. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.image/watermarkableimage/add)(Watermark) | Voegt een watermerk toe aan deze [`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage). Deze methode gaat ervan uit dat de offset en grootte van het watermerk in pixels worden gemeten (indien ze zijn toegewezen). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Vindt alle afbeeldingen in de inhoud. Het zoeken wordt uitgevoerd in de objecten die zijn gespecificeerd in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Vindt afbeeldingen volgens de opgegeven zoekcriteria. Het zoeken wordt uitgevoerd in de objecten die zijn gespecificeerd in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [GetBytes](../../groupdocs.watermark.contents.image/watermarkableimage/getbytes)() | Haalt de afbeelding op als byte-array. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Vindt alle mogelijke watermerken in de inhoud. Het zoeken wordt uitgevoerd in de objecten die zijn gespecificeerd in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Zoekt mogelijke watermerken volgens de opgegeven zoekcriteria. De zoekopdracht wordt uitgevoerd in de objecten die zijn gespecificeerd in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Zie ook

* class [WatermarkableImage](../../groupdocs.watermark.contents.image/watermarkableimage)
* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
