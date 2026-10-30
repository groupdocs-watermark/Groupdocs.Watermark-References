---
title: "FileType"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Stelt bestandstype voor."
type: docs
weight: 40
url: /nl/net/groupdocs.watermark.common/filetype/
---
## FileType class

Stelt bestandstype voor.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Extension](../../groupdocs.watermark.common/filetype/extension) { get; } | Haalt het bestandsextensie (inclusief de punt ".") op, bijv. ".doc". |
| [FileFormatName](../../groupdocs.watermark.common/filetype/fileformatname) { get; } | Haalt de bestandstypename op, bijv. "Microsoft Word Document". |
| [FormatFamily](../../groupdocs.watermark.common/filetype/formatfamily) { get; } | Haalt de formaatfamilie op. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| static [FromExtension](../../groupdocs.watermark.common/filetype/fromextension)(string) | Mapt de bestandsextensie naar het bestandstype. |
| [Equals](../../groupdocs.watermark.common/filetype/equals#equals)(FileType) | Bepaalt of de huidige [`FileType`](../filetype) hetzelfde is als het opgegeven [`FileType`](../filetype) object. |
| override [Equals](../../groupdocs.watermark.common/filetype/equals#equals_1)(object) | Bepaalt of het huidige [`FileType`](../filetype) hetzelfde is als het opgegeven object. |
| override [GetHashCode](../../groupdocs.watermark.common/filetype/gethashcode)() | Retourneert een hashcode voor het huidige [`FileType`](../filetype) object. |
| override [ToString](../../groupdocs.watermark.common/filetype/tostring)() | Retourneert een string die het huidige object vertegenwoordigt. |
| static [GetSupportedFileTypes](../../groupdocs.watermark.common/filetype/getsupportedfiletypes)() | Haalt de ondersteunde bestandstypen op. |
| [operator ==](../../groupdocs.watermark.common/filetype/op_equality) | Bepaalt of twee [`FileType`](../filetype) objecten hetzelfde zijn. |
| [operator !=](../../groupdocs.watermark.common/filetype/op_inequality) | Bepaalt of twee [`FileType`](../filetype) objecten niet hetzelfde zijn. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| static readonly [BMP](../../groupdocs.watermark.common/filetype/bmp) | Bestanden met de extensie .BMP vertegenwoordigen Bitmap Image‑bestanden die worden gebruikt om bitmap‑digitale afbeeldingen op te slaan. Deze afbeeldingen zijn onafhankelijk van de grafische adapter en worden ook wel device independent bitmap (DIB) bestandsformaat genoemd. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/bmp/). |
| static readonly [DOC](../../groupdocs.watermark.common/filetype/doc) | Bestanden met de extensie .doc vertegenwoordigen documenten die door Microsoft Word of andere tekstverwerkingsprogramma's zijn gegenereerd in binair bestandsformaat. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/word-processing/doc/). |
| static readonly [DOCM](../../groupdocs.watermark.common/filetype/docm) | DOCM‑bestanden zijn door Microsoft Word 2007 of hoger gegenereerde documenten met de mogelijkheid macro's uit te voeren. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/word-processing/docm/). |
| static readonly [DOCX](../../groupdocs.watermark.common/filetype/docx) | DOCX is een bekend formaat voor Microsoft Word‑documenten. Sinds 2007, met de uitgave van Microsoft Office 2007, is de structuur van dit nieuwe documentformaat gewijzigd van eenvoudig binair naar een combinatie van XML‑ en binaire bestanden. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/word-processing/docx/). |
| static readonly [DOT](../../groupdocs.watermark.common/filetype/dot) | Bestanden met de extensie .DOT zijn sjabloonbestanden die door Microsoft Word zijn aangemaakt om vooraf geformatteerde instellingen te hebben voor het genereren van verdere DOC‑ of DOCX‑bestanden. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/word-processing/dot/). |
| static readonly [DOTM](../../groupdocs.watermark.common/filetype/dotm) | Een bestand met de extensie DOTM vertegenwoordigt een sjabloonbestand dat is aangemaakt met Microsoft Word 2007 of hoger. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/word-processing/dotm/). |
| static readonly [DOTX](../../groupdocs.watermark.common/filetype/dotx) | Bestanden met de extensie .DOTX zijn sjabloonbestanden die door Microsoft Word zijn aangemaakt om vooraf geformatteerde instellingen te hebben voor het genereren van verdere DOCX‑bestanden. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/word-processing/dotx/). |
| static readonly [EML](../../groupdocs.watermark.common/filetype/eml) | Het EML‑bestandsformaat vertegenwoordigt e‑mailberichten die zijn opgeslagen met Outlook en andere relevante toepassingen. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/email/eml/). |
| static readonly [EMLX](../../groupdocs.watermark.common/filetype/emlx) | Het EMLX‑bestandsformaat is geïmplementeerd en ontwikkeld door Apple. De Apple Mail‑applicatie gebruikt het EMLX‑bestandsformaat voor het exporteren van e‑mails. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/email/emlx/). |
| static readonly [FlatOpc](../../groupdocs.watermark.common/filetype/flatopc) | Office Open XML WordprocessingML opgeslagen in een plat XML‑bestand in plaats van een ZIP‑pakket (.xml). Meer informatie over dit bestandsformaat [hier](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [FlatOpcMacroEnabled](../../groupdocs.watermark.common/filetype/flatopcmacroenabled) | Office Open XML WordprocessingML macro‑ingeschakeld document opgeslagen in een plat XML‑bestand in plaats van een ZIP‑pakket (.xml). Meer informatie over dit bestandsformaat [hier](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [FlatOpcTemplate](../../groupdocs.watermark.common/filetype/flatopctemplate) | Office Open XML WordprocessingML‑sjabloon (macro‑vrij) opgeslagen in een plat XML‑bestand in plaats van een ZIP‑pakket (.xml). Meer informatie over dit bestandsformaat [hier](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [FlatOpcTemplateMacroEnabled](../../groupdocs.watermark.common/filetype/flatopctemplatemacroenabled) | Office Open XML WordprocessingML macro‑ingeschakelde sjabloon opgeslagen in een plat XML‑bestand in plaats van een ZIP‑pakket (.xml). Meer informatie over dit bestandsformaat [hier](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [GIF](../../groupdocs.watermark.common/filetype/gif) | Een GIF of Graphical Interchange Format is een type sterk gecomprimeerde afbeelding. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/gif/). |
| static readonly [JPEG](../../groupdocs.watermark.common/filetype/jpeg) | Een JPEG is een type afbeeldingsformaat dat wordt opgeslagen met behulp van verliesgevende compressie. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/jpeg/). |
| static readonly [JPF](../../groupdocs.watermark.common/filetype/jpf) | JPEG 2000 (JPF) is een beeldcodering systeem en een geavanceerde beeldcompressiestandaard. Ontworpen met behulp van wavelet‑technologie kan JPEG 2000 verliesloze inhoud in elke kwaliteit tegelijk coderen. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/jp2/). |
| static readonly [JPG](../../groupdocs.watermark.common/filetype/jpg) | Een JPEG is een type afbeeldingsformaat dat wordt opgeslagen met behulp van verliesgevende compressie. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/jpeg/). |
| static readonly [JPM](../../groupdocs.watermark.common/filetype/jpm) | JPEG 2000 (JPM) is een beeldcodering systeem en een geavanceerde beeldcompressiestandaard. Ontworpen, met behulp van wavelettechnologie kan JPEG 2000 verliesvrije inhoud in elke kwaliteit tegelijk coderen. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/jp2/). |
| static readonly [JPX](../../groupdocs.watermark.common/filetype/jpx) | JPEG 2000 (JPX) is een beeldcodering systeem en een geavanceerde beeldcompressiestandaard. Ontworpen, met behulp van wavelettechnologie kan JPEG 2000 verliesvrije inhoud in elke kwaliteit tegelijk coderen. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/jp2/). |
| static readonly [MSG](../../groupdocs.watermark.common/filetype/msg) | MSG is een bestandsformaat dat wordt gebruikt door Microsoft Outlook en Exchange om e‑mailberichten, contactpersonen, afspraken of andere taken op te slaan. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/email/msg/). |
| static readonly [ODT](../../groupdocs.watermark.common/filetype/odt) | ODT‑bestanden zijn een type documenten die worden aangemaakt met tekstverwerkingsprogramma's die gebaseerd zijn op het OpenDocument‑tekstbestandsformaat. Ze worden gemaakt met tekstverwerkers zoals de gratis OpenOffice Writer en kunnen inhoud bevatten zoals tekst, afbeeldingen, objecten en stijlen. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/word-processing/odt/). |
| static readonly [OFT](../../groupdocs.watermark.common/filetype/oft) | Bestanden met de .OFT‑extensie zijn berichtsjabloonbestanden die worden aangemaakt met Microsoft Outlook. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/email/oft/). |
| static readonly [OOXML](../../groupdocs.watermark.common/filetype/ooxml) | Office Open XML‑bestand (.ooxml). |
| static readonly [PDF](../../groupdocs.watermark.common/filetype/pdf) | Portable Document Format (PDF) is een type document dat in de jaren 1990 door Adobe werd gecreëerd. Het doel van dit bestandsformaat was een standaard te introduceren voor de weergave van documenten en ander referentiemateriaal in een formaat dat onafhankelijk is van toepassingssoftware, hardware en besturingssysteem. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/view/pdf/). |
| static readonly [PNG](../../groupdocs.watermark.common/filetype/png) | PNG, Portable Network Graphics, verwijst naar een type rasterafbeeldingsbestand dat verliesloze compressie gebruikt. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/png/). |
| static readonly [POTM](../../groupdocs.watermark.common/filetype/potm) | Bestanden met de POTM‑extensie zijn Microsoft PowerPoint‑sjabloonbestanden met ondersteuning voor macro's. POTM‑bestanden worden gemaakt met PowerPoint 2007 of hoger en bevatten standaardinstellingen die kunnen worden gebruikt om verdere presentaties te maken. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/potm/). |
| static readonly [POTX](../../groupdocs.watermark.common/filetype/potx) | Bestanden met de .POTX‑extensie zijn Microsoft PowerPoint‑sjabloonpresentaties die zijn gemaakt met Microsoft PowerPoint 2007 en hoger. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/potx/). |
| static readonly [PPS](../../groupdocs.watermark.common/filetype/pps) | PPS, PowerPoint Slide Show, bestanden worden aangemaakt met Microsoft PowerPoint voor presentatiedoeleinden. Het lezen en maken van PPS‑bestanden wordt ondersteund door Microsoft PowerPoint 97-2003. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/pps/). |
| static readonly [PPSM](../../groupdocs.watermark.common/filetype/ppsm) | Bestanden met de PPSM‑extensie zijn macro‑ondersteunde Slide Show‑bestandsformaten die zijn gemaakt met Microsoft PowerPoint 2007 of hoger. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/ppsm/). |
| static readonly [PPSX](../../groupdocs.watermark.common/filetype/ppsx) | PPSX, Power Point Slide Show, bestanden worden aangemaakt met Microsoft PowerPoint 2007 en hoger voor presentatiedoeleinden. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/ppsx/). |
| static readonly [PPT](../../groupdocs.watermark.common/filetype/ppt) | Een bestand met de PPT‑extensie vertegenwoordigt een PowerPoint‑bestand dat bestaat uit een verzameling dia's voor weergave als diavoorstelling. Het specificeert het binaire bestandsformaat dat wordt gebruikt door Microsoft PowerPoint 97-2003. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/ppt/). |
| static readonly [PPTM](../../groupdocs.watermark.common/filetype/pptm) | Bestanden met de PPTM‑extensie zijn macro‑ondersteunde presentaties die zijn gemaakt met Microsoft PowerPoint 2007 of hogere versies. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/pptm/). |
| static readonly [PPTX](../../groupdocs.watermark.common/filetype/pptx) | Bestanden met de PPTX‑extensie zijn presentaties die zijn gemaakt met de populaire Microsoft PowerPoint‑applicatie. In tegenstelling tot de vorige versie van het presentatiebestandsformaat PPT, dat binair was, is het PPTX‑formaat gebaseerd op het Microsoft PowerPoint Open XML‑presentatiebestandformaat. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/pptx/). |
| static readonly [RTF](../../groupdocs.watermark.common/filetype/rtf) | Introductie en documentatie door Microsoft, het Rich Text Format (RTF) vertegenwoordigt een methode om opgemaakte tekst en grafische elementen te coderen voor gebruik binnen applicaties. Het formaat vergemakkelijkt cross‑platform documentuitwisseling met andere Microsoft‑producten, en dient daarmee interoperabiliteit. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/word-processing/rtf/). |
| static readonly [TIF](../../groupdocs.watermark.common/filetype/tif) | TIFF of TIF, Tagged Image File Format, vertegenwoordigt rasterafbeeldingen die bedoeld zijn voor gebruik op diverse apparaten die aan deze bestandsformaatstandaard voldoen. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/tiff/). |
| static readonly [TIFF](../../groupdocs.watermark.common/filetype/tiff) | TIFF of TIF, Tagged Image File Format, vertegenwoordigt rasterafbeeldingen die bedoeld zijn voor gebruik op diverse apparaten die aan deze bestandsformaatstandaard voldoen. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/tiff/). |
| static readonly [Unknown](../../groupdocs.watermark.common/filetype/unknown) | Stelt een onbekend bestandstype voor. |
| static readonly [VDW](../../groupdocs.watermark.common/filetype/vdw) | VDW is het Visio Graphics Service‑bestandsformaat dat de streams en opslaglocaties specificeert die nodig zijn voor het renderen van een webtekening. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/web/vdw/). |
| static readonly [VDX](../../groupdocs.watermark.common/filetype/vdx) | Elke tekening of grafiek die in Microsoft Visio is gemaakt, maar in XML‑formaat is opgeslagen, heeft de .VDX‑extensie. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/vdx/). |
| static readonly [VSD](../../groupdocs.watermark.common/filetype/vsd) | VSD‑bestanden zijn tekeningen die met de Microsoft Visio‑applicatie zijn gemaakt om een verscheidenheid aan grafische objecten en de onderlinge verbindingen weer te geven. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/vsd/). |
| static readonly [VSDM](../../groupdocs.watermark.common/filetype/vsdm) | Bestanden met de VSDM‑extensie zijn tekenbestanden die met de Microsoft Visio‑applicatie zijn gemaakt en macro's ondersteunen. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/vsdm/). |
| static readonly [VSDX](../../groupdocs.watermark.common/filetype/vsdx) | Bestanden met de .VSDX‑extensie vertegenwoordigen het Microsoft Visio‑bestandsformaat dat vanaf Microsoft Office 2013 is geïntroduceerd. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/vsdx/). |
| static readonly [VSS](../../groupdocs.watermark.common/filetype/vss) | VSS zijn sjabloonbestanden die met Microsoft Visio 2007 en eerder zijn gemaakt. Sjabloonbestanden bieden tekenobjecten die in een .VSD‑Visio‑tekening kunnen worden opgenomen. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/vss/). |
| static readonly [VSSM](../../groupdocs.watermark.common/filetype/vssm) | Bestanden met de .VSSM‑extensie zijn Microsoft Visio‑sjabloonbestanden die ondersteuning voor macro's bieden. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/vssm/). |
| static readonly [VSSX](../../groupdocs.watermark.common/filetype/vssx) | Bestanden met de .VSSX‑extensie zijn tekensjablonen die met Microsoft Visio 2013 en hoger zijn gemaakt. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/vssx/). |
| static readonly [VST](../../groupdocs.watermark.common/filetype/vst) | Bestanden met de VST‑extensie zijn vectorafbeeldingsbestanden die met Microsoft Visio zijn gemaakt en dienen als sjabloon voor het aanmaken van verdere bestanden. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/vst/). |
| static readonly [VSTM](../../groupdocs.watermark.common/filetype/vstm) | Bestanden met de VSTM‑extensie zijn sjabloonbestanden die met Microsoft Visio zijn gemaakt en macro's ondersteunen. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/vstm/). |
| static readonly [VSTX](../../groupdocs.watermark.common/filetype/vstx) | Bestanden met de VSTX‑extensies zijn tekensjabloonbestanden die met Microsoft Visio 2013 en hoger zijn gemaakt. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/vstx/). |
| static readonly [VSX](../../groupdocs.watermark.common/filetype/vsx) | Bestanden met de .VSX‑extensie verwijzen naar sjablonen die bestaan uit tekeningen en vormen die worden gebruikt voor het maken van diagrammen in Microsoft Visio. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/vsx/). |
| static readonly [VTX](../../groupdocs.watermark.common/filetype/vtx) | Een bestand met de VTX‑extensie is een Microsoft Visio‑teken‑sjabloon dat op schijf wordt opgeslagen in XML‑bestandsformaat. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/vtx/). |
| static readonly [WEBP](../../groupdocs.watermark.common/filetype/webp) | WebP, geïntroduceerd door Google, is een modern raster‑webafbeeldingsbestandsformaat dat gebaseerd is op verliesloze en verliesgevende compressie. Het levert dezelfde beeldkwaliteit terwijl het de bestandsgrootte aanzienlijk verkleint. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/webp/). |
| static readonly [XLS](../../groupdocs.watermark.common/filetype/xls) | Bestanden met de XLS‑extensie vertegenwoordigen het Excel Binary File Format. Dergelijke bestanden kunnen worden aangemaakt door Microsoft Excel evenals andere vergelijkbare spreadsheet‑programma's zoals OpenOffice Calc of Apple Numbers. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/specification/spreadsheet/xls/). |
| static readonly [XLSB](../../groupdocs.watermark.common/filetype/xlsb) | XLSB-bestandsformaat specificeert het **Excel Binary File Format**, dat een verzameling records en structuren is die de inhoud van een Excel-werkmap specificeren. Leer meer over dit bestandsformaat [hier](https://wiki.fileformat.com/specification/spreadsheet/xlsb/). |
| static readonly [XLSM](../../groupdocs.watermark.common/filetype/xlsm) | Bestanden met de XLSM-extensie zijn een type spreadsheet‑bestanden die macro's ondersteunen. Leer meer over dit bestandsformaat [hier](https://wiki.fileformat.com/specification/spreadsheet/xlsm/). |
| static readonly [XLSX](../../groupdocs.watermark.common/filetype/xlsx) | XLSX is een bekend formaat voor Microsoft Excel‑documenten dat werd geïntroduceerd door Microsoft met de release van Microsoft Office 2007. Leer meer over dit bestandsformaat [hier](https://wiki.fileformat.com/specification/spreadsheet/xlsx/). |
| static readonly [XLT](../../groupdocs.watermark.common/filetype/xlt) | Bestanden met de .XLT-extensie zijn sjabloonbestanden die zijn gemaakt met Microsoft Excel, een spreadsheet‑applicatie die deel uitmaakt van de Microsoft Office‑suite. Leer meer over dit bestandsformaat [hier](https://wiki.fileformat.com/specification/spreadsheet/xlt/). |
| static readonly [XLTM](../../groupdocs.watermark.common/filetype/xltm) | De XLTM-bestandsextensie vertegenwoordigt bestanden die door Microsoft Excel worden gegenereerd als macro‑ingeschakelde sjabloonbestanden. Leer meer over dit bestandsformaat [hier](https://wiki.fileformat.com/specification/spreadsheet/xltm/). |
| static readonly [XLTX](../../groupdocs.watermark.common/filetype/xltx) | Bestanden met de XLTX-extensie vertegenwoordigen Microsoft Excel‑sjabloonbestanden die gebaseerd zijn op de Office OpenXML‑bestandsformaatspecificaties. Leer meer over dit bestandsformaat [hier](https://wiki.fileformat.com/specification/spreadsheet/xltx/). |

### Opmerkingen

Deze klasse biedt methoden om een lijst van alle bestandstypen te verkrijgen die worden ondersteund door **GroupDocs.Watermark**.**Meer info**

* [Supported Document Formats](https://docs.groupdocs.com/display/watermarknet/Supported+Document+Formats)
* [Get supported file formats](https://docs.groupdocs.com/display/watermarknet/Get+supported+file+formats)
* [Get document info](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### Zie ook

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
