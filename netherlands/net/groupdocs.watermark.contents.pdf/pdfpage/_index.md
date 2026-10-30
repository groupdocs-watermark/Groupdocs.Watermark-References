---
title: "PdfPage"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Stelt een pdf-documentpagina voor."
type: docs
weight: 730
url: /nl/net/groupdocs.watermark.contents.pdf/pdfpage/
---
## PdfPage class

Stelt een pdf-documentpagina voor.

```csharp
public class PdfPage : ContentPart
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Annotations](../../groupdocs.watermark.contents.pdf/pdfpage/annotations) { get; } | Haalt de collectie van alle annotaties van deze [`PdfPage`](../pdfpage) op. |
| [Artifacts](../../groupdocs.watermark.contents.pdf/pdfpage/artifacts) { get; } | Haalt de collectie van alle artefacten van deze [`PdfPage`](../pdfpage) op. |
| [Height](../../groupdocs.watermark.contents.pdf/pdfpage/height) { get; } | Haalt de hoogte van deze [`PdfPage`](../pdfpage) op in punten. |
| [Width](../../groupdocs.watermark.contents.pdf/pdfpage/width) { get; } | Haalt de breedte van deze [`PdfPage`](../pdfpage) op in punten. |
| [XObjects](../../groupdocs.watermark.contents.pdf/pdfpage/xobjects) { get; } | Haalt de collectie van alle XObjecten van deze [`PdfPage`](../pdfpage) op. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Vindt alle afbeeldingen in de inhoud. Het zoeken wordt uitgevoerd in de objecten die zijn gespecificeerd in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Vindt afbeeldingen volgens de opgegeven zoekcriteria. Het zoeken wordt uitgevoerd in de objecten die zijn gespecificeerd in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| virtual [Rasterize](../../groupdocs.watermark.contents.pdf/pdfpage/rasterize)(int, int, PdfImageConversionFormat) | Converteert paginainhoud naar een afbeelding. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Vindt alle mogelijke watermerken in de inhoud. Het zoeken wordt uitgevoerd in de objecten die zijn gespecificeerd in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Zoekt mogelijke watermerken volgens de opgegeven zoekcriteria. De zoekopdracht wordt uitgevoerd in de objecten die zijn gespecificeerd in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Zie ook

* class [ContentPart](../../groupdocs.watermark.contents/contentpart)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
