---
title: FileType
second_title: GroupDocs.Watermark voor .NET API-referentie
description: Vertegenwoordigt bestandstype.
type: docs
weight: 40
url: /nl/net/groupdocs.watermark.common/filetype/
---
## FileType class

Vertegenwoordigt bestandstype.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Extension](../../groupdocs.watermark.common/filetype/extension) { get; } | Krijgt het achtervoegsel van de bestandsnaam (inclusief de punt ".") bijv. ".doc". |
| [FileFormatName](../../groupdocs.watermark.common/filetype/fileformatname) { get; } | Haalt de naam van het bestandstype op, bijvoorbeeld "Microsoft Word-document". |
| [FormatFamily](../../groupdocs.watermark.common/filetype/formatfamily) { get; } | Krijgt de formaatfamilie. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| static [FromExtension](../../groupdocs.watermark.common/filetype/fromextension)(string) | Wijst de bestandsextensie toe aan het bestandstype. |
| [Equals](../../groupdocs.watermark.common/filetype/equals#equals)(FileType) | Bepaalt of de stroom[`FileType`](../filetype) is hetzelfde als de opgegeven[`FileType`](../filetype) object. |
| override [Equals](../../groupdocs.watermark.common/filetype/equals#equals_1)(object) | Bepaalt of de stroom[`FileType`](../filetype) is hetzelfde als het opgegeven object. |
| override [GetHashCode](../../groupdocs.watermark.common/filetype/gethashcode)() | Retourneert een hash-code voor de huidige[`FileType`](../filetype) object. |
| override [ToString](../../groupdocs.watermark.common/filetype/tostring)() | Retourneert een tekenreeks die het huidige object vertegenwoordigt. |
| static [GetSupportedFileTypes](../../groupdocs.watermark.common/filetype/getsupportedfiletypes)() | Haalt de ondersteunde bestandstypen op. |
| [operator ==](../../groupdocs.watermark.common/filetype/op_equality) | Bepaalt of twee[`FileType`](../filetype) objecten zijn hetzelfde. |
| [operator !=](../../groupdocs.watermark.common/filetype/op_inequality) | Bepaalt of twee[`FileType`](../filetype) objecten zijn niet hetzelfde. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| static readonly [BMP](../../groupdocs.watermark.common/filetype/bmp) | Bestanden met de extensie .BMP vertegenwoordigen bitmapafbeeldingsbestanden die worden gebruikt om digitale bitmapafbeeldingen op te slaan. Deze afbeeldingen zijn onafhankelijk van de grafische adapter en worden ook apparaatonafhankelijk bitmapbestand (DIB) genoemd formaat. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/image/bmp/) . |
| static readonly [DOC](../../groupdocs.watermark.common/filetype/doc) | Bestanden met de extensie .doc vertegenwoordigen documenten die zijn gegenereerd door Microsoft Word of andere tekstverwerkers documenten in binaire bestandsindeling. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/word-processing/doc/) . |
| static readonly [DOCM](../../groupdocs.watermark.common/filetype/docm) | DOCM-bestanden zijn Microsoft Word 2007 of hoger gegenereerde documenten met de mogelijkheid om macro's uit te voeren. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/word-processing/docm/) . |
| static readonly [DOCX](../../groupdocs.watermark.common/filetype/docx) | DOCX is een bekend formaat voor Microsoft Word-documenten. Geïntroduceerd vanaf 2007 met de release van Microsoft Office 2007, werd de structuur van dit nieuwe documentformaat gewijzigd van gewoon binair naar een combinatie van XML en binaire bestanden. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/word-processing/docx/) . |
| static readonly [DOT](../../groupdocs.watermark.common/filetype/dot) | Bestanden met de extensie .DOT zijn sjabloonbestanden die door Microsoft Word zijn gemaakt met vooraf geformatteerde instellingen voor het genereren van verdere DOC- of DOCX-bestanden. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/word-processing/dot/) . |
| static readonly [DOTM](../../groupdocs.watermark.common/filetype/dotm) | Een bestand met de DOTM-extensie vertegenwoordigt een sjabloonbestand dat is gemaakt met Microsoft Word 2007 of hoger. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/word-processing/dotm/) . |
| static readonly [DOTX](../../groupdocs.watermark.common/filetype/dotx) | Bestanden met de DOTX-extensie zijn sjabloonbestanden die door Microsoft Word zijn gemaakt met vooraf geformatteerde instellingen voor het genereren van verdere DOCX-bestanden. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/word-processing/dotx/) . |
| static readonly [EML](../../groupdocs.watermark.common/filetype/eml) | EML-bestandsindeling vertegenwoordigt e-mailberichten die zijn opgeslagen met behulp van Outlook en andere relevante toepassingen. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/email/eml/) . |
| static readonly [EMLX](../../groupdocs.watermark.common/filetype/emlx) | Het EMLX-bestandsformaat is geïmplementeerd en ontwikkeld door Apple. De Apple Mail-applicatie gebruikt het EMLX -bestandsformaat voor het exporteren van de e-mails. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/email/emlx/) . |
| static readonly [FlatOpc](../../groupdocs.watermark.common/filetype/flatopc) | Office Open XML WordprocessingML opgeslagen in een plat XML-bestand in plaats van een ZIP-pakket (.xml). Meer informatie over dit bestandsformaat[hier](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [FlatOpcMacroEnabled](../../groupdocs.watermark.common/filetype/flatopcmacroenabled) | Office Open XML WordprocessingML Macro-Enabled Document opgeslagen in een plat XML-bestand in plaats van een ZIP-pakket (.xml). Meer informatie over deze bestandsindeling[hier](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [FlatOpcTemplate](../../groupdocs.watermark.common/filetype/flatopctemplate) | Office Open XML WordprocessingML-sjabloon (macrovrij) opgeslagen in een plat XML-bestand in plaats van een ZIP-pakket (.xml). Meer informatie over dit bestandsformaat[hier](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [FlatOpcTemplateMacroEnabled](../../groupdocs.watermark.common/filetype/flatopctemplatemacroenabled) | Office Open XML WordprocessingML Macro-enabled sjabloon opgeslagen in een plat XML-bestand in plaats van een ZIP-pakket (.xml). Meer informatie over deze bestandsindeling[hier](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [GIF](../../groupdocs.watermark.common/filetype/gif) | Een GIF of Graphical Interchange Format is een type sterk gecomprimeerde afbeelding. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/image/gif/) . |
| static readonly [JPEG](../../groupdocs.watermark.common/filetype/jpeg) | Een JPEG is een type afbeeldingsindeling die wordt opgeslagen met behulp van compressie met verlies. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/image/jpeg/) . |
| static readonly [JPF](../../groupdocs.watermark.common/filetype/jpf) | JPEG 2000 (JPF) is een beeldcoderingssysteem en de modernste beeldcompressiestandaard. Ontworpen, kan met behulp van wavelet-technologie JPEG 2000 inhoud zonder verlies in elke gewenste kwaliteit tegelijk coderen. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/image/jp2/) . |
| static readonly [JPG](../../groupdocs.watermark.common/filetype/jpg) | Een JPEG is een type afbeeldingsindeling die wordt opgeslagen met behulp van compressie met verlies. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/image/jpeg/) . |
| static readonly [JPM](../../groupdocs.watermark.common/filetype/jpm) | JPEG 2000 (JPM) is een beeldcoderingssysteem en de modernste beeldcompressiestandaard. Ontworpen, kan met behulp van wavelet-technologie JPEG 2000 inhoud zonder verlies in elke gewenste kwaliteit tegelijk coderen. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/image/jp2/) . |
| static readonly [JPX](../../groupdocs.watermark.common/filetype/jpx) | JPEG 2000 (JPX) is een beeldcoderingssysteem en de modernste beeldcompressiestandaard. Ontworpen, kan met behulp van wavelet-technologie JPEG 2000 inhoud zonder verlies in elke gewenste kwaliteit tegelijk coderen. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/image/jp2/) . |
| static readonly [MSG](../../groupdocs.watermark.common/filetype/msg) | MSG is een bestandsindeling die wordt gebruikt door Microsoft Outlook en Exchange om e-mailberichten, contacten, afspraken of andere taken op te slaan. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/email/msg/) . |
| static readonly [ODT](../../groupdocs.watermark.common/filetype/odt) | ODT-bestanden zijn type documenten die zijn gemaakt met tekstverwerkingsprogramma's die zijn gebaseerd op OpenDocument Text File-indeling. Deze zijn gemaakt met tekstverwerkertoepassingen zoals het gratis OpenOffice Writer en kunnen inhoud bevatten zoals tekst, afbeeldingen, objecten en stijlen. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/word-processing/odt/) . |
| static readonly [OFT](../../groupdocs.watermark.common/filetype/oft) | Bestanden met de extensie .OFT vertegenwoordigen berichtsjabloonbestanden die zijn gemaakt met Microsoft Outlook. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/email/oft/) . |
| static readonly [OOXML](../../groupdocs.watermark.common/filetype/ooxml) | Office opent xml-bestand (.ooxml). |
| static readonly [PDF](../../groupdocs.watermark.common/filetype/pdf) | Portable Document Format (PDF) is een type document dat in de jaren negentig door Adobe is gemaakt. Het doel van dit bestandsformaat was om een standaard te introduceren voor de weergave van documenten en ander referentiemateriaal in een formaat dat onafhankelijk is van applicatiesoftware, hardware en het besturingssysteem. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/view/pdf/) . |
| static readonly [PNG](../../groupdocs.watermark.common/filetype/png) | PNG, Portable Network Graphics, verwijst naar een type rasterafbeeldingsbestandsindeling die lossless compressie gebruikt. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/image/png/) . |
| static readonly [POTM](../../groupdocs.watermark.common/filetype/potm) | Bestanden met de POTM-extensie zijn Microsoft PowerPoint-sjabloonbestanden met ondersteuning voor macro's. POTM-bestanden zijn gemaakt met PowerPoint 2007 of hoger en bevatten standaardinstellingen die kunnen worden gebruikt om andere presentatiebestanden te maken. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/potm/) . |
| static readonly [POTX](../../groupdocs.watermark.common/filetype/potx) | Bestanden met de extensie .POTX vertegenwoordigen Microsoft PowerPoint-sjabloonpresentaties die zijn gemaakt met Microsoft PowerPoint 2007 en hoger. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/potx/) . |
| static readonly [PPS](../../groupdocs.watermark.common/filetype/pps) | PPS, PowerPoint-diavoorstelling, bestanden worden gemaakt met behulp van Microsoft PowerPoint voor diavoorstellingen. Het lezen en maken van PPS-bestanden wordt ondersteund door Microsoft PowerPoint 97-2003. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/pps/) . |
| static readonly [PPSM](../../groupdocs.watermark.common/filetype/ppsm) | Bestanden met de PPSM-extensie vertegenwoordigen een diavoorstelling met macro's die is gemaakt met Microsoft PowerPoint 2007 of hoger. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/ppsm/) . |
| static readonly [PPSX](../../groupdocs.watermark.common/filetype/ppsx) | PPSX, PowerPoint-diavoorstelling, bestand is gemaakt met Microsoft PowerPoint 2007 en hoger voor het doel Diavoorstelling. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/ppsx/) . |
| static readonly [PPT](../../groupdocs.watermark.common/filetype/ppt) | Een bestand met de PPT-extensie vertegenwoordigt een PowerPoint-bestand dat bestaat uit een verzameling dia's voor die worden weergegeven als SlideShow. Het specificeert de binaire bestandsindeling die wordt gebruikt door Microsoft PowerPoint 97-2003. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/presentation/ppt/) . |
| static readonly [PPTM](../../groupdocs.watermark.common/filetype/pptm) | Bestanden met de PPTM-extensie zijn presentatiebestanden met macro's die zijn gemaakt met Microsoft PowerPoint 2007 of hogere versies. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/pptm/) . |
| static readonly [PPTX](../../groupdocs.watermark.common/filetype/pptx) | Bestanden met de PPTX-extensie zijn presentatiebestanden die zijn gemaakt met de populaire Microsoft PowerPoint-toepassing. In tegenstelling tot de vorige versie van het presentatiebestandsformaat PPT, dat binair was, is het PPTX-formaat gebaseerd op het open XML-presentatiebestandsformaat van Microsoft PowerPoint. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/presentation/pptx/) . |
| static readonly [RTF](../../groupdocs.watermark.common/filetype/rtf) | Geïntroduceerd en gedocumenteerd door Microsoft, de Rich Text Format (RTF) vertegenwoordigt een methode voor het coderen van geformatteerde tekst en afbeeldingen voor gebruik binnen applicaties. Het formaat vergemakkelijkt platformonafhankelijke document -uitwisseling met andere Microsoft-producten, en dient zo het doel van interoperabiliteit. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/word-processing/rtf/) . |
| static readonly [TIF](../../groupdocs.watermark.common/filetype/tif) | TIFF of TIF, Tagged Image File Format, vertegenwoordigt rasterafbeeldingen die bedoeld zijn voor gebruik op een verscheidenheid apparaten die voldoen aan deze standaard voor bestandsindelingen. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/tiff/) . |
| static readonly [TIFF](../../groupdocs.watermark.common/filetype/tiff) | TIFF of TIF, Tagged Image File Format, vertegenwoordigt rasterafbeeldingen die bedoeld zijn voor gebruik op een verscheidenheid apparaten die voldoen aan deze standaard voor bestandsindelingen. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/tiff/) . |
| static readonly [Unknown](../../groupdocs.watermark.common/filetype/unknown) | Vertegenwoordigt onbekend bestandstype. |
| static readonly [VDW](../../groupdocs.watermark.common/filetype/vdw) | VDW is de Visio Graphics Service-bestandsindeling die de streams en opslagruimte specificeert die nodig zijn voor het renderen van een webtekening. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/web/vdw/) . |
| static readonly [VDX](../../groupdocs.watermark.common/filetype/vdx) | Elke tekening of grafiek die is gemaakt in Microsoft Visio, maar is opgeslagen in XML-indeling, heeft de extensie .VDX. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/image/vdx/) . |
| static readonly [VSD](../../groupdocs.watermark.common/filetype/vsd) | VSD-bestanden zijn tekeningen die zijn gemaakt met de Microsoft Visio-toepassing om verschillende grafische -objecten en de onderlinge verbinding daartussen weer te geven. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/vsd/) . |
| static readonly [VSDM](../../groupdocs.watermark.common/filetype/vsdm) | Bestanden met de extensie VSDM zijn tekenbestanden die zijn gemaakt met de Microsoft Visio-toepassing die macro's ondersteunt. Meer informatie over deze bestandsindeling [hier](https://wiki.fileformat.com/image/vsdm/) . |
| static readonly [VSDX](../../groupdocs.watermark.common/filetype/vsdx) | Bestanden met de extensie .VSDX vertegenwoordigen het Microsoft Visio-bestandsformaat dat vanaf Microsoft Office 2013 is geïntroduceerd. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/vsdx/) . |
| static readonly [VSS](../../groupdocs.watermark.common/filetype/vss) | VSS zijn stencilbestanden die zijn gemaakt met Microsoft Visio 2007 en eerder. Stencilbestanden bieden drawing -objecten die kunnen worden opgenomen in een .VSD Visio-tekening. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/vss/) . |
| static readonly [VSSM](../../groupdocs.watermark.common/filetype/vssm) | Bestanden met de extensie .VSSM zijn Microsoft Visio Stencil-bestanden die ondersteuning bieden voor macro's. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/image/vssm/) . |
| static readonly [VSSX](../../groupdocs.watermark.common/filetype/vssx) | Bestanden met de extensie .VSSX zijn tekensjablonen die zijn gemaakt met Microsoft Visio 2013 en hoger. Meer informatie over deze bestandsindeling [hier](https://wiki.fileformat.com/image/vssx/) . |
| static readonly [VST](../../groupdocs.watermark.common/filetype/vst) | Bestanden met de extensie VST zijn vectorafbeeldingsbestanden gemaakt met Microsoft Visio en fungeren als sjabloon voor het maken van andere bestanden. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/vst/) . |
| static readonly [VSTM](../../groupdocs.watermark.common/filetype/vstm) | Bestanden met de extensie VSTM zijn sjabloonbestanden gemaakt met Microsoft Visio die macro's ondersteunen. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/image/vstm/) . |
| static readonly [VSTX](../../groupdocs.watermark.common/filetype/vstx) | Bestanden met VSTX-extensies zijn tekensjabloonbestanden gemaakt met Microsoft Visio 2013 en hoger. Meer informatie over deze bestandsindeling [hier](https://wiki.fileformat.com/image/vstx/) . |
| static readonly [VSX](../../groupdocs.watermark.common/filetype/vsx) | Bestanden met de extensie .VSX verwijzen naar stencils die bestaan uit tekeningen en vormen die worden gebruikt voor het maken van diagrammen in Microsoft Visio. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/image/vsx/) . |
| static readonly [VTX](../../groupdocs.watermark.common/filetype/vtx) | Een bestand met de extensie VTX is een Microsoft Visio-tekeningsjabloon dat in XML-bestandsindeling op schijf wordt opgeslagen. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/image/vtx/) . |
| static readonly [WEBP](../../groupdocs.watermark.common/filetype/webp) | WebP, geïntroduceerd door Google, is een moderne bestandsindeling voor rasterwebafbeeldingen die is gebaseerd op lossless en lossy compressie. Het biedt dezelfde beeldkwaliteit terwijl de afbeeldingsgrootte aanzienlijk wordt verkleind. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/image/webp/) . |
| static readonly [XLS](../../groupdocs.watermark.common/filetype/xls) | Bestanden met de extensie XLS vertegenwoordigen de binaire bestandsindeling van Excel. Dergelijke bestanden kunnen worden gemaakt door Microsoft Excel en andere vergelijkbare spreadsheetprogramma's zoals OpenOffice Calc of Apple Numbers. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/specification/spreadsheet/xls/) . |
| static readonly [XLSB](../../groupdocs.watermark.common/filetype/xlsb) | XLSB-bestandsindeling specificeert de Excel binaire bestandsindeling, een verzameling records en -structuren die de inhoud van de Excel-werkmap specificeren. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/specification/spreadsheet/xlsb/) . |
| static readonly [XLSM](../../groupdocs.watermark.common/filetype/xlsm) | Bestanden met de extensie XLSM is een type spreadsheet-bestand dat macro's ondersteunt. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/specification/spreadsheet/xlsm/) . |
| static readonly [XLSX](../../groupdocs.watermark.common/filetype/xlsx) | XLSX is een bekende indeling voor Microsoft Excel-documenten die door Microsoft is geïntroduceerd met release van Microsoft Office 2007. Meer informatie over deze bestandsindeling [hier](https://wiki.fileformat.com/specification/spreadsheet/xlsx/) . |
| static readonly [XLT](../../groupdocs.watermark.common/filetype/xlt) | Bestanden met de extensie .XLT zijn sjabloonbestanden die zijn gemaakt met Microsoft Excel, een spreadsheet -toepassing die deel uitmaakt van de Microsoft Office-suite. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/specification/spreadsheet/xlt/) . |
| static readonly [XLTM](../../groupdocs.watermark.common/filetype/xltm) | De XLTM-bestandsextensie vertegenwoordigt bestanden die door Microsoft Excel worden gegenereerd als macro-enabled -sjabloonbestanden. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/specification/spreadsheet/xltm/) . |
| static readonly [XLTX](../../groupdocs.watermark.common/filetype/xltx) | Bestanden met de extensie XLTX vertegenwoordigen Microsoft Excel-sjabloonbestanden die zijn gebaseerd op de Office OpenXML bestandsformaatspecificaties. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/specification/spreadsheet/xltx/) . |

### Opmerkingen

Deze klasse biedt methoden om een lijst te verkrijgen van alle bestandstypen die worden ondersteund door**GroupDocs.Watermerk**.**Kom meer te weten**

* [Ondersteunde documentindelingen](https://docs.groupdocs.com/display/watermarknet/Supported+Document+Formats)
* [Download ondersteunde bestandsindelingen](https://docs.groupdocs.com/display/watermarknet/Get+supported+file+formats)
* [Documentinformatie ophalen](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### Zie ook

* naamruimte [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* montage [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
