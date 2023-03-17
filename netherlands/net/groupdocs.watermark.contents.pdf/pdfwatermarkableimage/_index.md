---
title: PdfWatermarkableImage
second_title: GroupDocs.Watermark voor .NET API-referentie
description: Vertegenwoordigt een afbeelding in een pdfdocument.
type: docs
weight: 730
url: /nl/net/groupdocs.watermark.contents.pdf/pdfwatermarkableimage/
---
## PdfWatermarkableImage class

Vertegenwoordigt een afbeelding in een pdf-document.

```csharp
public class PdfWatermarkableImage : WatermarkableImage
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [PdfWatermarkableImage](pdfwatermarkableimage)(byte[]) | Initialiseert een nieuw exemplaar van het[`PdfWatermarkableImage`](../pdfwatermarkableimage) klasse met behulp van opgegeven afbeeldingsgegevens. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Height](../../groupdocs.watermark.contents.image/watermarkableimage/height) { get; } | Krijgt de hoogte hiervan[`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) in pixels. |
| [Width](../../groupdocs.watermark.contents.image/watermarkableimage/width) { get; } | Krijgt de breedte hiervan[`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) in pixels. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.image/watermarkableimage/add)(Watermark) | Voegt hier een watermerk aan toe[`WatermarkableImage`](../../groupdocs.watermark.contents.image/watermarkableimage) . Deze methode gaat ervan uit dat de offset en grootte van het watermerk worden gemeten in pixels (indien toegewezen). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Vindt alle afbeeldingen in de inhoud. De zoekopdracht wordt uitgevoerd in de objecten die zijn opgegeven in[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Zoekt afbeeldingen volgens de opgegeven zoekcriteria. De zoekopdracht wordt uitgevoerd in de objecten die zijn opgegeven in[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [GetBytes](../../groupdocs.watermark.contents.image/watermarkableimage/getbytes)() | Haalt de afbeelding op als byte-array. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Vindt alle mogelijke watermerken in de inhoud. De zoekopdracht wordt uitgevoerd in de objecten die zijn opgegeven in[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Vindt mogelijke watermerken volgens opgegeven zoekcriteria. De zoekopdracht wordt uitgevoerd in de objecten die zijn opgegeven in[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |

### Zie ook

* class [WatermarkableImage](../../groupdocs.watermark.contents.image/watermarkableimage)
* naamruimte [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* montage [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->