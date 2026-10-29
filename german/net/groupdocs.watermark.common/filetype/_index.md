---
title: "FileType"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt den Dateityp dar."
type: docs
weight: 40
url: /de/net/groupdocs.watermark.common/filetype/
---
## FileType class

Stellt den Dateityp dar.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Extension](../../groupdocs.watermark.common/filetype/extension) { get; } | Liefert die Dateinamensuffix (einschließlich des Punktes "."), z. B. ".doc". |
| [FileFormatName](../../groupdocs.watermark.common/filetype/fileformatname) { get; } | Liefert den Dateitypnamen, z. B. "Microsoft Word Document". |
| [FormatFamily](../../groupdocs.watermark.common/filetype/formatfamily) { get; } | Liefert die Formatfamilie. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromExtension](../../groupdocs.watermark.common/filetype/fromextension)(string) | Ordnet die Dateierweiterung dem Dateityp zu. |
| [Equals](../../groupdocs.watermark.common/filetype/equals#equals)(FileType) | Bestimmt, ob der aktuelle [`FileType`](../filetype) derselbe ist wie das angegebene [`FileType`](../filetype)-Objekt. |
| override [Equals](../../groupdocs.watermark.common/filetype/equals#equals_1)(object) | Bestimmt, ob der aktuelle [`FileType`](../filetype) derselbe ist wie das angegebene Objekt. |
| override [GetHashCode](../../groupdocs.watermark.common/filetype/gethashcode)() | Gibt einen Hashcode für das aktuelle [`FileType`](../filetype)-Objekt zurück. |
| override [ToString](../../groupdocs.watermark.common/filetype/tostring)() | Gibt eine Zeichenkette zurück, die das aktuelle Objekt darstellt. |
| static [GetSupportedFileTypes](../../groupdocs.watermark.common/filetype/getsupportedfiletypes)() | Ruft die unterstützten Dateitypen ab. |
| [operator ==](../../groupdocs.watermark.common/filetype/op_equality) | Bestimmt, ob zwei [`FileType`](../filetype)-Objekte identisch sind. |
| [operator !=](../../groupdocs.watermark.common/filetype/op_inequality) | Bestimmt, ob zwei [`FileType`](../filetype)-Objekte nicht identisch sind. |

## Felder

| Name | Beschreibung |
| --- | --- |
| static readonly [BMP](../../groupdocs.watermark.common/filetype/bmp) | Dateien mit der Erweiterung .BMP stellen Bitmap‑Bilddateien dar, die zum Speichern von Bitmap‑Digitalbildern verwendet werden. Diese Bilder sind unabhängig vom Grafikadapter und werden auch als device independent bitmap (DIB)-Dateiformat bezeichnet. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://wiki.fileformat.com/image/bmp/). |
| static readonly [DOC](../../groupdocs.watermark.common/filetype/doc) | Dateien mit der Erweiterung .doc stellen Dokumente dar, die von Microsoft Word oder anderen Textverarbeitungsprogrammen im Binärdateiformat erzeugt werden. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://wiki.fileformat.com/word-processing/doc/). |
| static readonly [DOCM](../../groupdocs.watermark.common/filetype/docm) | DOCM‑Dateien sind von Microsoft Word 2007 oder höher erzeugte Dokumente mit der Möglichkeit, Makros auszuführen. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://wiki.fileformat.com/word-processing/docm/). |
| static readonly [DOCX](../../groupdocs.watermark.common/filetype/docx) | DOCX ist ein bekanntes Format für Microsoft‑Word‑Dokumente. Eingeführt ab 2007 mit der Veröffentlichung von Microsoft Office 2007, wurde die Struktur dieses neuen Dokumentenformats von reinem Binärformat zu einer Kombination aus XML‑ und Binärdateien geändert. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://wiki.fileformat.com/word-processing/docx/). |
| static readonly [DOT](../../groupdocs.watermark.common/filetype/dot) | Dateien mit der Erweiterung .DOT sind Vorlagendateien, die von Microsoft Word erstellt wurden, um vordefinierte Einstellungen für die Erstellung weiterer DOC‑ oder DOCX‑Dateien zu besitzen. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://wiki.fileformat.com/word-processing/dot/). |
| static readonly [DOTM](../../groupdocs.watermark.common/filetype/dotm) | Eine Datei mit der Erweiterung DOTM stellt eine Vorlagendatei dar, die mit Microsoft Word 2007 oder höher erstellt wurde. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://wiki.fileformat.com/word-processing/dotm/). |
| static readonly [DOTX](../../groupdocs.watermark.common/filetype/dotx) | Dateien mit der Erweiterung DOTX sind Vorlagendateien, die von Microsoft Word erstellt wurden, um vordefinierte Einstellungen für die Erstellung weiterer DOCX‑Dateien zu besitzen. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://wiki.fileformat.com/word-processing/dotx/). |
| static readonly [EML](../../groupdocs.watermark.common/filetype/eml) | Das EML‑Dateiformat stellt E‑Mail‑Nachrichten dar, die mit Outlook und anderen relevanten Anwendungen gespeichert wurden. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://wiki.fileformat.com/email/eml/). |
| static readonly [EMLX](../../groupdocs.watermark.common/filetype/emlx) | Das EMLX‑Dateiformat wird von Apple implementiert und entwickelt. Die Apple‑Mail‑Anwendung verwendet das EMLX‑Dateiformat zum Exportieren von E‑Mails. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://wiki.fileformat.com/email/emlx/). |
| static readonly [FlatOpc](../../groupdocs.watermark.common/filetype/flatopc) | Office Open XML WordprocessingML wird in einer flachen XML‑Datei anstelle eines ZIP‑Pakets (.xml) gespeichert. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [FlatOpcMacroEnabled](../../groupdocs.watermark.common/filetype/flatopcmacroenabled) | Office Open XML WordprocessingML Makro‑aktiviertes Dokument wird in einer flachen XML‑Datei anstelle eines ZIP‑Pakets (.xml) gespeichert. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [FlatOpcTemplate](../../groupdocs.watermark.common/filetype/flatopctemplate) | Office Open XML WordprocessingML-Vorlage (makrofrei) wird in einer flachen XML-Datei anstelle eines ZIP-Pakets (.xml) gespeichert. Erfahren Sie mehr über dieses Dateiformat [hier](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [FlatOpcTemplateMacroEnabled](../../groupdocs.watermark.common/filetype/flatopctemplatemacroenabled) | Office Open XML WordprocessingML-Makroaktivierte Vorlage wird in einer flachen XML-Datei anstelle eines ZIP-Pakets (.xml) gespeichert. Erfahren Sie mehr über dieses Dateiformat [hier](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [GIF](../../groupdocs.watermark.common/filetype/gif) | Ein GIF oder Graphical Interchange Format ist eine Art stark komprimiertes Bild. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/image/gif/). |
| static readonly [JPEG](../../groupdocs.watermark.common/filetype/jpeg) | Ein JPEG ist ein Bildformat, das mit verlustbehafteter Kompression gespeichert wird. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/image/jpeg/). |
| static readonly [JPF](../../groupdocs.watermark.common/filetype/jpf) | JPEG 2000 (JPF) ist ein Bildkodierungssystem und ein hochmodernes Bildkompressionsstandard. Durch die Verwendung von Wavelet‑Technologie kann JPEG 2000 verlustfreie Inhalte in beliebiger Qualität gleichzeitig codieren. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/image/jp2/). |
| static readonly [JPG](../../groupdocs.watermark.common/filetype/jpg) | Ein JPEG ist ein Bildformat, das mit verlustbehafteter Kompression gespeichert wird. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/image/jpeg/). |
| static readonly [JPM](../../groupdocs.watermark.common/filetype/jpm) | JPEG 2000 (JPM) ist ein Bildkodierungssystem und ein hochmodernes Bildkompressionsstandard. Durch die Verwendung von Wavelet‑Technologie kann JPEG 2000 verlustfreie Inhalte in beliebiger Qualität gleichzeitig codieren. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/image/jp2/). |
| static readonly [JPX](../../groupdocs.watermark.common/filetype/jpx) | JPEG 2000 (JPX) ist ein Bildkodierungssystem und ein hochmodernes Bildkompressionsstandard. Durch die Verwendung von Wavelet‑Technologie kann JPEG 2000 verlustfreie Inhalte in beliebiger Qualität gleichzeitig codieren. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/image/jp2/). |
| static readonly [MSG](../../groupdocs.watermark.common/filetype/msg) | MSG ist ein Dateiformat, das von Microsoft Outlook und Exchange verwendet wird, um E‑Mail‑Nachrichten, Kontakte, Termine oder andere Aufgaben zu speichern. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/email/msg/). |
| static readonly [ODT](../../groupdocs.watermark.common/filetype/odt) | ODT‑Dateien sind Dokumente, die mit Textverarbeitungsprogrammen erstellt werden, die auf dem OpenDocument‑Textdateiformat basieren. Sie werden mit Anwendungen wie dem kostenlosen OpenOffice Writer erzeugt und können Inhalte wie Text, Bilder, Objekte und Formatvorlagen enthalten. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/word-processing/odt/). |
| static readonly [OFT](../../groupdocs.watermark.common/filetype/oft) | Dateien mit der Erweiterung .OFT stellen Nachrichtenvorlagendateien dar, die mit Microsoft Outlook erstellt werden. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/email/oft/). |
| static readonly [OOXML](../../groupdocs.watermark.common/filetype/ooxml) | Office‑Open‑XML‑Datei (.ooxml). |
| static readonly [PDF](../../groupdocs.watermark.common/filetype/pdf) | Portable Document Format (PDF) ist ein Dokumenttyp, der von Adobe in den 1990er‑Jahren erstellt wurde. Ziel dieses Dateiformats war es, einen Standard für die Darstellung von Dokumenten und anderen Referenzmaterialien in einem Format einzuführen, das unabhängig von Anwendungssoftware, Hardware sowie Betriebssystem ist. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/view/pdf/). |
| static readonly [PNG](../../groupdocs.watermark.common/filetype/png) | PNG, Portable Network Graphics, bezeichnet ein Rastergrafik‑Dateiformat, das verlustfreie Kompression verwendet. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/image/png/). |
| static readonly [POTM](../../groupdocs.watermark.common/filetype/potm) | Dateien mit der POTM-Erweiterung sind Microsoft PowerPoint-Vorlagendateien mit Unterstützung für Makros. POTM-Dateien werden mit PowerPoint 2007 oder höher erstellt und enthalten Standard‑Einstellungen, die zur Erstellung weiterer Präsentationsdateien verwendet werden können. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/presentation/potm/). |
| static readonly [POTX](../../groupdocs.watermark.common/filetype/potx) | Dateien mit der .POTX-Erweiterung stellen Microsoft PowerPoint‑Vortragsvorlagen dar, die mit Microsoft PowerPoint 2007 und höher erstellt werden. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/presentation/potx/). |
| static readonly [PPS](../../groupdocs.watermark.common/filetype/pps) | PPS‑Dateien, PowerPoint‑Slide‑Show, werden mit Microsoft PowerPoint für Slide‑Show‑Zwecke erstellt. Das Lesen und Erstellen von PPS‑Dateien wird von Microsoft PowerPoint 97‑2003 unterstützt. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/presentation/pps/). |
| static readonly [PPSM](../../groupdocs.watermark.common/filetype/ppsm) | Dateien mit der PPSM-Erweiterung stellen ein Makro‑unterstütztes Slide‑Show‑Dateiformat dar, das mit Microsoft PowerPoint 2007 oder höher erstellt wurde. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/presentation/ppsm/). |
| static readonly [PPSX](../../groupdocs.watermark.common/filetype/ppsx) | PPSX‑Dateien, Power‑Point‑Slide‑Show, werden mit Microsoft PowerPoint 2007 und höher für Slide‑Show‑Zwecke erstellt. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/presentation/ppsx/). |
| static readonly [PPT](../../groupdocs.watermark.common/filetype/ppt) | Eine Datei mit der PPT-Erweiterung stellt eine PowerPoint‑Datei dar, die aus einer Sammlung von Folien für die Anzeige als Slide‑Show besteht. Sie gibt das von Microsoft PowerPoint 97‑2003 verwendete Binärdateiformat an. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/presentation/ppt/). |
| static readonly [PPTM](../../groupdocs.watermark.common/filetype/pptm) | Dateien mit der PPTM-Erweiterung sind Makro‑unterstützte Präsentationsdateien, die mit Microsoft PowerPoint 2007 oder neueren Versionen erstellt werden. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/presentation/pptm/). |
| static readonly [PPTX](../../groupdocs.watermark.common/filetype/pptx) | Dateien mit der PPTX-Erweiterung sind Präsentationsdateien, die mit der beliebten Microsoft PowerPoint‑Anwendung erstellt werden. Im Gegensatz zur vorherigen Version des Präsentationsdateiformats PPT, das binär war, basiert das PPTX‑Format auf dem offenen XML‑Präsentationsdateiformat von Microsoft PowerPoint. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/presentation/pptx/). |
| static readonly [RTF](../../groupdocs.watermark.common/filetype/rtf) | Von Microsoft eingeführt und dokumentiert, stellt das Rich‑Text‑Format (RTF) eine Methode zur Kodierung von formatiertem Text und Grafiken für die Verwendung in Anwendungen dar. Das Format erleichtert den plattformübergreifenden Dokumentenaustausch mit anderen Microsoft‑Produkten und dient damit der Interoperabilität. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/word-processing/rtf/). |
| static readonly [TIF](../../groupdocs.watermark.common/filetype/tif) | TIFF oder TIF, Tagged Image File Format, stellt Rasterbilder dar, die für die Verwendung auf einer Vielzahl von Geräten gedacht sind, die diesem Dateiformatstandard entsprechen. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/image/tiff/). |
| static readonly [TIFF](../../groupdocs.watermark.common/filetype/tiff) | TIFF oder TIF, Tagged Image File Format, stellt Rasterbilder dar, die für die Verwendung auf einer Vielzahl von Geräten gedacht sind, die diesem Dateiformatstandard entsprechen. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/image/tiff/). |
| static readonly [Unknown](../../groupdocs.watermark.common/filetype/unknown) | Stellt einen unbekannten Dateityp dar. |
| static readonly [VDW](../../groupdocs.watermark.common/filetype/vdw) | VDW ist das Visio‑Graphics‑Service‑Dateiformat, das die für die Darstellung einer Web‑Zeichnung erforderlichen Streams und Speicherbereiche festlegt. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/web/vdw/). |
| static readonly [VDX](../../groupdocs.watermark.common/filetype/vdx) | Jede Zeichnung oder Grafik, die in Microsoft Visio erstellt, aber im XML-Format gespeichert wurde, hat die .VDX-Erweiterung. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/image/vdx/). |
| static readonly [VSD](../../groupdocs.watermark.common/filetype/vsd) | VSD-Dateien sind Zeichnungen, die mit der Microsoft Visio‑Anwendung erstellt wurden, um eine Vielzahl von grafischen Objekten und deren Verbindungen darzustellen. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/image/vsd/). |
| static readonly [VSDM](../../groupdocs.watermark.common/filetype/vsdm) | Dateien mit der VSDM-Erweiterung sind Zeichnungsdateien, die mit der Microsoft Visio‑Anwendung erstellt wurden und Makros unterstützen. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/image/vsdm/). |
| static readonly [VSDX](../../groupdocs.watermark.common/filetype/vsdx) | Dateien mit der .VSDX-Erweiterung stellen das Microsoft Visio‑Dateiformat dar, das ab Microsoft Office 2013 eingeführt wurde. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/image/vsdx/). |
| static readonly [VSS](../../groupdocs.watermark.common/filetype/vss) | VSS sind Schablonendateien, die mit Microsoft Visio 2007 und früheren Versionen erstellt wurden. Schablonendateien stellen Zeichenobjekte bereit, die in einer .VSD‑Visio‑Zeichnung eingebunden werden können. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/image/vss/). |
| static readonly [VSSM](../../groupdocs.watermark.common/filetype/vssm) | Dateien mit der .VSSM-Erweiterung sind Microsoft Visio‑Schablonendateien, die Makros unterstützen. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/image/vssm/). |
| static readonly [VSSX](../../groupdocs.watermark.common/filetype/vssx) | Dateien mit der .VSSX-Erweiterung sind Zeichen‑Schablonen, die mit Microsoft Visio 2013 und neueren Versionen erstellt wurden. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/image/vssx/). |
| static readonly [VST](../../groupdocs.watermark.common/filetype/vst) | Dateien mit der VST-Erweiterung sind Vektor‑Bilddateien, die mit Microsoft Visio erstellt wurden und als Vorlage für die Erstellung weiterer Dateien dienen. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/image/vst/). |
| static readonly [VSTM](../../groupdocs.watermark.common/filetype/vstm) | Dateien mit der VSTM-Erweiterung sind Vorlagendateien, die mit Microsoft Visio erstellt wurden und Makros unterstützen. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/image/vstm/). |
| static readonly [VSTX](../../groupdocs.watermark.common/filetype/vstx) | Dateien mit der VSTX-Erweiterung sind Zeichen‑Vorlagendateien, die mit Microsoft Visio 2013 und neueren Versionen erstellt wurden. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/image/vstx/). |
| static readonly [VSX](../../groupdocs.watermark.common/filetype/vsx) | Dateien mit der .VSX-Erweiterung beziehen sich auf Schablonen, die aus Zeichnungen und Formen bestehen und zum Erstellen von Diagrammen in Microsoft Visio verwendet werden. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/image/vsx/). |
| static readonly [VTX](../../groupdocs.watermark.common/filetype/vtx) | Eine Datei mit VTX-Erweiterung ist eine Microsoft Visio‑Zeichnungsvorlage, die auf der Festplatte im XML‑Dateiformat gespeichert wird. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/image/vtx/). |
| static readonly [WEBP](../../groupdocs.watermark.common/filetype/webp) | WebP, von Google eingeführt, ist ein modernes rasterbasiertes Web‑Bilddateiformat, das auf verlustfreier und verlustbehafteter Kompression basiert. Es liefert dieselbe Bildqualität, reduziert jedoch die Dateigröße erheblich. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/image/webp/). |
| static readonly [XLS](../../groupdocs.watermark.common/filetype/xls) | Dateien mit der XLS-Erweiterung stellen das Excel‑Binary‑Dateiformat dar. Solche Dateien können von Microsoft Excel sowie von anderen ähnlichen Tabellenkalkulationsprogrammen wie OpenOffice Calc oder Apple Numbers erstellt werden. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/specification/spreadsheet/xls/). |
| static readonly [XLSB](../../groupdocs.watermark.common/filetype/xlsb) | Das XLSB-Dateiformat spezifiziert das Excel Binary File Format, das eine Sammlung von Datensätzen und Strukturen ist, die den Inhalt von Excel-Arbeitsmappen festlegen. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/specification/spreadsheet/xlsb/). |
| static readonly [XLSM](../../groupdocs.watermark.common/filetype/xlsm) | Dateien mit der XLSM-Erweiterung sind eine Art von Tabellenkalkulationsdateien, die Makros unterstützen. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/specification/spreadsheet/xlsm/). |
| static readonly [XLSX](../../groupdocs.watermark.common/filetype/xlsx) | XLSX ist ein bekanntes Format für Microsoft‑Excel‑Dokumente, das von Microsoft mit der Veröffentlichung von Microsoft Office 2007 eingeführt wurde. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/specification/spreadsheet/xlsx/). |
| static readonly [XLT](../../groupdocs.watermark.common/filetype/xlt) | Dateien mit der .XLT-Erweiterung sind Vorlagendateien, die mit Microsoft Excel erstellt wurden, einer Tabellenkalkulationsanwendung, die Teil der Microsoft‑Office‑Suite ist. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/specification/spreadsheet/xlt/). |
| static readonly [XLTM](../../groupdocs.watermark.common/filetype/xltm) | Die XLTM-Dateierweiterung steht für Dateien, die von Microsoft Excel als makrofähige Vorlagendateien erzeugt werden. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/specification/spreadsheet/xltm/). |
| static readonly [XLTX](../../groupdocs.watermark.common/filetype/xltx) | Dateien mit der XLTX-Erweiterung stellen Microsoft‑Excel‑Vorlagendateien dar, die auf den Office‑OpenXML-Dateiformatspezifikationen basieren. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/specification/spreadsheet/xltx/). |

### Hinweise

Diese Klasse stellt Methoden bereit, um die Liste aller von **GroupDocs.Watermark** unterstützten Dateitypen zu erhalten.**Mehr erfahren**

* [Supported Document Formats](https://docs.groupdocs.com/display/watermarknet/Supported+Document+Formats)
* [Get supported file formats](https://docs.groupdocs.com/display/watermarknet/Get+supported+file+formats)
* [Get document info](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### Siehe auch

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
