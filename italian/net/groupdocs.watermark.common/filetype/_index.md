---
title: FileType
second_title: Riferimento API GroupDocs.Watermark per .NET
description: Rappresenta il tipo di file.
type: docs
weight: 40
url: /it/net/groupdocs.watermark.common/filetype/
---
## FileType class

Rappresenta il tipo di file.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Extension](../../groupdocs.watermark.common/filetype/extension) { get; } | Ottiene il suffisso del nome del file (incluso il punto ".") ad es. ".doc". |
| [FileFormatName](../../groupdocs.watermark.common/filetype/fileformatname) { get; } | Ottiene il nome del tipo di file, ad esempio "Documento Microsoft Word". |
| [FormatFamily](../../groupdocs.watermark.common/filetype/formatfamily) { get; } | Ottiene la famiglia di formati. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromExtension](../../groupdocs.watermark.common/filetype/fromextension)(string) | Associa l'estensione del file al tipo di file. |
| [Equals](../../groupdocs.watermark.common/filetype/equals#equals)(FileType) | Determina se la corrente[`FileType`](../filetype) è uguale a quello specificato[`FileType`](../filetype) oggetto. |
| override [Equals](../../groupdocs.watermark.common/filetype/equals#equals_1)(object) | Determina se la corrente[`FileType`](../filetype) è uguale all'oggetto specificato. |
| override [GetHashCode](../../groupdocs.watermark.common/filetype/gethashcode)() | Restituisce un codice hash per la corrente[`FileType`](../filetype) oggetto. |
| override [ToString](../../groupdocs.watermark.common/filetype/tostring)() | Restituisce una stringa che rappresenta l'oggetto corrente. |
| static [GetSupportedFileTypes](../../groupdocs.watermark.common/filetype/getsupportedfiletypes)() | Recupera i tipi di file supportati. |
| [operator ==](../../groupdocs.watermark.common/filetype/op_equality) | Determina se due[`FileType`](../filetype) gli oggetti sono gli stessi. |
| [operator !=](../../groupdocs.watermark.common/filetype/op_inequality) | Determina se due[`FileType`](../filetype) gli oggetti non sono gli stessi. |

## Campi

| Nome | Descrizione |
| --- | --- |
| static readonly [BMP](../../groupdocs.watermark.common/filetype/bmp) | I file con estensione .BMP rappresentano i file di immagini bitmap che vengono utilizzati per memorizzare immagini digitali bitmap. Queste immagini sono indipendenti dall'adattatore grafico e sono anche chiamate file bitmap indipendenti dal dispositivo (DIB) formato. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/image/bmp/) . |
| static readonly [DOC](../../groupdocs.watermark.common/filetype/doc) | I file con estensione .doc rappresentano documenti generati da Microsoft Word o altri documenti di elaborazione testi in formato file binario. Ulteriori informazioni su questo formato di file [qui](https://wiki.fileformat.com/word-processing/doc/) . |
| static readonly [DOCM](../../groupdocs.watermark.common/filetype/docm) | I file DOCM sono documenti generati da Microsoft Word 2007 o versioni successive con la possibilità di eseguire macro. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/word-processing/docm/) . |
| static readonly [DOCX](../../groupdocs.watermark.common/filetype/docx) | DOCX è un formato ben noto per i documenti di Microsoft Word. Introdotto a partire dal 2007 con la release di Microsoft Office 2007, la struttura di questo nuovo formato di documento è stata modificata da semplice binary a una combinazione di file XML e binari. Ulteriori informazioni su questo formato di file [qui](https://wiki.fileformat.com/word-processing/docx/) . |
| static readonly [DOT](../../groupdocs.watermark.common/filetype/dot) | I file con estensione .DOT sono file modello creati da Microsoft Word per avere impostazioni preformattate per la generazione di ulteriori file DOC o DOCX. Ulteriori informazioni su questo formato di file [qui](https://wiki.fileformat.com/word-processing/dot/) . |
| static readonly [DOTM](../../groupdocs.watermark.common/filetype/dotm) | Un file con estensione DOTM rappresenta un file modello creato con Microsoft Word 2007 o versioni successive. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/word-processing/dotm/) . |
| static readonly [DOTX](../../groupdocs.watermark.common/filetype/dotx) | I file con estensione DOTX sono file modello creati da Microsoft Word per avere impostazioni preformattate per la generazione di ulteriori file DOCX. Ulteriori informazioni su questo formato di file [qui](https://wiki.fileformat.com/word-processing/dotx/) . |
| static readonly [EML](../../groupdocs.watermark.common/filetype/eml) | Il formato di file EML rappresenta i messaggi di posta elettronica salvati utilizzando Outlook e altre applicazioni pertinenti. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/email/eml/) . |
| static readonly [EMLX](../../groupdocs.watermark.common/filetype/emlx) | Il formato file EMLX è implementato e sviluppato da Apple. L'applicazione Apple Mail utilizza il formato di file EMLX per l'esportazione delle e-mail. Ulteriori informazioni su questo formato di file [qui](https://wiki.fileformat.com/email/emlx/) . |
| static readonly [FlatOpc](../../groupdocs.watermark.common/filetype/flatopc) | Office Open XML WordprocessingML memorizzato in un file XML piatto anziché in un pacchetto ZIP (.xml). Ulteriori informazioni su questo formato di file[qui](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [FlatOpcMacroEnabled](../../groupdocs.watermark.common/filetype/flatopcmacroenabled) | Office Open XML WordprocessingML Documento con attivazione macro memorizzato in un file XML flat anziché in un pacchetto ZIP (.xml). Ulteriori informazioni su questo formato di file[qui](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [FlatOpcTemplate](../../groupdocs.watermark.common/filetype/flatopctemplate) | Modello Office Open XML WordprocessingML (privo di macro) memorizzato in un file XML flat anziché in un pacchetto ZIP (.xml). Ulteriori informazioni su questo formato di file[qui](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [FlatOpcTemplateMacroEnabled](../../groupdocs.watermark.common/filetype/flatopctemplatemacroenabled) | Office Open XML WordprocessingML Modello con attivazione macro memorizzato in un file XML flat anziché in un pacchetto ZIP (.xml). Ulteriori informazioni su questo formato di file[qui](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [GIF](../../groupdocs.watermark.common/filetype/gif) | Un GIF o formato di interscambio grafico è un tipo di immagine altamente compressa. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/image/gif/) . |
| static readonly [JPEG](../../groupdocs.watermark.common/filetype/jpeg) | Un JPEG è un tipo di formato di immagine che viene salvato utilizzando il metodo di compressione con perdita. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/image/jpeg/) . |
| static readonly [JPF](../../groupdocs.watermark.common/filetype/jpf) | JPEG 2000 (JPF) è un sistema di codifica delle immagini e uno standard di compressione delle immagini all'avanguardia. Progettato, utilizzando la tecnologia wavelet JPEG 2000 può codificare contenuti senza perdita di qualsiasi qualità contemporaneamente. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/image/jp2/) . |
| static readonly [JPG](../../groupdocs.watermark.common/filetype/jpg) | Un JPEG è un tipo di formato di immagine che viene salvato utilizzando il metodo di compressione con perdita. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/image/jpeg/) . |
| static readonly [JPM](../../groupdocs.watermark.common/filetype/jpm) | JPEG 2000 (JPM) è un sistema di codifica delle immagini e uno standard di compressione delle immagini all'avanguardia. Progettato, utilizzando la tecnologia wavelet JPEG 2000 può codificare contenuti senza perdita di qualsiasi qualità contemporaneamente. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/image/jp2/) . |
| static readonly [JPX](../../groupdocs.watermark.common/filetype/jpx) | JPEG 2000 (JPX) è un sistema di codifica delle immagini e uno standard di compressione delle immagini all'avanguardia. Progettato, utilizzando la tecnologia wavelet JPEG 2000 può codificare contenuti senza perdita di qualsiasi qualità contemporaneamente. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/image/jp2/) . |
| static readonly [MSG](../../groupdocs.watermark.common/filetype/msg) | MSG è un formato di file utilizzato da Microsoft Outlook ed Exchange per archiviare messaggi di posta elettronica, contatti, appuntamenti o altre attività. Ulteriori informazioni su questo formato di file [qui](https://wiki.fileformat.com/email/msg/) . |
| static readonly [ODT](../../groupdocs.watermark.common/filetype/odt) | I file ODT sono tipi di documenti creati con applicazioni di elaborazione testi basate sul formato OpenDocument File di testo. Questi vengono creati con applicazioni di elaborazione testi come OpenOffice Writer gratuito e possono contenere contenuti come testo, immagini, oggetti e stili. Ulteriori informazioni su questo formato di file [qui](https://wiki.fileformat.com/word-processing/odt/) . |
| static readonly [OFT](../../groupdocs.watermark.common/filetype/oft) | I file con estensione .OFT rappresentano file modello di messaggio creati utilizzando Microsoft Outlook. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/email/oft/) . |
| static readonly [OOXML](../../groupdocs.watermark.common/filetype/ooxml) | File xml aperto da ufficio (.ooxml). |
| static readonly [PDF](../../groupdocs.watermark.common/filetype/pdf) | Portable Document Format (PDF) è un tipo di documento creato da Adobe negli anni '90. Lo scopo di questo formato di file era quello di introdurre uno standard per la rappresentazione di documenti e altro materiale di riferimento in un formato indipendente dal software applicativo, dall'hardware e dal sistema operativo. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/view/pdf/) . |
| static readonly [PNG](../../groupdocs.watermark.common/filetype/png) | PNG, Portable Network Graphics, si riferisce a un tipo di formato di file di immagine raster che utilizza la compressione senza perdita. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/image/png/) . |
| static readonly [POTM](../../groupdocs.watermark.common/filetype/potm) | I file con estensione POTM sono file modello di Microsoft PowerPoint con supporto per le macro. I file POTM vengono creati con PowerPoint 2007 o versioni successive e contengono impostazioni predefinite che possono essere utilizzate per creare ulteriori file di presentazione. Ulteriori informazioni su questo formato di file [qui](https://wiki.fileformat.com/presentation/potm/) . |
| static readonly [POTX](../../groupdocs.watermark.common/filetype/potx) | I file con estensione .POTX rappresentano presentazioni modello Microsoft PowerPoint create con Microsoft PowerPoint 2007 e versioni successive. Ulteriori informazioni su questo formato di file [qui](https://wiki.fileformat.com/presentation/potx/) . |
| static readonly [PPS](../../groupdocs.watermark.common/filetype/pps) | PPS, presentazione di diapositive di PowerPoint, i file vengono creati utilizzando Microsoft PowerPoint a scopo di presentazione. La lettura e la creazione di file PPS è supportata da Microsoft PowerPoint 97-2003. Ulteriori informazioni su questo formato di file [qui](https://wiki.fileformat.com/presentation/pps/) . |
| static readonly [PPSM](../../groupdocs.watermark.common/filetype/ppsm) | I file con estensione PPSM rappresentano il formato di file di presentazione con attivazione macro creato con Microsoft PowerPoint 2007 o versioni successive. Ulteriori informazioni su questo formato di file [qui](https://wiki.fileformat.com/presentation/ppsm/) . |
| static readonly [PPSX](../../groupdocs.watermark.common/filetype/ppsx) | PPSX, PowerPoint Slide Show, il file viene creato utilizzando Microsoft PowerPoint 2007 e versioni successive per lo scopo della presentazione. Ulteriori informazioni su questo formato di file [qui](https://wiki.fileformat.com/presentation/ppsx/) . |
| static readonly [PPT](../../groupdocs.watermark.common/filetype/ppt) | Un file con estensione PPT rappresenta un file PowerPoint costituito da una raccolta di diapositive per visualizzate come SlideShow. Specifica il formato di file binario utilizzato da Microsoft PowerPoint 97-2003. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/presentation/ppt/) . |
| static readonly [PPTM](../../groupdocs.watermark.common/filetype/pptm) | I file con estensione PPTM sono file di presentazione con attivazione macro creati con Microsoft PowerPoint 2007 o versioni successive. Ulteriori informazioni su questo formato di file [qui](https://wiki.fileformat.com/presentation/pptm/) . |
| static readonly [PPTX](../../groupdocs.watermark.common/filetype/pptx) | I file con estensione PPTX sono file di presentazione creati con la popolare applicazione Microsoft PowerPoint. A differenza della versione precedente del formato di file di presentazione PPT che era binario, il formato PPTX si basa sul formato di file di presentazione XML aperto di Microsoft PowerPoint. Ulteriori informazioni su questo formato di file [qui](https://wiki.fileformat.com/presentation/pptx/) . |
| static readonly [RTF](../../groupdocs.watermark.common/filetype/rtf) | Introdotto e documentato da Microsoft, il Rich Text Format (RTF) rappresenta un metodo di codifica di testo e grafica formattati per l'utilizzo all'interno delle applicazioni. Il formato facilita lo scambio multipiattaforma document con altri prodotti Microsoft, al fine di garantire l'interoperabilità. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/word-processing/rtf/) . |
| static readonly [TIF](../../groupdocs.watermark.common/filetype/tif) | TIFF o TIF, Tagged Image File Format, rappresenta le immagini raster destinate all'utilizzo su una varietà di dispositivi conformi a questo standard di formato file. Ulteriori informazioni su questo formato di file [qui](https://wiki.fileformat.com/image/tiff/) . |
| static readonly [TIFF](../../groupdocs.watermark.common/filetype/tiff) | TIFF o TIF, Tagged Image File Format, rappresenta le immagini raster destinate all'utilizzo su una varietà di dispositivi conformi a questo standard di formato file. Ulteriori informazioni su questo formato di file [qui](https://wiki.fileformat.com/image/tiff/) . |
| static readonly [Unknown](../../groupdocs.watermark.common/filetype/unknown) | Rappresenta un tipo di file sconosciuto. |
| static readonly [VDW](../../groupdocs.watermark.common/filetype/vdw) | VDW è il formato file di Visio Graphics Service che specifica i flussi e gli archivi necessari per il rendering di un disegno Web. Ulteriori informazioni su questo formato di file [qui](https://wiki.fileformat.com/web/vdw/) . |
| static readonly [VDX](../../groupdocs.watermark.common/filetype/vdx) | Qualsiasi disegno o grafico creato in Microsoft Visio, ma salvato in formato XML ha estensione .VDX. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/image/vdx/) . |
| static readonly [VSD](../../groupdocs.watermark.common/filetype/vsd) | I file VSD sono disegni creati con l'applicazione Microsoft Visio per rappresentare una varietà di oggetti grafici e l'interconnessione tra questi. Ulteriori informazioni su questo formato di file [qui](https://wiki.fileformat.com/image/vsd/) . |
| static readonly [VSDM](../../groupdocs.watermark.common/filetype/vsdm) | I file con estensione VSDM sono file di disegno creati con l'applicazione Microsoft Visio che supporta le macro. Ulteriori informazioni su questo formato di file [qui](https://wiki.fileformat.com/image/vsdm/) . |
| static readonly [VSDX](../../groupdocs.watermark.common/filetype/vsdx) | I file con estensione .VSDX rappresentano il formato di file Microsoft Visio introdotto da Microsoft Office 2013 in poi. Ulteriori informazioni su questo formato di file [qui](https://wiki.fileformat.com/image/vsdx/) . |
| static readonly [VSS](../../groupdocs.watermark.common/filetype/vss) | VSS sono file stencil creati con Microsoft Visio 2007 e versioni precedenti. I file stencil forniscono oggetti drawing che possono essere inclusi in un disegno .VSD Visio. Ulteriori informazioni su questo formato di file [qui](https://wiki.fileformat.com/image/vss/) . |
| static readonly [VSSM](../../groupdocs.watermark.common/filetype/vssm) | I file con estensione .VSSM sono file Microsoft Visio Stencil che supportano le macro. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/image/vssm/) . |
| static readonly [VSSX](../../groupdocs.watermark.common/filetype/vssx) | I file con estensione .VSSX stanno disegnando stencil creati con Microsoft Visio 2013 e versioni successive. Ulteriori informazioni su questo formato di file [qui](https://wiki.fileformat.com/image/vssx/) . |
| static readonly [VST](../../groupdocs.watermark.common/filetype/vst) | I file con estensione VST sono file di immagini vettoriali creati con Microsoft Visio e fungono da modello per la creazione di ulteriori file. Ulteriori informazioni su questo formato di file [qui](https://wiki.fileformat.com/image/vst/) . |
| static readonly [VSTM](../../groupdocs.watermark.common/filetype/vstm) | I file con estensione VSTM sono file modello creati con Microsoft Visio che supportano le macro. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/image/vstm/) . |
| static readonly [VSTX](../../groupdocs.watermark.common/filetype/vstx) | I file con estensioni VSTX sono file modello di disegno creati con Microsoft Visio 2013 e versioni successive. Ulteriori informazioni su questo formato di file [qui](https://wiki.fileformat.com/image/vstx/) . |
| static readonly [VSX](../../groupdocs.watermark.common/filetype/vsx) | I file con estensione .VSX si riferiscono a stencil costituiti da disegni e forme utilizzati per la creazione di diagrammi in Microsoft Visio. Ulteriori informazioni su questo formato di file [qui](https://wiki.fileformat.com/image/vsx/) . |
| static readonly [VTX](../../groupdocs.watermark.common/filetype/vtx) | Un file con estensione VTX è un modello di disegno di Microsoft Visio che viene salvato su disco in formato file XML. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/image/vtx/) . |
| static readonly [WEBP](../../groupdocs.watermark.common/filetype/webp) | WebP, introdotto da Google, è un moderno formato di file immagine web raster basato sulla compressione lossless e lossy. Fornisce la stessa qualità dell'immagine riducendo considerevolmente le dimensioni dell'immagine. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/image/webp/) . |
| static readonly [XLS](../../groupdocs.watermark.common/filetype/xls) | I file con estensione XLS rappresentano il formato di file binario di Excel. Tali file possono essere creati da Microsoft Excel così come altri programmi di fogli di calcolo simili come OpenOffice Calc o Apple Numbers. Ulteriori informazioni su questo formato di file[qui](https://wiki.fileformat.com/specification/spreadsheet/xls/) . |
| static readonly [XLSB](../../groupdocs.watermark.common/filetype/xlsb) | Il formato di file XLSB specifica il formato di file binario di Excel, che è una raccolta di record e strutture che specificano il contenuto della cartella di lavoro di Excel. Ulteriori informazioni su questo formato di file [qui](https://wiki.fileformat.com/specification/spreadsheet/xlsb/) . |
| static readonly [XLSM](../../groupdocs.watermark.common/filetype/xlsm) | I file con estensione XLSM sono un tipo di file Spreasheet che supportano le macro. Ulteriori informazioni su questo formato di file [qui](https://wiki.fileformat.com/specification/spreadsheet/xlsm/) . |
| static readonly [XLSX](../../groupdocs.watermark.common/filetype/xlsx) | XLSX è un formato noto per i documenti Microsoft Excel introdotto da Microsoft con la versione di Microsoft Office 2007. Ulteriori informazioni su questo formato file [qui](https://wiki.fileformat.com/specification/spreadsheet/xlsx/) . |
| static readonly [XLT](../../groupdocs.watermark.common/filetype/xlt) | I file con estensione .XLT sono file modello creati con Microsoft Excel che è un'applicazione spreadsheet che fa parte della suite Microsoft Office. Ulteriori informazioni su questo formato di file [qui](https://wiki.fileformat.com/specification/spreadsheet/xlt/) . |
| static readonly [XLTM](../../groupdocs.watermark.common/filetype/xltm) | L'estensione file XLTM rappresenta i file generati da Microsoft Excel come file modello Macro-enabled . Ulteriori informazioni su questo formato di file [qui](https://wiki.fileformat.com/specification/spreadsheet/xltm/) . |
| static readonly [XLTX](../../groupdocs.watermark.common/filetype/xltx) | I file con estensione XLTX rappresentano i file modello di Microsoft Excel basati sulle specifiche del formato di file Office OpenXML . Ulteriori informazioni su questo formato di file [qui](https://wiki.fileformat.com/specification/spreadsheet/xltx/) . |

### Osservazioni

Questa classe fornisce metodi per ottenere l'elenco di tutti i tipi di file supportati da**GroupDocs.Filigrana**.**Scopri di più**

* [Formati di documenti supportati](https://docs.groupdocs.com/display/watermarknet/Supported+Document+Formats)
* [Ottieni i formati di file supportati](https://docs.groupdocs.com/display/watermarknet/Get+supported+file+formats)
* [Ottieni informazioni sul documento](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### Guarda anche

* spazio dei nomi [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assemblea [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
