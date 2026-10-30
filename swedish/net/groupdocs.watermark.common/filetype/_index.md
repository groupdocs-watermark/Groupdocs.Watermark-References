---
title: "FileType"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar filtyp."
type: docs
weight: 40
url: /sv/net/groupdocs.watermark.common/filetype/
---
## FileType class

Representerar filtyp.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Extension](../../groupdocs.watermark.common/filetype/extension) { get; } | Hämtar filnamnssuffixet (inklusive punkten ".") t.ex. ".doc". |
| [FileFormatName](../../groupdocs.watermark.common/filetype/fileformatname) { get; } | Hämtar filtypens namn t.ex. "Microsoft Word Document". |
| [FormatFamily](../../groupdocs.watermark.common/filetype/formatfamily) { get; } | Hämtar formatfamiljen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [FromExtension](../../groupdocs.watermark.common/filetype/fromextension)(string) | Mappar filändelsen till filtypen. |
| [Equals](../../groupdocs.watermark.common/filetype/equals#equals)(FileType) | Bestämmer om den aktuella [`FileType`](../filetype) är densamma som det angivna [`FileType`](../filetype)-objektet. |
| override [Equals](../../groupdocs.watermark.common/filetype/equals#equals_1)(object) | Avgör om den aktuella [`FileType`](../filetype) är densamma som det angivna objektet. |
| override [GetHashCode](../../groupdocs.watermark.common/filetype/gethashcode)() | Returnerar en hashkod för det aktuella [`FileType`](../filetype)-objektet. |
| override [ToString](../../groupdocs.watermark.common/filetype/tostring)() | Returnerar en sträng som representerar det aktuella objektet. |
| static [GetSupportedFileTypes](../../groupdocs.watermark.common/filetype/getsupportedfiletypes)() | Hämtar de stödjade filtyperna. |
| [operator ==](../../groupdocs.watermark.common/filetype/op_equality) | Avgör om två [`FileType`](../filetype)-objekt är desamma. |
| [operator !=](../../groupdocs.watermark.common/filetype/op_inequality) | Avgör om två [`FileType`](../filetype)-objekt inte är desamma. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| static readonly [BMP](../../groupdocs.watermark.common/filetype/bmp) | Filer med filändelsen .BMP representerar Bitmap Image-filer som används för att lagra bitmap-digitalbilder. Dessa bilder är oberoende av grafikadapter och kallas även device independent bitmap (DIB)-filformat. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/bmp/). |
| static readonly [DOC](../../groupdocs.watermark.common/filetype/doc) | Filer med .doc‑ändelse representerar dokument som genererats av Microsoft Word eller andra ordbehandlingsprogram i binärt filformat. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/doc/). |
| static readonly [DOCM](../../groupdocs.watermark.common/filetype/docm) | DOCM‑filer är dokument som skapats av Microsoft Word 2007 eller senare med möjlighet att köra makron. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/docm/). |
| static readonly [DOCX](../../groupdocs.watermark.common/filetype/docx) | DOCX är ett välkänt format för Microsoft Word‑dokument. Introducerat från 2007 med lanseringen av Microsoft Office 2007 förändrades strukturen för detta nya dokumentformat från ren binär till en kombination av XML‑ och binära filer. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/docx/). |
| static readonly [DOT](../../groupdocs.watermark.common/filetype/dot) | Filer med .DOT‑ändelse är mallfiler som skapats av Microsoft Word för att ha förformaterade inställningar för generering av ytterligare DOC‑ eller DOCX‑filer. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/dot/). |
| static readonly [DOTM](../../groupdocs.watermark.common/filetype/dotm) | En fil med DOTM‑ändelse representerar en mallfil skapad med Microsoft Word 2007 eller senare. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/dotm/). |
| static readonly [DOTX](../../groupdocs.watermark.common/filetype/dotx) | Filer med .DOTX‑ändelse är mallfiler som skapats av Microsoft Word för att ha förformaterade inställningar för generering av ytterligare DOCX‑filer. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/dotx/). |
| static readonly [EML](../../groupdocs.watermark.common/filetype/eml) | EML‑filformatet representerar e‑postmeddelanden som sparats med Outlook och andra relevanta program. Läs mer om detta filformat [här](https://wiki.fileformat.com/email/eml/). |
| static readonly [EMLX](../../groupdocs.watermark.common/filetype/emlx) | EMLX‑filformatet är implementerat och utvecklat av Apple. Apple Mail‑applikationen använder EMLX‑filformatet för att exportera e‑postmeddelanden. Läs mer om detta filformat [här](https://wiki.fileformat.com/email/emlx/). |
| static readonly [FlatOpc](../../groupdocs.watermark.common/filetype/flatopc) | Office Open XML WordprocessingML lagras i en platt XML‑fil istället för ett ZIP‑paket (.xml). Läs mer om detta filformat [här](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [FlatOpcMacroEnabled](../../groupdocs.watermark.common/filetype/flatopcmacroenabled) | Office Open XML WordprocessingML makroaktiverat dokument lagras i en platt XML‑fil istället för ett ZIP‑paket (.xml). Läs mer om detta filformat [här](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [FlatOpcTemplate](../../groupdocs.watermark.common/filetype/flatopctemplate) | Office Open XML WordprocessingML‑mall (utan makro) lagras i en platt XML‑fil istället för ett ZIP‑paket (.xml). Läs mer om detta filformat [här](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [FlatOpcTemplateMacroEnabled](../../groupdocs.watermark.common/filetype/flatopctemplatemacroenabled) | Office Open XML WordprocessingML Macro-Enabled Template lagrad i en platt XML-fil istället för ett ZIP-paket (.xml). Läs mer om detta filformat [här](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [GIF](../../groupdocs.watermark.common/filetype/gif) | En GIF eller Graphical Interchange Format är en typ av starkt komprimerad bild. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/gif/). |
| static readonly [JPEG](../../groupdocs.watermark.common/filetype/jpeg) | En JPEG är en typ av bildformat som sparas med metoden för förlustkomprimering. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/jpeg/). |
| static readonly [JPF](../../groupdocs.watermark.common/filetype/jpf) | JPEG 2000 (JPF) är ett bildkodningssystem och en toppmodern bildkomprimeringsstandard. Designad med vågformsteknik kan JPEG 2000 koda förlustfri innehåll i vilken kvalitet som helst på en gång. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/jp2/). |
| static readonly [JPG](../../groupdocs.watermark.common/filetype/jpg) | En JPEG är en typ av bildformat som sparas med metoden för förlustkomprimering. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/jpeg/). |
| static readonly [JPM](../../groupdocs.watermark.common/filetype/jpm) | JPEG 2000 (JPM) är ett bildkodningssystem och en toppmodern bildkomprimeringsstandard. Designad med vågformsteknik kan JPEG 2000 koda förlustfri innehåll i vilken kvalitet som helst på en gång. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/jp2/). |
| static readonly [JPX](../../groupdocs.watermark.common/filetype/jpx) | JPEG 2000 (JPX) är ett bildkodningssystem och en toppmodern bildkomprimeringsstandard. Designad med vågformsteknik kan JPEG 2000 koda förlustfri innehåll i vilken kvalitet som helst på en gång. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/jp2/). |
| static readonly [MSG](../../groupdocs.watermark.common/filetype/msg) | MSG är ett filformat som används av Microsoft Outlook och Exchange för att lagra e-postmeddelanden, kontakter, möten eller andra uppgifter. Läs mer om detta filformat [här](https://wiki.fileformat.com/email/msg/). |
| static readonly [ODT](../../groupdocs.watermark.common/filetype/odt) | ODT-filer är en typ av dokument som skapas med ordbehandlingsprogram baserade på OpenDocument Text-filformatet. De skapas med ordbehandlingsprogram såsom den fria OpenOffice Writer och kan innehålla innehåll som text, bilder, objekt och stilar. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/odt/). |
| static readonly [OFT](../../groupdocs.watermark.common/filetype/oft) | Filer med .OFT‑tillägg representerar meddelandemallar som skapas med Microsoft Outlook. Läs mer om detta filformat [här](https://wiki.fileformat.com/email/oft/). |
| static readonly [OOXML](../../groupdocs.watermark.common/filetype/ooxml) | Office Open XML‑fil (.ooxml). |
| static readonly [PDF](../../groupdocs.watermark.common/filetype/pdf) | Portable Document Format (PDF) är en typ av dokument som skapades av Adobe på 1990‑talet. Syftet med detta filformat var att införa en standard för representation av dokument och annat referensmaterial i ett format som är oberoende av programvara, hårdvara samt operativsystem. Läs mer om detta filformat [här](https://wiki.fileformat.com/view/pdf/). |
| static readonly [PNG](../../groupdocs.watermark.common/filetype/png) | PNG, Portable Network Graphics, avser en typ av rasterbildsfilformat som använder förlustfri kompression. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/png/). |
| static readonly [POTM](../../groupdocs.watermark.common/filetype/potm) | Filer med POTM‑tillägg är Microsoft PowerPoint‑mallar med stöd för makron. POTM-filer skapas med PowerPoint 2007 eller senare och innehåller standardinställningar som kan användas för att skapa ytterligare presentationsfiler. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/potm/). |
| static readonly [POTX](../../groupdocs.watermark.common/filetype/potx) | Filer med .POTX‑extension representerar Microsoft PowerPoint‑mallpresentationer som skapas med Microsoft PowerPoint 2007 och senare. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/potx/). |
| static readonly [PPS](../../groupdocs.watermark.common/filetype/pps) | PPS, PowerPoint‑bildspel, filer skapas med Microsoft PowerPoint för bildspelsändamål. PPS‑filens läsning och skapande stöds av Microsoft PowerPoint 97‑2003. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/pps/). |
| static readonly [PPSM](../../groupdocs.watermark.common/filetype/ppsm) | Filer med PPSM‑extension representerar makroaktiverat bildspelsfilformat skapat med Microsoft PowerPoint 2007 eller senare. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/ppsm/). |
| static readonly [PPSX](../../groupdocs.watermark.common/filetype/ppsx) | PPSX, Power Point‑bildspel, filer skapas med Microsoft PowerPoint 2007 och senare för bildspelsändamål. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/ppsx/). |
| static readonly [PPT](../../groupdocs.watermark.common/filetype/ppt) | En fil med PPT‑extension representerar en PowerPoint‑fil som består av en samling bilder för visning som bildspel. Den specificerar det binära filformatet som används av Microsoft PowerPoint 97‑2003. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/ppt/). |
| static readonly [PPTM](../../groupdocs.watermark.common/filetype/pptm) | Filer med PPTM‑extension är makroaktiverade presentationsfiler som skapas med Microsoft PowerPoint 2007 eller senare versioner. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/pptm/). |
| static readonly [PPTX](../../groupdocs.watermark.common/filetype/pptx) | Filer med PPTX‑extension är presentationsfiler som skapats med det populära Microsoft PowerPoint‑programmet. Till skillnad från den tidigare versionen av presentationsfilformatet PPT som var binärt, är PPTX‑formatet baserat på Microsoft PowerPoints öppna XML‑presentationsfilformat. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/pptx/). |
| static readonly [RTF](../../groupdocs.watermark.common/filetype/rtf) | Introducerat och dokumenterat av Microsoft, representerar Rich Text Format (RTF) en metod för att koda formaterad text och grafik för användning i applikationer. Formatet underlättar plattformsoberoende dokumentutbyte med andra Microsoft‑produkter, vilket möjliggör interoperabilitet. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/rtf/). |
| static readonly [TIF](../../groupdocs.watermark.common/filetype/tif) | TIFF eller TIF, Tagged Image File Format, representerar rasterbilder som är avsedda för användning på en mängd olika enheter som följer denna filformatstandard. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/tiff/). |
| static readonly [TIFF](../../groupdocs.watermark.common/filetype/tiff) | TIFF eller TIF, Tagged Image File Format, representerar rasterbilder som är avsedda för användning på en mängd olika enheter som följer denna filformatstandard. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/tiff/). |
| static readonly [Unknown](../../groupdocs.watermark.common/filetype/unknown) | Representerar okänd filtyp. |
| static readonly [VDW](../../groupdocs.watermark.common/filetype/vdw) | VDW är Visio Graphics Service‑filformatet som specificerar de strömmar och lagringar som krävs för rendering av en webbteckning. Läs mer om detta filformat [här](https://wiki.fileformat.com/web/vdw/). |
| static readonly [VDX](../../groupdocs.watermark.common/filetype/vdx) | Alla ritningar eller diagram som skapats i Microsoft Visio, men sparats i XML‑format, har .VDX‑extension. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vdx/). |
| static readonly [VSD](../../groupdocs.watermark.common/filetype/vsd) | VSD‑filer är ritningar som skapats med Microsoft Visio‑applikationen för att representera en mängd grafiska objekt och deras sammankoppling. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vsd/). |
| static readonly [VSDM](../../groupdocs.watermark.common/filetype/vsdm) | Filer med VSDM‑tillägg är ritningsfiler som skapats med Microsoft Visio‑programmet som stöder makron. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vsdm/). |
| static readonly [VSDX](../../groupdocs.watermark.common/filetype/vsdx) | Filer med .VSDX‑tillägg representerar Microsoft Visio‑filformatet som introducerades från Microsoft Office 2013 och framåt. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vsdx/). |
| static readonly [VSS](../../groupdocs.watermark.common/filetype/vss) | VSS är stencil‑filer som skapats med Microsoft Visio 2007 och tidigare. Stencil‑filer tillhandahåller ritobjekt som kan inkluderas i en .VSD Visio‑ritning. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vss/). |
| static readonly [VSSM](../../groupdocs.watermark.common/filetype/vssm) | Filer med .VSSM‑tillägg är Microsoft Visio‑stencil‑filer som ger stöd för makron. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vssm/). |
| static readonly [VSSX](../../groupdocs.watermark.common/filetype/vssx) | Filer med .VSSX‑tillägg är ritningsstencil‑filer som skapats med Microsoft Visio 2013 och senare. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vssx/). |
| static readonly [VST](../../groupdocs.watermark.common/filetype/vst) | Filer med VST‑tillägg är vektorbildfiler som skapats med Microsoft Visio och fungerar som mall för att skapa ytterligare filer. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vst/). |
| static readonly [VSTM](../../groupdocs.watermark.common/filetype/vstm) | Filer med VSTM‑tillägg är mallfiler som skapats med Microsoft Visio och som stöder makron. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vstm/). |
| static readonly [VSTX](../../groupdocs.watermark.common/filetype/vstx) | Filer med VSTX‑tillägg är ritningsmallfiler som skapats med Microsoft Visio 2013 och senare. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vstx/). |
| static readonly [VSX](../../groupdocs.watermark.common/filetype/vsx) | Filer med .VSX‑tillägg avser stencil‑filer som består av ritningar och former som används för att skapa diagram i Microsoft Visio. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vsx/). |
| static readonly [VTX](../../groupdocs.watermark.common/filetype/vtx) | En fil med VTX‑tillägg är en Microsoft Visio‑ritningsmall som sparas på disk i XML‑filformat. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vtx/). |
| static readonly [WEBP](../../groupdocs.watermark.common/filetype/webp) | WebP, introducerat av Google, är ett modernt rasterwebb‑bildfilformat som baseras på förlustfri och förlustkomprimering. Det ger samma bildkvalitet samtidigt som det avsevärt minskar bildstorleken. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/webp/). |
| static readonly [XLS](../../groupdocs.watermark.common/filetype/xls) | Filer med XLS‑tillägg representerar Excel Binary File Format. Sådana filer kan skapas av Microsoft Excel såväl som andra liknande kalkylprogram som OpenOffice Calc eller Apple Numbers. Läs mer om detta filformat [här](https://wiki.fileformat.com/specification/spreadsheet/xls/). |
| static readonly [XLSB](../../groupdocs.watermark.common/filetype/xlsb) | XLSB‑filformatet specificerar Excel Binary File Format, vilket är en samling poster och strukturer som specificerar innehållet i en Excel‑arbetsbok. Läs mer om detta filformat [här](https://wiki.fileformat.com/specification/spreadsheet/xlsb/). |
| static readonly [XLSM](../../groupdocs.watermark.common/filetype/xlsm) | Filer med XLSM‑tillägg är en typ av kalkylbladsfiler som stöder makron. Läs mer om detta filformat [här](https://wiki.fileformat.com/specification/spreadsheet/xlsm/). |
| static readonly [XLSX](../../groupdocs.watermark.common/filetype/xlsx) | XLSX är ett välkänt format för Microsoft Excel‑dokument som introducerades av Microsoft med lanseringen av Microsoft Office 2007. Läs mer om detta filformat [här](https://wiki.fileformat.com/specification/spreadsheet/xlsx/). |
| static readonly [XLT](../../groupdocs.watermark.common/filetype/xlt) | Filer med .XLT‑tillägg är mallfiler som skapats med Microsoft Excel, vilket är ett kalkylprogram som ingår i Microsoft Office‑sviten. Läs mer om detta filformat [här](https://wiki.fileformat.com/specification/spreadsheet/xlt/). |
| static readonly [XLTM](../../groupdocs.watermark.common/filetype/xltm) | XLTM‑filändelsen representerar filer som genereras av Microsoft Excel som makroaktiverade mallfiler. Läs mer om detta filformat [här](https://wiki.fileformat.com/specification/spreadsheet/xltm/). |
| static readonly [XLTX](../../groupdocs.watermark.common/filetype/xltx) | Filer med XLTX‑tillägg representerar Microsoft Excel‑mallfiler som är baserade på Office OpenXML‑filformatspecifikationerna. Läs mer om detta filformat [här](https://wiki.fileformat.com/specification/spreadsheet/xltx/). |

### Anmärkningar

Denna klass tillhandahåller metoder för att hämta en lista över alla filtyper som stöds av **GroupDocs.Watermark**.**Läs mer**

* [Supported Document Formats](https://docs.groupdocs.com/display/watermarknet/Supported+Document+Formats)
* [Get supported file formats](https://docs.groupdocs.com/display/watermarknet/Get+supported+file+formats)
* [Get document info](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### Se även

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
