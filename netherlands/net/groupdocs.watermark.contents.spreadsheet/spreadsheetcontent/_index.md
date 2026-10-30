---
title: "SpreadsheetContent"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Stelt een Excel-document voor waarin een watermerk kan worden geplaatst."
type: docs
weight: 1170
url: /nl/net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/
---
## SpreadsheetContent class

Stelt een Excel-document voor waarin een watermerk kan worden geplaatst.

```csharp
public class SpreadsheetContent : Content
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Worksheets](../../groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/worksheets) { get; } | Krijgt de collectie van alle werkbladen van deze [`SpreadsheetContent`](../spreadsheetcontent). |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Decrypt](../../groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/decrypt)() | Ontsleutelt het document. |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Verwijdert de huidige instantie. |
| [Encrypt](../../groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/encrypt)(string) | Versleutelt de inhoud. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Vindt alle afbeeldingen in de inhoud. Het zoeken wordt uitgevoerd in de objecten die zijn gespecificeerd in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Vindt afbeeldingen volgens de opgegeven zoekcriteria. Het zoeken wordt uitgevoerd in de objecten die zijn gespecificeerd in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Vindt alle mogelijke watermerken in de inhoud. Het zoeken wordt uitgevoerd in de objecten die zijn gespecificeerd in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Zoekt mogelijke watermerken volgens de opgegeven zoekcriteria. De zoekopdracht wordt uitgevoerd in de objecten die zijn gespecificeerd in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Opmerkingen

**Learn more:**

* [Add watermarks to spreadsheet documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)
* [Shapes in spreadsheet document](https://docs.groupdocs.com/display/watermarknet/Shapes+in+spreadsheet+document)
* [Working with spreadsheet document attachments](https://docs.groupdocs.com/display/watermarknet/Working+with+spreadsheet+document+attachments)
* [Working with worksheet backgrounds](https://docs.groupdocs.com/display/watermarknet/Working+with+worksheet+backgrounds)
* [Working with worksheet headers and footers](https://docs.groupdocs.com/display/watermarknet/Working+with+worksheet+headers+and+footers)

### Voorbeelden

Laad en sla een Excel-document op van elk ondersteund type.

```csharp
SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\input.xls", loadOptions))
{
    // Gebruik de Add-methode om een watermerk toe te voegen aan een specifiek of alle werkbladen.

    // Sla wijzigingen op.
    watermarker.Save(@"D:\output.xls");
}
```

### Zie ook

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Spreadsheet](../../groupdocs.watermark.contents.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
