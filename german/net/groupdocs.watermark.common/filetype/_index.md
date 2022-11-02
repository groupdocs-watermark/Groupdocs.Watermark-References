---
title: FileType
second_title: GroupDocs.Watermark für .NET-API-Referenz
description: Stellt den Dateityp dar.
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
| [Extension](../../groupdocs.watermark.common/filetype/extension) { get; } | Ermittelt das Suffix des Dateinamens (einschließlich des Punkts „.“), z. B. „.doc“. |
| [FileFormatName](../../groupdocs.watermark.common/filetype/fileformatname) { get; } | Ruft den Dateitypnamen ab, z. B. "Microsoft Word-Dokument". |
| [FormatFamily](../../groupdocs.watermark.common/filetype/formatfamily) { get; } | Ruft die Formatfamilie ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromExtension](../../groupdocs.watermark.common/filetype/fromextension)(string) | Ordnet die Dateierweiterung dem Dateityp zu. |
| [Equals](../../groupdocs.watermark.common/filetype/equals#equals)(FileType) | Bestimmt, ob der Strom[`FileType`](../filetype) ist die gleiche wie die angegebene[`FileType`](../filetype) Objekt. |
| override [Equals](../../groupdocs.watermark.common/filetype/equals#equals_1)(object) | Bestimmt, ob der Strom[`FileType`](../filetype) ist das gleiche wie das angegebene Objekt. |
| override [GetHashCode](../../groupdocs.watermark.common/filetype/gethashcode)() | Gibt einen Hash-Code für den Strom zurück[`FileType`](../filetype) Objekt. |
| override [ToString](../../groupdocs.watermark.common/filetype/tostring)() | Gibt eine Zeichenfolge zurück, die das aktuelle Objekt darstellt. |
| static [GetSupportedFileTypes](../../groupdocs.watermark.common/filetype/getsupportedfiletypes)() | Ruft die unterstützten Dateitypen ab. |
| [operator ==](../../groupdocs.watermark.common/filetype/op_equality) | Bestimmt, ob zwei[`FileType`](../filetype) Objekte sind gleich. |
| [operator !=](../../groupdocs.watermark.common/filetype/op_inequality) | Bestimmt, ob zwei[`FileType`](../filetype) Objekte sind nicht gleich. |

## Felder

| Name | Beschreibung |
| --- | --- |
| static readonly [BMP](../../groupdocs.watermark.common/filetype/bmp) | Dateien mit der Erweiterung .BMP stellen Bitmap-Bilddateien dar, die zum Speichern digitaler Bitmap-Bilder verwendet werden. Diese Bilder sind unabhängig vom Grafikadapter und werden auch als geräteunabhängige Bitmap-Datei (DIB) im -Format bezeichnet. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/image/bmp/) . |
| static readonly [DOC](../../groupdocs.watermark.common/filetype/doc) | Dateien mit der Erweiterung .doc stellen Dokumente dar, die von Microsoft Word oder anderen Textverarbeitungsdokumenten im binären Dateiformat generiert wurden. Weitere Informationen zu diesem Dateiformat [hier](https://wiki.fileformat.com/word-processing/doc/) . |
| static readonly [DOCM](../../groupdocs.watermark.common/filetype/docm) | DOCM-Dateien sind Microsoft Word 2007 oder höher erstellte Dokumente mit der Fähigkeit, Makros auszuführen. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/word-processing/docm/) . |
| static readonly [DOCX](../../groupdocs.watermark.common/filetype/docx) | DOCX ist ein bekanntes Format für Microsoft Word-Dokumente. Die Struktur dieses neuen Dokumentformats, das 2007 mit dem Release von Microsoft Office 2007 eingeführt wurde, wurde von einfachem Binary in eine Kombination aus XML- und Binärdateien geändert. Weitere Informationen zu diesem Dateiformat [hier](https://wiki.fileformat.com/word-processing/docx/) . |
| static readonly [DOT](../../groupdocs.watermark.common/filetype/dot) | Dateien mit der Erweiterung .DOT sind Vorlagendateien, die von Microsoft Word erstellt wurden, um vorformatierte Einstellungen für die Generierung weiterer DOC- oder DOCX-Dateien zu haben. Weitere Informationen zu diesem Dateiformat [hier](https://wiki.fileformat.com/word-processing/dot/) . |
| static readonly [DOTM](../../groupdocs.watermark.common/filetype/dotm) | Eine Datei mit DOTM-Erweiterung stellt eine Vorlagendatei dar, die mit Microsoft Word 2007 oder höher erstellt wurde. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/word-processing/dotm/) . |
| static readonly [DOTX](../../groupdocs.watermark.common/filetype/dotx) | Dateien mit DOTX-Erweiterung sind Vorlagendateien, die von Microsoft Word erstellt wurden, um vorformatierte Einstellungen für die Generierung weiterer DOCX-Dateien zu haben. Weitere Informationen zu diesem Dateiformat [hier](https://wiki.fileformat.com/word-processing/dotx/) . |
| static readonly [EML](../../groupdocs.watermark.common/filetype/eml) | Das EML-Dateiformat stellt E-Mail-Nachrichten dar, die mit Outlook und anderen relevanten Anwendungen gespeichert wurden. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/email/eml/) . |
| static readonly [EMLX](../../groupdocs.watermark.common/filetype/emlx) | Das EMLX-Dateiformat wird von Apple implementiert und entwickelt. Die Apple Mail-Anwendung verwendet das Dateiformat EMLX zum Exportieren der E-Mails. Weitere Informationen zu diesem Dateiformat [hier](https://wiki.fileformat.com/email/emlx/) . |
| static readonly [FlatOpc](../../groupdocs.watermark.common/filetype/flatopc) | Office Open XML WordprocessingML, gespeichert in einer flachen XML-Datei anstelle eines ZIP-Pakets (.xml). Weitere Informationen zu diesem Dateiformat[hier](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [FlatOpcMacroEnabled](../../groupdocs.watermark.common/filetype/flatopcmacroenabled) | Office Open XML WordprocessingML-Dokument mit Makros, das in einer flachen XML-Datei anstelle eines ZIP-Pakets (.xml) gespeichert wird. Weitere Informationen zu diesem Dateiformat[hier](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [FlatOpcTemplate](../../groupdocs.watermark.common/filetype/flatopctemplate) | Office Open XML WordprocessingML-Vorlage (ohne Makros), gespeichert in einer flachen XML-Datei anstelle eines ZIP-Pakets (.xml). Weitere Informationen zu diesem Dateiformat[hier](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [FlatOpcTemplateMacroEnabled](../../groupdocs.watermark.common/filetype/flatopctemplatemacroenabled) | Makrofähige Vorlage für Office Open XML WordprocessingML, gespeichert in einer flachen XML-Datei anstelle eines ZIP-Pakets (.xml). Weitere Informationen zu diesem Dateiformat[hier](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [GIF](../../groupdocs.watermark.common/filetype/gif) | Ein GIF oder Graphical Interchange Format ist eine Art stark komprimiertes Bild. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/image/gif/) . |
| static readonly [JPEG](../../groupdocs.watermark.common/filetype/jpeg) | Ein JPEG ist ein Bildformat, das mit der Methode der verlustbehafteten Komprimierung gespeichert wird. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/image/jpeg/) . |
| static readonly [JPF](../../groupdocs.watermark.common/filetype/jpf) | JPEG 2000 (JPF) ist ein Bildkodierungssystem und modernster Bildkompressionsstandard. Entworfen, mit Wavelet-Technologie JPEG 2000 kann verlustfreie Inhalte in jeder Qualität auf einmal codieren. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/image/jp2/) . |
| static readonly [JPG](../../groupdocs.watermark.common/filetype/jpg) | Ein JPEG ist ein Bildformat, das mit der Methode der verlustbehafteten Komprimierung gespeichert wird. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/image/jpeg/) . |
| static readonly [JPM](../../groupdocs.watermark.common/filetype/jpm) | JPEG 2000 (JPM) ist ein Bildkodierungssystem und modernster Bildkompressionsstandard. Entworfen, mit Wavelet-Technologie JPEG 2000 kann verlustfreie Inhalte in jeder Qualität auf einmal codieren. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/image/jp2/) . |
| static readonly [JPX](../../groupdocs.watermark.common/filetype/jpx) | JPEG 2000 (JPX) ist ein Bildkodierungssystem und modernster Bildkompressionsstandard. Entworfen, mit Wavelet-Technologie JPEG 2000 kann verlustfreie Inhalte in jeder Qualität auf einmal codieren. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/image/jp2/) . |
| static readonly [MSG](../../groupdocs.watermark.common/filetype/msg) | MSG ist ein Dateiformat, das von Microsoft Outlook und Exchange zum Speichern von E-Mail-Nachrichten, Kontakten, Terminen oder anderen Aufgaben verwendet wird. Weitere Informationen zu diesem Dateiformat [hier](https://wiki.fileformat.com/email/msg/) . |
| static readonly [ODT](../../groupdocs.watermark.common/filetype/odt) | ODT-Dateien sind Dokumenttypen, die mit Textverarbeitungsanwendungen erstellt wurden, die auf dem OpenDocument -Textdateiformat basieren. Diese werden mit Textverarbeitungsprogrammen wie dem kostenlosen OpenOffice Writer erstellt und können Inhalte wie Text, Bilder, Objekte und Stile enthalten. Weitere Informationen zu diesem Dateiformat [hier](https://wiki.fileformat.com/word-processing/odt/) . |
| static readonly [OFT](../../groupdocs.watermark.common/filetype/oft) | Dateien mit der Erweiterung .OFT stellen Nachrichtenvorlagendateien dar, die mit Microsoft Outlook erstellt wurden. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/email/oft/) . |
| static readonly [OOXML](../../groupdocs.watermark.common/filetype/ooxml) | Offene Office-XML-Datei (.ooxml). |
| static readonly [PDF](../../groupdocs.watermark.common/filetype/pdf) | Portable Document Format (PDF) ist ein Dokumenttyp, der von Adobe in den 1990er Jahren erstellt wurde. Der Zweck dieses -Dateiformats bestand darin, einen Standard für die Darstellung von Dokumenten und anderem Referenzmaterial in einzuführen, einem Format, das unabhängig von Anwendungssoftware, Hardware und Betriebssystem ist. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/view/pdf/) . |
| static readonly [PNG](../../groupdocs.watermark.common/filetype/png) | PNG, Portable Network Graphics, bezieht sich auf ein Rasterbild-Dateiformat, das verlustfreie Komprimierung verwendet. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/image/png/) . |
| static readonly [POTM](../../groupdocs.watermark.common/filetype/potm) | Dateien mit der Erweiterung POTM sind Microsoft PowerPoint-Vorlagendateien mit Unterstützung für Makros. POTM-Dateien werden mit PowerPoint 2007 oder höher erstellt und enthalten Standardeinstellungen, die zum Erstellen weiterer Präsentationsdateien verwendet werden können. Weitere Informationen zu diesem Dateiformat [hier](https://wiki.fileformat.com/presentation/potm/) . |
| static readonly [POTX](../../groupdocs.watermark.common/filetype/potx) | Dateien mit der Erweiterung .POTX stellen Microsoft PowerPoint-Vorlagenpräsentationen dar, die mit Microsoft PowerPoint 2007 und höher erstellt wurden. Weitere Informationen zu diesem Dateiformat [hier](https://wiki.fileformat.com/presentation/potx/) . |
| static readonly [PPS](../../groupdocs.watermark.common/filetype/pps) | PPS, PowerPoint-Diashow, Dateien werden mit Microsoft PowerPoint für Diashowzwecke erstellt. Das Lesen und Erstellen von PPS-Dateien wird von Microsoft PowerPoint 97-2003 unterstützt. Weitere Informationen zu diesem Dateiformat [hier](https://wiki.fileformat.com/presentation/pps/) . |
| static readonly [PPSM](../../groupdocs.watermark.common/filetype/ppsm) | Dateien mit der Erweiterung PPSM stellen ein mit Microsoft PowerPoint 2007 oder höher erstelltes makrofähiges Diashow-Dateiformat dar. Weitere Informationen zu diesem Dateiformat [hier](https://wiki.fileformat.com/presentation/ppsm/) . |
| static readonly [PPSX](../../groupdocs.watermark.common/filetype/ppsx) | PPSX, Power Point Diashow, Dateien werden mit Microsoft PowerPoint 2007 und höher für Diashow-Zwecke erstellt. Weitere Informationen zu diesem Dateiformat [hier](https://wiki.fileformat.com/presentation/ppsx/) . |
| static readonly [PPT](../../groupdocs.watermark.common/filetype/ppt) | Eine Datei mit PPT-Erweiterung stellt eine PowerPoint-Datei dar, die aus einer Sammlung von Folien für besteht, die als Diashow angezeigt werden. Es gibt das von Microsoft PowerPoint 97-2003 verwendete binäre Dateiformat an. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/presentation/ppt/) . |
| static readonly [PPTM](../../groupdocs.watermark.common/filetype/pptm) | Dateien mit PPTM-Erweiterung sind makrofähige Präsentationsdateien, die mit Microsoft PowerPoint 2007 oder höheren Versionen erstellt werden. Weitere Informationen zu diesem Dateiformat [hier](https://wiki.fileformat.com/presentation/pptm/) . |
| static readonly [PPTX](../../groupdocs.watermark.common/filetype/pptx) | Dateien mit der Erweiterung PPTX sind Präsentationsdateien, die mit der beliebten Microsoft PowerPoint-Anwendung erstellt wurden. Anders als die vorherige Version des Präsentationsdateiformats PPT, die binär war, basiert das PPTX-Format auf dem offenen XML-Präsentationsdateiformat von Microsoft PowerPoint. Weitere Informationen zu diesem Dateiformat [hier](https://wiki.fileformat.com/presentation/pptx/) . |
| static readonly [RTF](../../groupdocs.watermark.common/filetype/rtf) | Das von Microsoft eingeführte und dokumentierte Rich Text Format (RTF) stellt eine Methode zum Codieren von formatiertem Text und Grafiken zur Verwendung in Anwendungen dar. Das Format erleichtert den plattformübergreifenden Austausch von document mit anderen Microsoft-Produkten und dient somit dem Zweck der Interoperabilität. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/word-processing/rtf/) . |
| static readonly [TIF](../../groupdocs.watermark.common/filetype/tif) | TIFF oder TIF, Tagged Image File Format, stellt Rasterbilder dar, die für die Verwendung auf einer Vielzahl von Geräten bestimmt sind, die diesem Dateiformatstandard entsprechen. Weitere Informationen zu diesem Dateiformat [hier](https://wiki.fileformat.com/image/tiff/) . |
| static readonly [TIFF](../../groupdocs.watermark.common/filetype/tiff) | TIFF oder TIF, Tagged Image File Format, stellt Rasterbilder dar, die für die Verwendung auf einer Vielzahl von Geräten bestimmt sind, die diesem Dateiformatstandard entsprechen. Weitere Informationen zu diesem Dateiformat [hier](https://wiki.fileformat.com/image/tiff/) . |
| static readonly [Unknown](../../groupdocs.watermark.common/filetype/unknown) | steht für unbekannten Dateityp. |
| static readonly [VDW](../../groupdocs.watermark.common/filetype/vdw) | VDW ist das Dateiformat des Visio Graphics Service, das die Streams und Speicher angibt, die für das Rendern einer Webzeichnung erforderlich sind. Weitere Informationen zu diesem Dateiformat [hier](https://wiki.fileformat.com/web/vdw/) . |
| static readonly [VDX](../../groupdocs.watermark.common/filetype/vdx) | Alle Zeichnungen oder Diagramme, die in Microsoft Visio erstellt, aber im XML-Format gespeichert wurden, haben die Erweiterung .VDX. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/image/vdx/) . |
| static readonly [VSD](../../groupdocs.watermark.common/filetype/vsd) | VSD-Dateien sind Zeichnungen, die mit der Microsoft Visio-Anwendung erstellt wurden, um eine Vielzahl von grafischen -Objekten und die Verbindung zwischen diesen darzustellen. Weitere Informationen zu diesem Dateiformat [hier](https://wiki.fileformat.com/image/vsd/) . |
| static readonly [VSDM](../../groupdocs.watermark.common/filetype/vsdm) | Dateien mit der Erweiterung VSDM sind Zeichnungsdateien, die mit der Microsoft Visio-Anwendung erstellt wurden, die Makros unterstützt. Weitere Informationen zu diesem Dateiformat [hier](https://wiki.fileformat.com/image/vsdm/) . |
| static readonly [VSDX](../../groupdocs.watermark.common/filetype/vsdx) | Dateien mit der Erweiterung .VSDX stellen das Microsoft Visio-Dateiformat dar, das ab Microsoft Office 2013 eingeführt wurde. Weitere Informationen zu diesem Dateiformat [hier](https://wiki.fileformat.com/image/vsdx/) . |
| static readonly [VSS](../../groupdocs.watermark.common/filetype/vss) | VSS sind Schablonendateien, die mit Microsoft Visio 2007 und früher erstellt wurden. Schablonendateien stellen Drawing -Objekte bereit, die in eine .VSD-Visio-Zeichnung aufgenommen werden können. Weitere Informationen zu diesem Dateiformat [hier](https://wiki.fileformat.com/image/vss/) . |
| static readonly [VSSM](../../groupdocs.watermark.common/filetype/vssm) | Dateien mit der Erweiterung .VSSM sind Microsoft Visio-Schablonendateien, die Makros unterstützen. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/image/vssm/) . |
| static readonly [VSSX](../../groupdocs.watermark.common/filetype/vssx) | Dateien mit der Erweiterung .VSSX sind Zeichnungsschablonen, die mit Microsoft Visio 2013 und höher erstellt wurden. Weitere Informationen zu diesem Dateiformat [hier](https://wiki.fileformat.com/image/vssx/) . |
| static readonly [VST](../../groupdocs.watermark.common/filetype/vst) | Dateien mit der Endung VST sind Vektorbilddateien, die mit Microsoft Visio erstellt wurden und als Vorlage für zur Erstellung weiterer Dateien dienen. Weitere Informationen zu diesem Dateiformat [hier](https://wiki.fileformat.com/image/vst/) . |
| static readonly [VSTM](../../groupdocs.watermark.common/filetype/vstm) | Dateien mit der Erweiterung VSTM sind Vorlagendateien, die mit Microsoft Visio erstellt wurden und Makros unterstützen. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/image/vstm/) . |
| static readonly [VSTX](../../groupdocs.watermark.common/filetype/vstx) | Dateien mit VSTX-Erweiterungen sind Zeichnungsvorlagendateien, die mit Microsoft Visio 2013 und höher erstellt wurden. Weitere Informationen zu diesem Dateiformat [hier](https://wiki.fileformat.com/image/vstx/) . |
| static readonly [VSX](../../groupdocs.watermark.common/filetype/vsx) | Dateien mit der Erweiterung .VSX beziehen sich auf Schablonen, die aus Zeichnungen und Formen bestehen, die zum Erstellen von Diagrammen in Microsoft Visio verwendet werden. Weitere Informationen zu diesem Dateiformat [hier](https://wiki.fileformat.com/image/vsx/) . |
| static readonly [VTX](../../groupdocs.watermark.common/filetype/vtx) | Eine Datei mit der Erweiterung VTX ist eine Microsoft Visio-Zeichnungsvorlage, die im XML-Dateiformat auf einer Disc gespeichert wird. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/image/vtx/) . |
| static readonly [WEBP](../../groupdocs.watermark.common/filetype/webp) | WebP, eingeführt von Google, ist ein modernes Raster-Webbild-Dateiformat, das auf verlustfreier und verlustbehafteter Komprimierung basiert. Es bietet die gleiche Bildqualität, während die Bildgröße erheblich reduziert wird. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/image/webp/) . |
| static readonly [XLS](../../groupdocs.watermark.common/filetype/xls) | Dateien mit der Erweiterung XLS repräsentieren das Excel-Binärdateiformat. Solche Dateien können von Microsoft Excel sowie anderen ähnlichen Tabellenkalkulationsprogrammen wie OpenOffice Calc oder Apple Numbers erstellt werden. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/specification/spreadsheet/xls/) . |
| static readonly [XLSB](../../groupdocs.watermark.common/filetype/xlsb) | Das XLSB-Dateiformat gibt das Excel-Binärdateiformat an, bei dem es sich um eine Sammlung von Datensätzen und -Strukturen handelt, die den Inhalt von Excel-Arbeitsmappen angeben. Weitere Informationen zu diesem Dateiformat [hier](https://wiki.fileformat.com/specification/spreadsheet/xlsb/) . |
| static readonly [XLSM](../../groupdocs.watermark.common/filetype/xlsm) | Dateien mit der Erweiterung XLSM ist eine Art von Tabellenkalkulationsdatei, die Makros unterstützt. Weitere Informationen zu diesem Dateiformat [hier](https://wiki.fileformat.com/specification/spreadsheet/xlsm/) . |
| static readonly [XLSX](../../groupdocs.watermark.common/filetype/xlsx) | XLSX ist ein bekanntes Format für Microsoft Excel-Dokumente, das von Microsoft mit der Version von Microsoft Office 2007 eingeführt wurde. Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/specification/spreadsheet/xlsx/) . |
| static readonly [XLT](../../groupdocs.watermark.common/filetype/xlt) | -Dateien mit der Erweiterung .XLT sind Vorlagendateien, die mit Microsoft Excel erstellt wurden, einer Tabellenkalkulationsanwendung , die Teil der Microsoft Office-Suite ist. Weitere Informationen zu diesem Dateiformat [hier](https://wiki.fileformat.com/specification/spreadsheet/xlt/) . |
| static readonly [XLTM](../../groupdocs.watermark.common/filetype/xltm) | Die XLTM-Dateierweiterung stellt Dateien dar, die von Microsoft Excel als makrofähige -Vorlagendateien generiert werden. Weitere Informationen zu diesem Dateiformat [hier](https://wiki.fileformat.com/specification/spreadsheet/xltm/) . |
| static readonly [XLTX](../../groupdocs.watermark.common/filetype/xltx) | Dateien mit der Erweiterung XLTX stellen Microsoft Excel-Vorlagendateien dar, die auf den Office OpenXML -Dateiformatspezifikationen basieren. Weitere Informationen zu diesem Dateiformat [hier](https://wiki.fileformat.com/specification/spreadsheet/xltx/) . |

### Bemerkungen

Diese Klasse stellt Methoden bereit, um eine Liste aller unterstützten Dateitypen zu erhalten**GroupDocs.Watermark**.**Mehr erfahren**

* [Unterstützte Dokumentformate](https://docs.groupdocs.com/display/watermarknet/Supported+Document+Formats)
* [Holen Sie sich unterstützte Dateiformate](https://docs.groupdocs.com/display/watermarknet/Get+supported+file+formats)
* [Dokumentinformationen erhalten](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### Siehe auch

* namensraum [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* Montage [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
