---
title: FileType
second_title: GroupDocs.Watermark for .NET API-referens
description: Representerar filtyp.
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

| namn | Beskrivning |
| --- | --- |
| [Extension](../../groupdocs.watermark.common/filetype/extension) { get; } | Hämtar filnamnssuffixet (inklusive punkten ".") t.ex. ".doc". |
| [FileFormatName](../../groupdocs.watermark.common/filetype/fileformatname) { get; } | Hämtar filtypsnamnet t.ex. "Microsoft Word Document". |
| [FormatFamily](../../groupdocs.watermark.common/filetype/formatfamily) { get; } | Hämtar formatfamiljen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [FromExtension](../../groupdocs.watermark.common/filetype/fromextension)(string) | Mappar filtillägget till filtypen. |
| [Equals](../../groupdocs.watermark.common/filetype/equals#equals)(FileType) | Bestämmer om strömmen[`FileType`](../filetype) är samma som den angivna[`FileType`](../filetype) objekt. |
| override [Equals](../../groupdocs.watermark.common/filetype/equals#equals_1)(object) | Bestämmer om strömmen[`FileType`](../filetype) är samma som det angivna objektet. |
| override [GetHashCode](../../groupdocs.watermark.common/filetype/gethashcode)() | Returnerar en hash-kod för strömmen[`FileType`](../filetype) objekt. |
| override [ToString](../../groupdocs.watermark.common/filetype/tostring)() | Returnerar en sträng som representerar det aktuella objektet. |
| static [GetSupportedFileTypes](../../groupdocs.watermark.common/filetype/getsupportedfiletypes)() | Hämtar de filtyper som stöds. |
| [operator ==](../../groupdocs.watermark.common/filetype/op_equality) | Bestämmer om två[`FileType`](../filetype) objekten är desamma. |
| [operator !=](../../groupdocs.watermark.common/filetype/op_inequality) | Bestämmer om två[`FileType`](../filetype) objekt är inte samma sak. |

## Fält

| namn | Beskrivning |
| --- | --- |
| static readonly [BMP](../../groupdocs.watermark.common/filetype/bmp) | Filer med filtillägget .BMP representerar bitmappsbildfiler som används för att lagra digitala bitmappsbilder. Dessa bilder är oberoende av grafikkort och kallas även enhetsoberoende bitmapp (DIB) file -format. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/bmp/) . |
| static readonly [DOC](../../groupdocs.watermark.common/filetype/doc) | Filer med filtillägget .doc representerar dokument som genererats av Microsoft Word eller andra ordbehandlingsdokument i binärt filformat. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/doc/) . |
| static readonly [DOCM](../../groupdocs.watermark.common/filetype/docm) | DOCM-filer är Microsoft Word 2007 eller högre genererade dokument med möjlighet att köra makron. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/docm/) . |
| static readonly [DOCX](../../groupdocs.watermark.common/filetype/docx) | DOCX är ett välkänt format för Microsoft Word-dokument. Introducerad från 2007 med release av Microsoft Office 2007, ändrades strukturen för detta nya dokumentformat från vanlig binary till en kombination av XML och binära filer. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/docx/) . |
| static readonly [DOT](../../groupdocs.watermark.common/filetype/dot) | Filer med filtillägget .DOT är mallfiler skapade av Microsoft Word för att ha förformaterade settings för generering av ytterligare DOC- eller DOCX-filer. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/dot/) . |
| static readonly [DOTM](../../groupdocs.watermark.common/filetype/dotm) | En fil med DOTM-tillägget representerar en mallfil skapad med Microsoft Word 2007 eller högre. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/dotm/) . |
| static readonly [DOTX](../../groupdocs.watermark.common/filetype/dotx) | Filer med DOTX-tillägg är mallfiler skapade av Microsoft Word för att ha förformaterade settings för generering av ytterligare DOCX-filer. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/dotx/) . |
| static readonly [EML](../../groupdocs.watermark.common/filetype/eml) | EML-filformat representerar e-postmeddelanden som sparats med Outlook och andra relevanta applikationer. Läs mer om detta filformat[här](https://wiki.fileformat.com/email/eml/) . |
| static readonly [EMLX](../../groupdocs.watermark.common/filetype/emlx) | EMLX-filformatet är implementerat och utvecklat av Apple. Apple Mail-applikationen använder filformatet EMLX för att exportera e-postmeddelanden. Läs mer om detta filformat [här](https://wiki.fileformat.com/email/emlx/) . |
| static readonly [FlatOpc](../../groupdocs.watermark.common/filetype/flatopc) | Office Open XML WordprocessingML lagrad i en platt XML-fil istället för ett ZIP-paket (.xml). Läs mer om detta filformat[här](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [FlatOpcMacroEnabled](../../groupdocs.watermark.common/filetype/flatopcmacroenabled) | Office Open XML WordprocessingML Macro-Enabled Document lagras i en platt XML-fil istället för ett ZIP-paket (.xml). Läs mer om detta filformat[här](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [FlatOpcTemplate](../../groupdocs.watermark.common/filetype/flatopctemplate) | Office Open XML WordprocessingML-mall (makrofri) lagrad i en platt XML-fil istället för ett ZIP-paket (.xml). Läs mer om detta filformat[här](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [FlatOpcTemplateMacroEnabled](../../groupdocs.watermark.common/filetype/flatopctemplatemacroenabled) | Office Open XML WordprocessingML Macro-Enabled Mall lagrad i en platt XML-fil istället för ett ZIP-paket (.xml). Läs mer om detta filformat[här](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [GIF](../../groupdocs.watermark.common/filetype/gif) | En GIF eller Graphical Interchange Format är en typ av mycket komprimerad bild. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/gif/) . |
| static readonly [JPEG](../../groupdocs.watermark.common/filetype/jpeg) | En JPEG är en typ av bildformat som sparas med metoden för förlustkomprimering. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/jpeg/) . |
| static readonly [JPF](../../groupdocs.watermark.common/filetype/jpf) | JPEG 2000 (JPF) är ett bildkodningssystem och en toppmodern bildkomprimeringsstandard. Designad, med hjälp av wavelet-teknik JPEG 2000 kan koda förlustfritt innehåll i vilken kvalitet som helst på en gång. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/jp2/) . |
| static readonly [JPG](../../groupdocs.watermark.common/filetype/jpg) | En JPEG är en typ av bildformat som sparas med metoden för förlustkomprimering. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/jpeg/) . |
| static readonly [JPM](../../groupdocs.watermark.common/filetype/jpm) | JPEG 2000 (JPM) är ett bildkodningssystem och en toppmodern bildkomprimeringsstandard. Designad, med hjälp av wavelet-teknik JPEG 2000 kan koda förlustfritt innehåll i vilken kvalitet som helst på en gång. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/jp2/) . |
| static readonly [JPX](../../groupdocs.watermark.common/filetype/jpx) | JPEG 2000 (JPX) är ett bildkodningssystem och en toppmodern bildkomprimeringsstandard. Designad, med hjälp av wavelet-teknik JPEG 2000 kan koda förlustfritt innehåll i vilken kvalitet som helst på en gång. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/jp2/) . |
| static readonly [MSG](../../groupdocs.watermark.common/filetype/msg) | MSG är ett filformat som används av Microsoft Outlook och Exchange för att lagra e-postmeddelanden, kontakt, möte eller andra uppgifter. Läs mer om detta filformat [här](https://wiki.fileformat.com/email/msg/) . |
| static readonly [ODT](../../groupdocs.watermark.common/filetype/odt) | ODT-filer är typ av dokument skapade med ordbehandlingsprogram som är baserade på OpenDocument Text File-format. Dessa skapas med ordbehandlingsprogram som gratis OpenOffice Writer och kan innehålla innehåll som text, bilder, objekt och stilar. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/odt/) . |
| static readonly [OFT](../../groupdocs.watermark.common/filetype/oft) | Filer med filtillägget .OFT representerar meddelandemallsfiler som skapats med Microsoft Outlook. Läs mer om detta filformat[här](https://wiki.fileformat.com/email/oft/) . |
| static readonly [OOXML](../../groupdocs.watermark.common/filetype/ooxml) | Office öppen xml-fil (.ooxml). |
| static readonly [PDF](../../groupdocs.watermark.common/filetype/pdf) | Portable Document Format (PDF) är en typ av dokument som skapades av Adobe redan på 1990-talet. Syftet med detta filformat var att införa en standard för representation av dokument och annat referensmaterial i ett format som är oberoende av applikationsprogramvara, hårdvara samt operativsystem. Läs mer om detta filformat[här](https://wiki.fileformat.com/view/pdf/) . |
| static readonly [PNG](../../groupdocs.watermark.common/filetype/png) | PNG, Portable Network Graphics, hänvisar till en typ av rasterbildsfilformat som använder förlustfri komprimering. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/png/) . |
| static readonly [POTM](../../groupdocs.watermark.common/filetype/potm) | Filer med POTM-tillägg är Microsoft PowerPoint-mallfiler med stöd för makron. POTM-filer skapas med PowerPoint 2007 eller senare och innehåller standardinställningar som kan användas för att skapa ytterligare presentationsfiler. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/potm/) . |
| static readonly [POTX](../../groupdocs.watermark.common/filetype/potx) | Filer med tillägget .POTX representerar Microsoft PowerPoint-mallpresentationer som skapas med Microsoft PowerPoint 2007 och senare. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/potx/) . |
| static readonly [PPS](../../groupdocs.watermark.common/filetype/pps) | PPS, PowerPoint Slide Show, filer skapas med Microsoft PowerPoint för Slide Show-ändamål. Läsning och skapande av PPS-filer stöds av Microsoft PowerPoint 97-2003. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/pps/) . |
| static readonly [PPSM](../../groupdocs.watermark.common/filetype/ppsm) | Filer med PPSM-tillägget representerar Macro-aktiverat bildspelsfilformat som skapats med Microsoft PowerPoint 2007 eller högre. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/ppsm/) . |
| static readonly [PPSX](../../groupdocs.watermark.common/filetype/ppsx) | PPSX, Power Point Slide Show, filen skapas med Microsoft PowerPoint 2007 och högre för Slide Show syfte. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/ppsx/) . |
| static readonly [PPT](../../groupdocs.watermark.common/filetype/ppt) | En fil med PPT-tillägg representerar en PowerPoint-fil som består av en samling bilder för som visas som bildspel. Den anger det binära filformatet som används av Microsoft PowerPoint 97-2003. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/ppt/) . |
| static readonly [PPTM](../../groupdocs.watermark.common/filetype/pptm) | Filer med PPTM-tillägg är makroaktiverade presentationsfiler som skapas med Microsoft PowerPoint 2007 eller högre versioner. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/pptm/) . |
| static readonly [PPTX](../../groupdocs.watermark.common/filetype/pptx) | Filer med PPTX-tillägg är presentationsfiler skapade med populära Microsoft PowerPoint-applikation. Till skillnad från den tidigare versionen av presentationsfilformatet PPT som var binärt, är PPTX-formatet baserat på Microsoft PowerPoints öppna XML-presentationsfilformat. Läs mer om detta filformat [här](https://wiki.fileformat.com/presentation/pptx/) . |
| static readonly [RTF](../../groupdocs.watermark.common/filetype/rtf) | Introducerat och dokumenterat av Microsoft, Rich Text Format (RTF) representerar en metod för att koda formaterad text och grafik för användning i applikationer. Formatet underlättar plattformsoberoende dokument utbyte med andra Microsoft-produkter, vilket tjänar syftet med interoperabilitet. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/rtf/) . |
| static readonly [TIF](../../groupdocs.watermark.common/filetype/tif) | TIFF eller TIF, Tagged Image File Format, representerar rasterbilder som är avsedda för användning på en mängd av enheter som överensstämmer med denna filformatstandard. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/tiff/) . |
| static readonly [TIFF](../../groupdocs.watermark.common/filetype/tiff) | TIFF eller TIF, Tagged Image File Format, representerar rasterbilder som är avsedda för användning på en mängd av enheter som överensstämmer med denna filformatstandard. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/tiff/) . |
| static readonly [Unknown](../../groupdocs.watermark.common/filetype/unknown) | Representerar okänd filtyp. |
| static readonly [VDW](../../groupdocs.watermark.common/filetype/vdw) | VDW är filformatet Visio Graphics Service som anger de strömmar och lagringar som krävs för att rendera en webbritning. Läs mer om detta filformat [här](https://wiki.fileformat.com/web/vdw/) . |
| static readonly [VDX](../../groupdocs.watermark.common/filetype/vdx) | Alla ritningar eller diagram som skapats i Microsoft Visio men som sparats i XML-format har filtillägget .VDX. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/vdx/) . |
| static readonly [VSD](../../groupdocs.watermark.common/filetype/vsd) | VSD-filer är ritningar skapade med Microsoft Visio-applikationen för att representera olika grafiska -objekt och sammankopplingen mellan dessa. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vsd/) . |
| static readonly [VSDM](../../groupdocs.watermark.common/filetype/vsdm) | Filer med VSDM-tillägg är ritfiler skapade med Microsoft Visio-applikation som stöder makron. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vsdm/) . |
| static readonly [VSDX](../../groupdocs.watermark.common/filetype/vsdx) | Filer med tillägget .VSDX representerar filformatet Microsoft Visio som introducerats från Microsoft Office 2013 och framåt. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vsdx/) . |
| static readonly [VSS](../../groupdocs.watermark.common/filetype/vss) | VSS är stencilfiler skapade med Microsoft Visio 2007 och tidigare. Stencilfiler tillhandahåller drawing -objekt som kan inkluderas i en .VSD Visio-ritning. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vss/) . |
| static readonly [VSSM](../../groupdocs.watermark.common/filetype/vssm) | Filer med filtillägget .VSSM är Microsoft Visio Stencil-filer som stöder ger stöd för makron. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/vssm/) . |
| static readonly [VSSX](../../groupdocs.watermark.common/filetype/vssx) | Filer med tillägget .VSSX är ritschabloner skapade med Microsoft Visio 2013 och senare. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vssx/) . |
| static readonly [VST](../../groupdocs.watermark.common/filetype/vst) | Filer med VST-tillägg är vektorbildfiler skapade med Microsoft Visio och fungerar som mall för att skapa ytterligare filer. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vst/) . |
| static readonly [VSTM](../../groupdocs.watermark.common/filetype/vstm) | Filer med VSTM-tillägg är mallfiler skapade med Microsoft Visio som stöder makron. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/vstm/) . |
| static readonly [VSTX](../../groupdocs.watermark.common/filetype/vstx) | Filer med VSTX-tillägg är ritmallsfiler skapade med Microsoft Visio 2013 och högre. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vstx/) . |
| static readonly [VSX](../../groupdocs.watermark.common/filetype/vsx) | Filer med filtillägget .VSX hänvisar till schabloner som består av ritningar och former som används för att skapa diagram i Microsoft Visio. Läs mer om detta filformat [här](https://wiki.fileformat.com/image/vsx/) . |
| static readonly [VTX](../../groupdocs.watermark.common/filetype/vtx) | En fil med VTX-tillägg är en Microsoft Visio-ritmall som sparas på skiva i XML-filformat. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/vtx/) . |
| static readonly [WEBP](../../groupdocs.watermark.common/filetype/webp) | WebP, introducerat av Google, är ett modernt rasterwebbbildfilformat som är baserat på förlustfri och förlustfri komprimering. Den ger samma bildkvalitet samtidigt som den minskar bildstorleken avsevärt. Läs mer om detta filformat[här](https://wiki.fileformat.com/image/webp/) . |
| static readonly [XLS](../../groupdocs.watermark.common/filetype/xls) | Filer med XLS-tillägg representerar det binära filformatet i Excel. Sådana filer kan skapas av Microsoft Excel såväl som andra liknande kalkylprogram som OpenOffice Calc eller Apple Numbers. Läs mer om detta filformat[här](https://wiki.fileformat.com/specification/spreadsheet/xls/) . |
| static readonly [XLSB](../../groupdocs.watermark.common/filetype/xlsb) | XLSB-filformatet anger det binära filformatet för Excel, som är en samling poster och strukturer som anger innehållet i Excel-arbetsboken. Läs mer om detta filformat [här](https://wiki.fileformat.com/specification/spreadsheet/xlsb/) . |
| static readonly [XLSM](../../groupdocs.watermark.common/filetype/xlsm) | Filer med tillägget XLSM är en typ av kalkylbladsfiler som stöder makron. Läs mer om detta filformat [här](https://wiki.fileformat.com/specification/spreadsheet/xlsm/) . |
| static readonly [XLSX](../../groupdocs.watermark.common/filetype/xlsx) | XLSX är ett välkänt format för Microsoft Excel-dokument som introducerades av Microsoft med release av Microsoft Office 2007. Läs mer om detta filformat [här](https://wiki.fileformat.com/specification/spreadsheet/xlsx/) . |
| static readonly [XLT](../../groupdocs.watermark.common/filetype/xlt) | Filer med tillägget .XLT är mallfiler skapade med Microsoft Excel som är ett kalkylblad -program som kommer som en del av Microsoft Office-paketet. Läs mer om detta filformat [här](https://wiki.fileformat.com/specification/spreadsheet/xlt/) . |
| static readonly [XLTM](../../groupdocs.watermark.common/filetype/xltm) | Filtillägget XLTM representerar filer som genereras av Microsoft Excel som Macro-enabled mallfiler. Läs mer om detta filformat [här](https://wiki.fileformat.com/specification/spreadsheet/xltm/) . |
| static readonly [XLTX](../../groupdocs.watermark.common/filetype/xltx) | Filer med tillägget XLTX representerar Microsoft Excel-mallfiler som är baserade på Office OpenXML filformatspecifikationer. Läs mer om detta filformat [här](https://wiki.fileformat.com/specification/spreadsheet/xltx/) . |

### Anmärkningar

Den här klassen tillhandahåller metoder för att få en lista över alla filtyper som stöds av**GroupDocs.Watermark**.**Läs mer**

* [Dokumentformat som stöds](https://docs.groupdocs.com/display/watermarknet/Supported+Document+Formats)
* [Få filformat som stöds](https://docs.groupdocs.com/display/watermarknet/Get+supported+file+formats)
* [Få dokumentinformation](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### Se även

* namnutrymme [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* hopsättning [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
