---
title: "PdfContent"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Stelt een pdf-document voor waarin een watermerk kan worden geplaatst."
type: docs
weight: 660
url: /nl/net/groupdocs.watermark.contents.pdf/pdfcontent/
---
## PdfContent class

Stelt een pdf-document voor waarin een watermerk kan worden geplaatst.

```csharp
public class PdfContent : Content
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Attachments](../../groupdocs.watermark.contents.pdf/pdfcontent/attachments) { get; } | Haalt de verzameling van alle bijlagen van dit [`PdfContent`](../pdfcontent) op. |
| [PageMarginType](../../groupdocs.watermark.contents.pdf/pdfcontent/pagemargintype) { get; set; } | Haalt op of stelt pdf-paginamarges in die worden gebruikt tijdens het toevoegen van een watermerk. |
| [Pages](../../groupdocs.watermark.contents.pdf/pdfcontent/pages) { get; } | Haalt de verzameling van alle pagina's van dit [`PdfContent`](../pdfcontent) op. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Decrypt](../../groupdocs.watermark.contents.pdf/pdfcontent/decrypt)() | Ontsleutelt de inhoud. |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Verwijdert de huidige instantie. |
| [Encrypt](../../groupdocs.watermark.contents.pdf/pdfcontent/encrypt#encrypt)(string) | Versleutelt het document met hetzelfde wachtwoord als gebruikerswachtwoord en eigenaarwachtwoord. |
| [Encrypt](../../groupdocs.watermark.contents.pdf/pdfcontent/encrypt#encrypt_1)(string, string, PdfPermissions, PdfCryptoAlgorithm) | Versleutelt de inhoud. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Vindt alle afbeeldingen in de inhoud. Het zoeken wordt uitgevoerd in de objecten die zijn gespecificeerd in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Vindt afbeeldingen volgens de opgegeven zoekcriteria. Het zoeken wordt uitgevoerd in de objecten die zijn gespecificeerd in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Rasterize](../../groupdocs.watermark.contents.pdf/pdfcontent/rasterize)(int, int, PdfImageConversionFormat) | Converteert alle inhoudspagina's naar afbeeldingen. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Vindt alle mogelijke watermerken in de inhoud. Het zoeken wordt uitgevoerd in de objecten die zijn gespecificeerd in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Zoekt mogelijke watermerken volgens de opgegeven zoekcriteria. De zoekopdracht wordt uitgevoerd in de objecten die zijn gespecificeerd in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Opmerkingen

**Learn more:**

* [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)
* [Existing objects in PDF document](https://docs.groupdocs.com/display/watermarknet/Existing+objects+in+PDF+document)
* [Rasterize document or page](https://docs.groupdocs.com/display/watermarknet/Rasterize+document+or+page)
* [Watermarks in PDF document](https://docs.groupdocs.com/display/watermarknet/Watermarks+in+PDF+document)

### Zie ook

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
