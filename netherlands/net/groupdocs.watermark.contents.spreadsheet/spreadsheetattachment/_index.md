---
title: "SpreadsheetAttachment"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Stelt een bestand voor dat is bijgevoegd aan een Excel-document."
type: docs
weight: 1100
url: /nl/net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/
---
## SpreadsheetAttachment class

Stelt een bestand voor dat is bijgevoegd aan een Excel-document.

```csharp
public class SpreadsheetAttachment : Attachment, ITwoDObject
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/alternativetext) { get; set; } | Haalt de beschrijvende (alternatieve) tekst op die aan het bijgevoegde bestand is gekoppeld of stelt deze in. |
| override [Content](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/content) { get; set; } | Haalt de inhoud van het bijgevoegde bestand op of stelt deze in. |
| [Height](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/height) { get; set; } | Haalt de hoogte van het bijlageframe op in punten of stelt deze in. |
| [IsLink](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/islink) { get; } | Haalt een waarde op die aangeeft of de inhoud alleen een koppeling naar het bestand bevat. |
| [PreviewImageContent](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/previewimagecontent) { get; set; } | Haalt de voorbeeldafbeelding van het bijgevoegde bestand op als een byte-array of stelt deze in. |
| [SourceFullName](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/sourcefullname) { get; } | Haalt de volledige naam van het bijgevoegde bestand op. |
| [Width](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/width) { get; set; } | Haalt de breedte van het bijlageframe op in punten of stelt deze in. |
| [X](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/x) { get; set; } | Haalt de horizontale offset van het bijlageframe ten opzichte van de linkerrand van het werkblad op in punten of stelt deze in. |
| [Y](../../groupdocs.watermark.contents.spreadsheet/spreadsheetattachment/y) { get; set; } | Haalt de verticale offset van het bijlageframe ten opzichte van de bovengrens van het werkblad op in punten of stelt deze in. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)() | Laadt inhoud van het bijgevoegde bestand. |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions) | Laadt inhoud van het bijgevoegde bestand met de opgegeven laadopties. |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions, WatermarkerSettings) | Laadt inhoud van het bijgevoegde bestand met de opgegeven laadopties en instellingen. |
| [GetDocumentInfo](../../groupdocs.watermark.common/attachment/getdocumentinfo)() | Haalt de informatie over een document op dat is opgeslagen in het bijgevoegde bestand. |

### Zie ook

* class [Attachment](../../groupdocs.watermark.common/attachment)
* interface [ITwoDObject](../../groupdocs.watermark.search/itwodobject)
* namespace [GroupDocs.Watermark.Contents.Spreadsheet](../../groupdocs.watermark.contents.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
